# UNIVERSIDAD NACIONAL DE INGENIERÍA  
## FACULTAD DE INGENIERÍA INDUSTRIAL Y DE SISTEMAS  

**“NETTALCO”**  

**Curso:** SI807-U SISTEMA DE INTELIGENCIA DE NEGOCIOS  
**Grupo 5**  

**Integrantes:**  
- Grijalva Parra, Francisco Leonel – 20220071I  
- Loayza Segura, Roger Salvador – 20220018K  
- Otero Vicente, Daniel Mauricio – 20220288H  

**Profesor:** Dr. Ing. Aradiel Castaneda, Hilario  
**Ciclo:** 2025-II  

---

## 1. Generalidades de la empresa  

### 1.1 Nombre o razón social de la empresa  
**NETTALCO S.A. – RUC 20100064571**

### 1.2 Giro de la empresa  
Nettalco es una empresa textil y de confecciones verticalmente integrada, localizada en Lima, Perú. Se dedica a la producción y exportación de prendas de tejido de punto de algodón y mezclas, por encargo de clientes internacionales. Actúa como *contract manufacturer*, elaborando prendas de vestir conforme a los diseños y especificaciones de sus clientes.  

### 1.3 Ubicación de la empresa  
**Ca. Cinco 115 Urb. Vulcano, Ate – Lima, Perú**

### 1.4 Misión y Visión  
- **Misión:** Brindar un producto y servicio de calidad a nuestros clientes basados en los más altos estándares internacionales.  
- **Visión:** Posicionarnos como empresa peruana exportadora de prendas de vestir líder como *contract manufacturer* a nivel mundial.  

### 1.5 Productos y clientes  
**Productos:**  
- Prendas con hilados 100% de algodón: Pima Peruano, Supima, Upland y Algodón Orgánico.  
- Mezclas con fibras como LYCRA®, Poliéster, Micromodal, Bamboo.  

**Clientes:**  
- Lands’End  
- L.L.Bean  
- Hanna Andersson  
- Lacoste  
- The Company Store  
- Smaller Things  
- Radmor  
- Ricardo Almeida  

### 1.6 Organigrama  
<img width="879" height="593" alt="image" src="https://github.com/user-attachments/assets/0e5bf333-e824-48b3-b4d5-496895994e17" />


### 1.7 Mapa de procesos y subprocesos  
<img width="891" height="360" alt="image" src="Captura de pantalla 2025-09-24 115414.png" />


### 1.8 Cadena de valor  
La cadena de valor de Nettalco está integrada verticalmente, controlando desde la obtención de materias primas hasta la entrega final.  

**Actividades primarias:**  
- Producción y abastecimiento de materia prima.  
- Diseño y desarrollo de productos.  
- Fabricación y confección.  
- Control de calidad.  
- Distribución y logística.  

**Actividades de soporte:**  
- Gestión tecnológica.  
- Recursos humanos.  
- Infraestructura.  
- Compras y aprovisionamiento.  

### 1.9 Modelo de negocio  
*(Pendiente)*  

---

## 2. Identificación de Problemas del Negocio  

### 2.1 Problemática  

**Internacional:**  
- Competencia global con precios bajos (China, India, Bangladesh).  
- Fluctuaciones en el costo del algodón.  
- Tendencias de sostenibilidad y responsabilidad social.  

**Nacional (Perú):**  
- Acceso limitado a tecnologías avanzadas.  
- Infraestructura logística deficiente.  
- Competencia interna en la industria textil.  

**Local (Lima):**  
- Limitada mano de obra calificada.  
- Demanda creciente de sostenibilidad.  
- Altos costos operativos (logística, transporte, regulaciones).  

### 2.2 Formulación del problema  

**Problema general:**  
Nettalco enfrenta un aumento significativo en los costos de las telas, reduciendo su capacidad de producción y cumplimiento de plazos de entrega.  

**Problemas específicos:**  
- **Internacional:** Aumento de precios internacionales de materias primas.  
- **Nacional:** Escasez de proveedores locales confiables.  
- **Local:** Procesos manuales sin suficiente automatización.  

**Justificación:**  
El incremento en el costo de telas y la falta de automatización amenazan la rentabilidad, competitividad y cumplimiento de contratos internacionales.  

---

## 3. Necesidades de Información y Decisiones Críticas  

| Nivel       | Tipo de decisión | Necesidad de información |
|-------------|------------------|---------------------------|
| Estratégico | Competitividad, expansión, sostenibilidad | Costos de producción, rentabilidad por cliente, proyecciones de demanda |
| Táctico     | Planificación en producción, logística, clientes | Cumplimiento de plazos, eficiencia operativa, cadena de suministro |
| Operativo   | Procesos y control de calidad | Tasa de defectos, tiempos de producción, utilización de maquinaria, inventarios |

---

## 4. KPI’s iniciales  

### 4.1 KPIs de Producción  

| KPI | Definición | Fórmula | Unidad | Frecuencia | Semáforo |
|-----|------------|---------|--------|------------|----------|
| Tasa de defectos | % de prendas defectuosas | (Defectuosas / Total) * 100 | % por lote | Diario | ✅ ≤2%, 🟡 3–5%, 🔴 >5% |
| Tiempo de producción por lote | Tiempo total hasta producto final | Horas totales / Nº de lotes | Horas/lote | Diario | ✅ ≤48h, 🟡 49–72h, 🔴 >72h |
| Utilización de maquinaria | % tiempo activo | (Tiempo activo / Tiempo total) * 100 | % | Semanal | ✅ ≥85%, 🟡 70–84%, 🔴 <70% |

### 4.2 KPIs de Cadena de Suministro  

| KPI | Definición | Fórmula | Unidad | Frecuencia | Semáforo |
|-----|------------|---------|--------|------------|----------|
| Tiempo de entrega de materia prima | Pedido → llegada a planta | Recepción – Pedido | Días | Mensual | ✅ ≤5, 🟡 6–10, 🔴 >10 |
| Costo de transporte y logística | % sobre costo total | (Gastos logística / Costo total) * 100 | % o USD/unidad | Mensual | ✅ ≤5%, 🟡 6–10%, 🔴 >10% |

### 4.3 KPIs de Ventas y Clientes  

| KPI | Definición | Fórmula | Unidad | Frecuencia | Semáforo |
|-----|------------|---------|--------|------------|----------|
| Cumplimiento de plazos | % pedidos a tiempo | (Pedidos a tiempo / Total) * 100 | % | Semanal | ✅ ≥95%, 🟡 85–94%, 🔴 <85% |
| Satisfacción del cliente | Encuestas 1–10 | Promedio | Puntos | Trimestral | ✅ ≥8, 🟡 6–7, 🔴 ≤5 |
| Volumen de ventas por región/cliente | Comparación de pedidos | Σ Pedidos por región/cliente | Nº pedidos / USD | Mensual | Meta definida |

### 4.4 KPIs Financieros  

| KPI | Definición | Fórmula | Unidad | Frecuencia | Semáforo |
|-----|------------|---------|--------|------------|----------|
| Margen de utilidad por producto | (Precio – Costo) / Precio * 100 | % de margen | % | Mensual | ✅ ≥30%, 🟡 20–29%, 🔴 <20% |
| Costo por unidad producida | Costo total / Unidades | USD/prenda | USD/prenda | Mensual | ✅ ≤10, 🟡 11–15, 🔴 >15 |

---



## 5. Evidencia Tecnica - Parte 1

### 5.1 Implementación de HortonWorks 

#### 5.1.1 Capturas de pantalla de la VM mostrando:

##### Caracteristicas del sistema e inicializacion

<img width="891" height="360" alt="image" src="Captura de pantalla 2025-09-24 114953.png" />

##### modificación de contraseñas

<img width="891" height="360" alt="image" src="Captura de pantalla 2025-09-24 115026.png" />

##### Servicios en ejecucion en Ambari

<img width="891" height="360" alt="image" src="Captura de pantalla 2025-09-24 115053.png" />

##### Version de Spark

<img width="891" height="360" alt="image" src="Captura de pantalla 2025-09-24 115120.png" />

##### Servicio HDFS y HIVE

<img width="891" height="360" alt="image" src="Captura de pantalla 2025-09-24 115200.png" />

### 5.2 Diagrama de Arquitectura Inicial  

<img width="891" height="360" alt="image" src="Captura de pantalla 2025-09-24 115254.png" />

## 6. Preguntas del Negocio

| Área                  | Rol del Usuario                  | Pregunta de Negocio                                                                                   | Nivel de Prioridad | Fuente de Datos Actual         |
|-----------------------|----------------------------------|--------------------------------------------------------------------------------------------------------|--------------------|--------------------------------|
| Ventas y Marketing    | Gerente de Ventas / Marketing    | ¿Cómo mejorar las ventas por canal? / ¿Qué canal genera mayor rendimiento? / ¿Qué campañas han generado mayor ROI? | Alta               | CRM, Sistema de Ventas         |
| Inventario y Logística| Gerente de Inventario / Producción | ¿Cómo optimizar niveles de inventario? / ¿Qué productos tienen exceso o escasez? / ¿Cómo predecir demanda? | Alta               | Sistema de Inventario y Logística |
| Clientes              | Gerente de Ventas / Asistente de Ventas | ¿Quiénes son los mejores clientes y cómo retenerlos? / ¿Qué clientes han disminuido compras? / ¿Cómo mejorar la satisfacción del cliente? | Alta | CRM, Sistema de Ventas |
| Finanzas y Rentabilidad | Gerente de Finanzas             | ¿Qué productos son más rentables? / ¿Cuál es el margen de beneficio por producto? / ¿Cómo optimizar flujo de caja? | Alta | ERP, Sistema Contable |
| Operaciones           | Gerente de Producción            | ¿Cómo mejorar la eficiencia operativa? / ¿Dónde están los cuellos de botella?                           | Media              | ERP, Sistema de Producción     |
| Planificación Estratégica | Alta Gerencia                 | ¿Cómo proyectar ventas futuras? / ¿Qué factores afectan más nuestras proyecciones?                      | Media              | Datos Históricos de Ventas     |

---

## 7. KPI’s definidos (Logística, Producción, Calidad y RRHH)

Con estas preguntas defninimos los KPI’s:

| Nombre                    | KPI                 | Descripción                                              | Fórmula                                    | Unidad             | Periodicidad   | Fuente de Datos              | Responsable            |
|---------------------------|---------------------|----------------------------------------------------------|--------------------------------------------|--------------------|----------------|------------------------------|------------------------|
| Rotación de Inventario    | Inventario / Logística | Mide cuántas veces se vende y repone el inventario       | Costo de Ventas / Inventario Promedio      | Veces              | Mensual        | Sistema de Inventario        | Gerente de Inventario  |
| Días de Inventario Disponible | Inventario / Logística | Promedio de días que los productos permanecen en stock   | Inventario Promedio / (Costo Ventas / 365) | Días               | Mensual        | Sistema de Inventario        | Gerente de Inventario  |
| Stock Crítico             | Inventario / Logística | Identifica productos por debajo del nivel mínimo requerido | —                                          | Unidades           | Diario/Semanal | Sistema de Inventario        | Gerente de Inventario  |
| Tiempo de Ciclo de Reabastecimiento | Logística        | Tiempo desde la solicitud hasta la disponibilidad        | Fecha Disponibilidad – Fecha Pedido        | Días               | Mensual        | Sistema de Logística y Proveedores | Gerente de Logística |
| Tiempo Promedio de Producción | Producción          | Tiempo promedio necesario para fabricar cada prenda       | Σ Horas / Nº Prendas                       | Horas              | Diario/Mensual | Sistema de Producción        | Gerente de Producción |
| Índice de Eficiencia de Producción | Producción       | % de productos terminados vs planificados                | (Prendas Terminadas / Prendas Planificadas) * 100 | %          | Mensual        | ERP / Producción             | Gerente de Producción |
| Tasa de Desperdicio       | Producción / Calidad | Proporción de material desperdiciado en la producción    | Material Desperdiciado / Material Total * 100 | %              | Mensual        | ERP / Producción             | Gerente de Producción |
| Incidentes de Riesgo Operativo | Calidad / Producción | Número de incidentes que afectan las operaciones         | Conteo de incidentes registrados           | Nº                 | Mensual        | Sistema de Riesgos / Producción | Jefe de Calidad      |
| Conformidad Regulatoria   | Calidad             | Nivel de cumplimiento normativo                          | Nº Cumplimientos / Nº Total Requisitos * 100 | %               | Trimestral     | Sistema de Cumplimiento      | Jefe de Calidad       |
| Satisfacción del Personal | RRHH                | Nivel de satisfacción de empleados en encuestas internas | Σ Puntuaciones / Nº Encuestados            | %                  | Semestral      | Sistema de RRHH              | Gerente de RRHH       |
| Productividad del Personal | RRHH               | Medida de prendas producidas por trabajador              | Prendas Totales / Nº Trabajadores          | Unidades/Empleado  | Mensual        | Sistema de RRHH / Producción | Gerente de RRHH       |

---

## 8. Modelado preliminar

### 8.1. Modelado conceptual preliminar

En base a la información planteamos el siguiente modelo conceptual:

<img width="886" height="373" alt="image" src="Captura de pantalla 2025-10-01 121833.png" />

Captura de pantalla 2025-10-01 121833
---

### 8.2. Modelo lógico (Star Schema)

Recordemos que:

#### Tablas de dimensiones
Todas las tablas de dimensiones deben contener información clara y categorizada que permita análisis detallados. Esto incluye:

- **Dim_Producto**: Contendrá jerarquías de producto como tipo de tela, categoría de prenda, color, etc.  
- **Dim_Tiempo**: Deberá estar estructurada con atributos de granularidad temporal (día, mes, trimestre, año).  
- **Dim_Cliente**: Agrupará datos por región, país, segmento de mercado, etc.  
- **Dim_Empleado** y **Dim_Máquina**: Con información sobre el personal y los equipos para analizar eficiencia en producción.  

#### Tablas de hechos
Las tablas de hechos deben estar diseñadas para facilitar el análisis a distintos niveles de detalle, por ejemplo:  

- Ventas por categoría de producto.  
- Inventario a lo largo del tiempo.  

<img width="795" height="584" alt="image" src="https://github.com/user-attachments/assets/564fedf7-ba07-496d-a13c-9d61a8a10a97" />

## 9. Inventario de fuentes OLTP

Durante la revisión de la fuente de datos, se verificó que la información recopilada proviene de fuentes confiables y autorizadas. Se comprobó la coherencia, precisión y completitud de los datos para asegurar su validez en el análisis. Adicionalmente, se evaluó la calidad de los datos considerando su relevancia y actualidad para el propósito del proyecto. Todos los datos fueron procesados conforme a los estándares de integridad y confidencialidad requeridos.

| Sistema                           | Área Usuaria         | Tipo | Tecnología          | Frecuencia de Actualización | Observaciones                                    |
|-----------------------------------|----------------------|------|---------------------|-----------------------------|------------------------------------------------|
| Sistema de Inventario y Aprovisionamiento | Logística / Producción | OLTP | ERP Exactus (Oracle) | 24 horas                    | Maneja stock de telas, hilos y accesorios       |
| Sistema de Control de Calidad     | Producción / Calidad | OLTP | ERP Exactus (Oracle) | 24 horas                    | Registra prendas aprobadas/rechazadas           |
| Sistema de Costura y Producción   | Producción           | OLTP | ERP Exactus (Oracle) | 24 horas                    | Mide productividad, tiempos y residuos          |
| Sistema de Acabado y Embalaje     | Producción / Logística | OLTP | ERP Exactus (Oracle) | 24 horas                    | Registra prendas terminadas, costos de embalaje |
| Sistema de Distribución y Logística | Logística          | OLTP | ERP Exactus (Oracle) | 24 horas                    | Controla despachos, costos logísticos           |
| Sistema de Gestión de Tecnología y Equipos | Mantenimiento   | OLTP | ERP Exactus (Oracle) | 24 horas                    | Reportes de mantenimiento y fallas              |
| Sistema de Recursos Humanos y Capacitación | RRHH           | OLTP | ERP Exactus (Oracle) | 24 horas                    | Productividad del personal y capacitación       |

---

## 10. Evidencia técnica – Parte 2




### 10.1. Archivos cargados en HDFS
Seguiremos los siguientes pasos:
1. Creamos el archivo donde guardaremos el proyecto "Sistema_Inteligencia_Negocios_25-2"
2. Convertimos nuestros archivos excel donde tenemos la informacion en archivos csv
3. Procedemos a subir cada archivo al HDFS.
<img width="891" height="360" alt="image" src="Captura de pantalla 2025-10-01 114534.png" />

### 10.2. Scripts CREATE EXTERNAL TABLE en Hive

Para realizar las consultas en Hive, nos dirigimos a la opcion "Hive View", como se muestra en la imagen:

<img width="891" height="360" alt="image" src="Captura de pantalla 2025-10-01 114607.png" />

A continuación, un ejemplo del script utilizado para crear tablas externas en Hive:

```sql
CREATE EXTERNAL TABLE detalle_produccion_costura (
    ORDEN_PRODUCCION STRING,
    SECUENCIA_PAQUETE INT,
    ESTILO STRING,
    TALLA STRING,
    PRENDAS INT,
    FECHA_TERMINO TIMESTAMP
)
ROW FORMAT DELIMITED
FIELDS TERMINATED BY ','
STORED AS TEXTFILE
LOCATION '/Sistema_Inteligencia_Negocios_25-2/detalle-produccion-costura/'
TBLPROPERTIES ("skip.header.line.count"="1");
';
```

---

### 10.3. Resultados de consulta simple
Queremos saber que tipo de producto se vendio mas, para ser mas precisos los 5 con mas ventas.
Para ello hacemos la siguiente consulta:
```sql
SELECT categoria_producto, SUM(ventas) AS total_ventas
FROM detalle_produccion_costura
GROUP BY categoria_producto
ORDER BY total_ventas DESC
LIMIT 5;
```

Con lo cual nos sale la siguiente tabla:
<img width="891" height="360" alt="image" src="Captura de pantalla 2025-10-01 113649.png" />

---

## 11. Diseño del proceso ETL

El proceso **ETL (Extract, Transform, Load)** se desarrolló íntegramente en el entorno **Hortonworks Sandbox**, utilizando las herramientas nativas del ecosistema Hadoop:

- **HDFS** para almacenamiento  
- **Spark** para procesamiento  
- **Hive** como motor de base de datos analítica

---

### 🔁 Flujo general

Se diseñó un flujo estructurado que inicia con la extracción de los reportes Excel proporcionados por el área de producción y termina con la carga de datos consolidados en tablas Hive, preparadas para análisis y visualización.

El proceso se estructuró en tres fases principales:

---

### 🟩 1. Extracción (Extract)

Se recopilaron los siguientes archivos:

- `detalle-produccion-costura(1).xlsx`
- `detalle-produccion-costura.xlsx`
- `eficiencia.xlsx`
- `produccion-costura-cliente.xlsx`
- `produccion-costura-linea-cliente.xlsx`
- `segundas-prendas.xlsx`

Estos archivos se convirtieron a formato **CSV** y se almacenaron en la ruta `/data/raw/` dentro de **HDFS**, manteniendo carpetas por dataset y fecha de ingestión:

/data/raw/<nombre_archivo>/ingest_date=YYYYMMDD

### 🟨 2. Transformación (Transform)

Mediante **Spark (Scala)** se aplicaron reglas de limpieza y estandarización:

- Eliminación de registros duplicados por `ORDEN_PRODUCCION` y `SECUENCIA_PAQUETE`
- Normalización de mayúsculas en campos de texto (`ESTILO`, `TALLA`, `LINEA`)
- Conversión de fechas al formato ISO (`yyyy-MM-dd`)
- Cálculo del porcentaje de segundas: PORC_SEGUNDAS = FALLAS_SEGUNDAS / PRENDAS
- Validación de campos nulos y eliminación de filas incompletas

Los datos limpios se almacenaron temporalmente en la **zona staging** (`/data/staging/`).

---

### 🟦 3. Carga (Load)

Finalmente, los datos transformados se cargaron en tablas **Hive**, diferenciando dos zonas:

- **Raw layer:** tablas externas sobre los archivos CSV originales  
- **Curated layer:** tablas normalizadas en formato **ORC**, optimizadas para consulta y análisis

Las **particiones por año y mes (anio, mes)** se definieron para la tabla de hechos, mejorando el rendimiento en consultas analíticas.

El flujo ETL consolidó los reportes dispersos en una estructura uniforme, garantizando **trazabilidad y consistencia** en las métricas de producción y eficiencia.

---

## 📂 Fuentes de datos

| Archivo origen | Contenido principal | Campos clave |
|----------------|---------------------|---------------|
| `detalle-produccion-costura(1).xlsx` | Producción diaria por orden y paquete | ORDEN_PRODUCCION, SECUENCIA_PAQUETE, ESTILO, TALLA, PRENDAS, FECHA_TERMINO |
| `detalle-produccion-costura.xlsx` | Detalle complementario de producción | ORDEN_PRODUCCION, SECUENCIA_PAQUETE, ESTILO, TALLA, PRENDAS, FECHA_TERMINO |
| `eficiencia.xlsx` | Eficiencia por línea de costura y fecha | FECHA, LINEA, EFICIENCIA |
| `produccion-costura-cliente.xlsx` | Producción total por cliente | FECHA, TCODICLIE, PRENDAS |
| `produccion-costura-linea-cliente.xlsx` | Producción por cliente y línea | FECHA, LINEA, TCODICLIE, PRENDAS |
| `segundas-prendas.xlsx` | Registro de fallas y prendas observadas | FECHA, INSPECCION_TOTAL, FALLAS_SEGUNDAS, PORC_SEGUNDAS |

Cada archivo fue convertido a **CSV** y almacenado en la **zona raw de HDFS**, dentro de carpetas organizadas por fecha de ingestión (`ingest_date=YYYYMMDD`).

---

## 🧩 Zona Staging

Después de la carga inicial en `/data/raw`, se creó una zona de **staging** en `/data/staging/`, donde los archivos se procesaron mediante Spark para aplicar limpieza, validaciones y cálculos intermedios.

Reglas aplicadas:

- Eliminación de duplicados por `ORDEN_PRODUCCION` y `SECUENCIA_PAQUETE`
- Estandarización de formatos de texto (mayúsculas, eliminación de espacios)
- Conversión de fechas a formato ISO (`yyyy-MM-dd`)
- Validación de nulos y exclusión de filas incompletas
- Cálculo del porcentaje de segundas (`FALLAS_SEGUNDAS / INSPECCION_TOTAL`)
- Unión de datos complementarios (producción, eficiencia, clientes y fallas) en una estructura integrada

El resultado fue almacenado temporalmente en formato **Parquet**, para su posterior carga en las tablas finales del **Data Warehouse**.

---

## ⚙️ Reglas de negocio

1. **Integridad de producción:** una fila es válida solo si contiene `ORDEN_PRODUCCION`, `FECHA_TERMINO` y `PRENDAS > 0`.  
2. **Homogeneización de claves:** unificación de códigos de cliente (`TCODICLIE`) y líneas de costura bajo una nomenclatura única.  
3. **Cálculo de indicadores:**
 - `EFICIENCIA_PROMEDIO` por línea y fecha  
 - `% SEGUNDAS` por día  
 - Total de prendas por cliente y estilo  
4. **Trazabilidad:** se registró la fecha de ingestión (`ingest_date`) y el lote de carga.

---

## 💾 Carga final

En la fase final, los datos transformados se cargaron en Hive, distribuidos en dos esquemas:

- **dw_raw:** tablas externas apuntando a los CSV originales  
- **dw_curated:** tablas limpias y normalizadas en formato **ORC**, listas para análisis y construcción del **cubo OLAP**

Las tablas de la capa curated fueron **particionadas por año y mes (anio, mes)** para optimizar las consultas.

Antes de habilitar el acceso al dashboard, se ejecutaron consultas de verificación de conteos y validaciones de integridad.

---

## 12. Scripts de Extracción y Carga

El desarrollo de los scripts se realizó completamente dentro del entorno **Hortonworks Sandbox**, empleando **Hive** para la creación de tablas externas y **Spark (Scala)** para la limpieza, transformación y carga hacia la zona *Curated*.

---

### 12.1 Creación de bases de datos

```sql
CREATE DATABASE IF NOT EXISTS dw_raw;
CREATE DATABASE IF NOT EXISTS dw_curated;
```

---

### 12.2 Tablas RAW (HiveQL)

#### a) detalle_produccion_costura
```sql
USE dw_raw;

CREATE EXTERNAL TABLE IF NOT EXISTS detalle_produccion_costura (
  ORDEN_PRODUCCION STRING,
  SECUENCIA_PAQUETE STRING,
  ESTILO STRING,
  TALLA STRING,
  PRENDAS INT,
  FECHA_TERMINO STRING
)
ROW FORMAT SERDE 'org.apache.hadoop.hive.serde2.OpenCSVSerde'
WITH SERDEPROPERTIES ("separatorChar" = ",")
LOCATION '/data/raw/detalle_produccion_costura/';
```

#### b) eficiencia
```sql
CREATE EXTERNAL TABLE IF NOT EXISTS eficiencia (
  FECHA STRING,
  LINEA STRING,
  EFICIENCIA DOUBLE
)
ROW FORMAT SERDE 'org.apache.hadoop.hive.serde2.OpenCSVSerde'
WITH SERDEPROPERTIES ("separatorChar" = ",")
LOCATION '/data/raw/eficiencia/';
```

#### c) produccion_costura_cliente
```sql
CREATE EXTERNAL TABLE IF NOT EXISTS produccion_costura_cliente (
  FECHA STRING,
  TCODICLIE STRING,
  PRENDAS INT
)
ROW FORMAT SERDE 'org.apache.hadoop.hive.serde2.OpenCSVSerde'
LOCATION '/data/raw/produccion_costura_cliente/';
```

#### d) produccion_costura_linea_cliente
```sql
CREATE EXTERNAL TABLE IF NOT EXISTS produccion_costura_linea_cliente (
  FECHA STRING,
  LINEA STRING,
  TCODICLIE STRING,
  PRENDAS INT
)
ROW FORMAT SERDE 'org.apache.hadoop.hive.serde2.OpenCSVSerde'
LOCATION '/data/raw/produccion_costura_linea_cliente/';
```

#### e) segundas_prendas
```sql
CREATE EXTERNAL TABLE IF NOT EXISTS segundas_prendas (
  FECHA STRING,
  INSPECCION_TOTAL INT,
  FALLAS_SEGUNDAS INT,
  PORC_SEGUNDAS DOUBLE
)
ROW FORMAT SERDE 'org.apache.hadoop.hive.serde2.OpenCSVSerde'
LOCATION '/data/raw/segundas_prendas/';
```

---

### 12.3 Transformaciones (Spark - Scala)

```scala
import org.apache.spark.sql.SparkSession
import org.apache.spark.sql.functions._

val spark = SparkSession.builder()
  .appName("Transformacion Produccion Costura")
  .enableHiveSupport()
  .getOrCreate()

// Lectura de los datasets raw
val detalle = spark.read.option("header", "true").csv("/data/raw/detalle_produccion_costura/")
val eficiencia = spark.read.option("header", "true").csv("/data/raw/eficiencia/")
val cliente = spark.read.option("header", "true").csv("/data/raw/produccion_costura_cliente/")
val lineaCliente = spark.read.option("header", "true").csv("/data/raw/produccion_costura_linea_cliente/")
val segundas = spark.read.option("header", "true").csv("/data/raw/segundas_prendas/")

// Limpieza y normalización
val detalleClean = detalle
  .withColumn("ESTILO", upper(trim(col("ESTILO"))))
  .withColumn("TALLA", upper(trim(col("TALLA"))))
  .withColumn("FECHA_TERMINO", to_date(col("FECHA_TERMINO"), "yyyy-MM-dd"))
  .dropDuplicates("ORDEN_PRODUCCION", "SECUENCIA_PAQUETE")

val eficienciaClean = eficiencia
  .withColumn("FECHA", to_date(col("FECHA"), "yyyy-MM-dd"))
  .withColumn("LINEA", upper(trim(col("LINEA"))))

val segundasClean = segundas
  .withColumn("FECHA", to_date(col("FECHA"), "yyyy-MM-dd"))
  .withColumn("PORC_SEGUNDAS",
      when(col("INSPECCION_TOTAL") > 0, col("FALLAS_SEGUNDAS") / col("INSPECCION_TOTAL"))
      .otherwise(lit(null))
  )

// Almacenamiento temporal en staging
detalleClean.write.mode("overwrite").parquet("/data/staging/detalle_produccion_costura/")
eficienciaClean.write.mode("overwrite").parquet("/data/staging/eficiencia/")
segundasClean.write.mode("overwrite").parquet("/data/staging/segundas_prendas/")

spark.stop()
```

---

### 12.4 Creación de tablas Curated (HiveQL)

```sql
USE dw_curated;

-- Dimensión Tiempo
CREATE TABLE IF NOT EXISTS dim_tiempo (
  id_tiempo INT,
  fecha DATE,
  dia INT,
  mes INT,
  anio INT,
  trimestre INT
)
STORED AS ORC;

-- Dimensión Línea
CREATE TABLE IF NOT EXISTS dim_linea (
  id_linea INT,
  nombre_linea STRING
)
STORED AS ORC;

-- Dimensión Producto
CREATE TABLE IF NOT EXISTS dim_producto (
  id_producto INT,
  estilo STRING,
  talla STRING
)
STORED AS ORC;

-- Dimensión Cliente
CREATE TABLE IF NOT EXISTS dim_cliente (
  id_cliente INT,
  tcodiclie STRING
)
STORED AS ORC;

-- Tabla de Hechos
CREATE TABLE IF NOT EXISTS fact_produccion (
  orden_produccion STRING,
  secuencia_paquete STRING,
  id_producto INT,
  id_linea INT,
  id_cliente INT,
  prendas INT,
  eficiencia DOUBLE,
  fallas_segundas INT,
  porc_segundas DOUBLE,
  fecha_termino DATE
)
PARTITIONED BY (anio INT, mes INT)
STORED AS ORC;
```

---

### 12.5 Carga de datos a tablas Curated

```sql
INSERT OVERWRITE TABLE dw_curated.fact_produccion PARTITION (anio, mes)
SELECT
  d.ORDEN_PRODUCCION,
  d.SECUENCIA_PAQUETE,
  NULL AS id_producto,
  NULL AS id_linea,
  c.id_cliente,
  d.PRENDAS,
  e.EFICIENCIA,
  s.FALLAS_SEGUNDAS,
  s.PORC_SEGUNDAS,
  d.FECHA_TERMINO,
  year(d.FECHA_TERMINO) AS anio,
  month(d.FECHA_TERMINO) AS mes
FROM dw_raw.detalle_produccion_costura d
LEFT JOIN dw_raw.eficiencia e ON d.FECHA_TERMINO = e.FECHA
LEFT JOIN dw_raw.produccion_costura_cliente c ON d.FECHA_TERMINO = c.FECHA
LEFT JOIN dw_raw.segundas_prendas s ON d.FECHA_TERMINO = s.FECHA;
```

---

### 12.6 Validaciones y evidencias

```sql
DESCRIBE FORMATTED dw_curated.fact_produccion;
SHOW PARTITIONS dw_curated.fact_produccion;
SELECT COUNT(*) FROM dw_curated.fact_produccion;
SELECT SUM(prendas) FROM dw_curated.fact_produccion;
SELECT AVG(eficiencia) FROM dw_curated.fact_produccion;
```

## 13. Tablas en Hive

La estructura final implementada en **Hive** se resume en la siguiente tabla:

| Tabla | Tipo | Particiones | Formato |
|--------|------|--------------|----------|
| dw_raw.detalle_produccion_costura | Raw | ingest_date | CSV |
| dw_raw.eficiencia | Raw | ingest_date | CSV |
| dw_raw.produccion_costura_cliente | Raw | ingest_date | CSV |
| dw_raw.segundas_prendas | Raw | ingest_date | CSV |
| dw_curated.dim_tiempo | Curated | — | ORC |
| dw_curated.dim_linea | Curated | — | ORC |
| dw_curated.dim_producto | Curated | — | ORC |
| dw_curated.dim_cliente | Curated | — | ORC |
| dw_curated.fact_produccion | Curated | anio, mes | ORC |

### Evidencias

Se ejecutaron los siguientes comandos de validación:

```sql
DESCRIBE FORMATTED dw_curated.fact_produccion;
SHOW PARTITIONS dw_curated.fact_produccion;
SELECT COUNT(*) FROM dw_curated.fact_produccion;
SELECT SUM(prendas)
FROM dw_curated.fact_produccion
WHERE anio = 2025 AND mes = 10;
```

Los resultados confirmaron la correcta carga y estructura de las tablas en Hive.

---

## 14. Cubo OLAP

Con las tablas normalizadas se diseñó un **cubo OLAP** sobre la tabla de hechos `dw_curated.fact_produccion`, complementada por las dimensiones `dim_tiempo`, `dim_linea`, `dim_cliente` y `dim_producto`.

### Estructura del Cubo

- **Tabla de hechos:** `fact_produccion`
- **Dimensiones:** Tiempo, Línea, Cliente, Producto
- **Medidas:**
  - Total de prendas → `SUM(prendas)`
  - Eficiencia promedio → `AVG(eficiencia)`
  - Total de fallas segundas → `SUM(fallas_segundas)`
  - Porcentaje de segundas → `AVG(porc_segundas)`

### Ejemplo de consulta OLAP

```sql
SELECT 
    t.mes, 
    l.nombre_linea,
    SUM(f.prendas) AS total_prendas,
    AVG(f.eficiencia) AS eficiencia_prom,
    AVG(f.porc_segundas) AS porc_segundas_prom
FROM dw_curated.fact_produccion f
JOIN dw_curated.dim_tiempo t 
    ON f.anio = t.anio AND f.mes = t.mes
JOIN dw_curated.dim_linea l 
    ON f.id_linea = l.id_linea
GROUP BY t.mes, l.nombre_linea
ORDER BY t.mes;
```

Este cubo permitió visualizar el desempeño mensual por línea de producción, identificando tendencias y niveles de eficiencia.

---

## 15. Dashboard Preliminar

Para la visualización de los resultados se elaboró un **dashboard en Power BI**, conectado directamente al servidor **Hive** del **Hortonworks Sandbox**.

### Componentes del Dashboard

1. **Vista acumulativa de producción**
   - Línea temporal de producción total.
   - Filtros: Línea, Cliente, Estilo.

2. **Vista acumulativa de calidad**
   - Porcentaje acumulado de segundas por mes y línea.
   - Filtros: Línea, Estilo, Mes.

3. **Vista comparativa**
   - Gráfico de barras comparando la producción total y segundas entre el mes actual y el anterior.

4. **KPI destacado con semáforo**
   - Eficiencia promedio mensual:
     - 🟢 Verde: > 80%
     - 🟡 Amarillo: 70–80%
     - 🔴 Rojo: < 70%

---

## 16. Limitaciones y Propuesta de Mejora

### Limitaciones

- Las fuentes originales en Excel presentaban diferencias de formato y errores tipográficos que requirieron limpieza manual.  
- El entorno **Hortonworks Sandbox** se ejecutó en una máquina virtual local, limitando los recursos de procesamiento.  
- La conversión de archivos Excel a CSV se realizó de forma semi-manual.  
- No se contó con un orquestador de flujos (*Airflow* o *NiFi*) para automatizar completamente el ETL.  
- El cubo OLAP fue implementado a nivel lógico en Hive; no se integró aún un motor OLAP dedicado.

### Propuestas de Mejora

- Implementar **Apache NiFi** para automatizar la carga de archivos y controlar la ingestión desde el origen.  
- Migrar el entorno a un **clúster Hadoop distribuido**, aumentando la capacidad de procesamiento.  
- Incorporar un motor OLAP como **Apache Kylin** o **Druid** para generar cubos con consultas multidimensionales en tiempo real.  
- Crear un **catálogo maestro de productos y clientes** para mejorar la integridad referencial.  
- Programar **validaciones automáticas** entre tablas *raw* y *curated* para detectar discrepancias en las cargas diarias.

---
## Bibliografía  

- [Tableau – Visualización de datos](https://www.tableau.com/es-es/blog)  
- [Microsoft Power BI Docs](https://docs.microsoft.com/es-es/power-bi/)  
- [Datascope – BI en diversos sectores](https://datascope.io/es/blog/)  
- [IBM – Business Intelligence](https://www.ibm.com/blogs/systems/es-es/tag/business-intelligence/)  
- [Ceintec – Inteligencia de negocios y Big Data](http://www.ceintec.com/inteligencia-de-negocios-y-big-data)
