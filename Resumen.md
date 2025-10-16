# 🧠 Sistema de Inteligencia de Negocios – NETTALCO S.A.

## 📘 Descripción General

Proyecto desarrollado para el curso **SI807-U - Sistema de Inteligencia de Negocios** en la  
**Facultad de Ingeniería Industrial y de Sistemas – Universidad Nacional de Ingeniería**.

El sistema implementa un **Data Warehouse** y un **Dashboard Power BI** para la empresa **NETTALCO S.A.**, dedicada a la producción y exportación de prendas textiles.  
Su objetivo principal es analizar y optimizar los procesos de **producción, calidad, logística y rentabilidad** mediante un modelo **ETL completo** sobre el ecosistema **Hortonworks**.

---

## 👥 Equipo

| Integrante | Código |
|-------------|--------|
| Grijalva Parra, Francisco Leonel | 20220071I |
| Loayza Segura, Roger Salvador | 20220018K |
| Otero Vicente, Daniel Mauricio | 20220288H |

**Profesor:** Dr. Ing. Hilario Aradiel Castaneda  
**Ciclo:** 2025-II

---

## 🏢 Empresa Analizada

**NETTALCO S.A. – RUC 20100064571**  
Productora y exportadora de prendas de punto de algodón.  
**Ubicación:** Ca. Cinco 115 Urb. Vulcano, Ate – Lima, Perú.

---

## 🚀 Objetivo del Proyecto

Implementar una solución de **Inteligencia de Negocios (BI)** que permita:
- Analizar la eficiencia productiva y de calidad.
- Monitorear KPIs de producción, logística y rentabilidad.
- Consolidar fuentes OLTP en un modelo **Star Schema**.
- Diseñar un **cubo OLAP** para consultas multidimensionales.
- Visualizar resultados en **Power BI**.

---

## 🧩 Arquitectura General

**Tecnologías utilizadas:**
- **Hortonworks Sandbox**
- **HDFS** → Almacenamiento distribuido
- **Hive** → Data Warehouse / SQL analítico
- **Spark (Scala)** → Limpieza y transformación de datos
- **Power BI** → Dashboard interactivo
- **Excel / CSV** → Fuentes OLTP iniciales

**Capas del sistema:**
1. **Raw Layer:** Datos originales en formato CSV.  
2. **Staging Layer:** Limpieza y validación con Spark.  
3. **Curated Layer:** Tablas ORC normalizadas en Hive.  
4. **Dashboard:** Visualización de indicadores en Power BI.

---

## ⚙️ Requisitos del Sistema

- **Sistema operativo:** Windows 10 / Linux Ubuntu
- **VirtualBox o VMware**
- **Hortonworks Sandbox (versión 2.6+)**
- **Apache Spark 2.3+**
- **Hive 2.1+**
- **Power BI Desktop (opcional para visualizar el dashboard)**

---

## 🧱 Estructura del Repositorio

```
📂 SI807U-INE-20252/
│
├── 📄 README.md                → Este archivo
├── 📄 PARCIAL - G7.docx        → Informe completo del proyecto
├── 📊 NETALLCO - Dashboard.pbix → Dashboard Power BI
│
├── 📁 data/
│   ├── detalle-produccion-costura.csv
│   ├── eficiencia.csv
│   ├── produccion-costura-cliente.csv
│   ├── produccion-costura-linea-cliente.csv
│   └── segundas-prendas.csv
│
├── 📁 scripts/
│   ├── create_tables_raw.hql       → Tablas externas (Raw)
│   ├── create_tables_curated.hql   → Tablas ORC (Curated)
│   ├── etl_transform.scala         → Script de transformación con Spark
│   └── load_fact_produccion.hql    → Inserción de datos en tabla de hechos
│
└── 📁 images/
    └── evidencias/ (Capturas del entorno Hortonworks)
```

---

## 🧮 Estructura del Data Warehouse

**Esquema en estrella (Star Schema):**
- **Hechos:** `fact_produccion`
- **Dimensiones:** `dim_tiempo`, `dim_linea`, `dim_producto`, `dim_cliente`

### Medidas clave:
- Total de prendas producidas (`SUM(prendas)`)
- Eficiencia promedio (`AVG(eficiencia)`)
- % Segundas (`AVG(porc_segundas)`)

---

## 🧰 Cómo Ejecutar el Proyecto

1. **Descargar el repositorio**
   ```bash
   git clone https://github.com/Grijalva1234/SI807U-INE-20252.git
   cd SI807U-INE-20252
   ```

2. **Levantar la VM de Hortonworks**
   - Abrir en **VirtualBox / VMware**
   - Usuario: `maria_dev`
   - Contraseña: `maria_dev`

3. **Cargar los archivos CSV en HDFS**
   ```bash
   hdfs dfs -mkdir /data/raw/
   hdfs dfs -put data/*.csv /data/raw/
   ```

4. **Ejecutar scripts en Hive**
   ```bash
   hive -f scripts/create_tables_raw.hql
   hive -f scripts/create_tables_curated.hql
   hive -f scripts/load_fact_produccion.hql
   ```

5. **Ejecutar el script de transformación (Spark)**
   ```bash
   spark-shell -i scripts/etl_transform.scala
   ```

6. **Validar tablas y consultas**
   ```sql
   SHOW TABLES IN dw_curated;
   SELECT COUNT(*) FROM dw_curated.fact_produccion;
   ```

7. **Abrir el Dashboard**
   - Archivo: [`NETALLCO - Dashboard.pbix`](https://github.com/Grijalva1234/SI807U-INE-20252/blob/main/NETALLCO%20-%20Dashboard.pbix)
   - Fuente de datos: conexión ODBC a Hive (Hortonworks Sandbox)

---

## 📈 Resultados Principales

- Consolidación de 6 datasets OLTP en un único modelo analítico.
- Estructura de datos particionada por año y mes.
- KPIs clave:
  - Eficiencia promedio mensual.
  - Porcentaje de segundas.
  - Producción total por cliente y línea.
- Dashboard Power BI con semáforos de rendimiento y vistas comparativas.

---

## 💡 Propuestas de Mejora

- Automatizar el flujo ETL con **Apache NiFi**.  
- Escalar la infraestructura a un clúster Hadoop distribuido.  
- Integrar un motor OLAP como **Apache Kylin** para análisis en tiempo real.  
- Incluir control de calidad y catálogo maestro de datos.

---

## 📚 Referencias

- [Power BI Documentation](https://learn.microsoft.com/es-es/power-bi/)
- [Hortonworks Docs](https://docs.cloudera.com/HDPDocuments/)
- [Apache Spark](https://spark.apache.org/)
- [IBM – Business Intelligence](https://www.ibm.com/blogs/systems/es-es/tag/business-intelligence/)
- [Ceintec – Inteligencia de Negocios y Big Data](http://www.ceintec.com/inteligencia-de-negocios-y-big-data)

---

**📅 Proyecto académico – Universidad Nacional de Ingeniería (2025-II)**  
Desarrollado por el **Grupo 5 – SI807U**
