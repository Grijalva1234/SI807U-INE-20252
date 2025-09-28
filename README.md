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

<img width="886" height="373" alt="image" src="https://github.com/user-attachments/assets/36b747b4-dac7-4262-b7a3-c87f0ead594e" />


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
*(Aquí puedes colocar las capturas o evidencia de los archivos cargados en HDFS)*  
![Archivos en HDFS](ruta/a/imagen_hdfs.png)

---

### 10.2. Scripts CREATE EXTERNAL TABLE en Hive
A continuación, un ejemplo del script utilizado para crear tablas externas en Hive:

```sql
CREATE EXTERNAL TABLE IF NOT EXISTS nombre_tabla (
    id INT,
    campo1 STRING,
    campo2 STRING,
    campo3 DOUBLE
)
ROW FORMAT DELIMITED
FIELDS TERMINATED BY ','
STORED AS TEXTFILE
LOCATION '/user/hive/warehouse/nombre_tabla';
```

---

### 10.3. Resultados de consulta simple



---

## Bibliografía  

- [Tableau – Visualización de datos](https://www.tableau.com/es-es/blog)  
- [Microsoft Power BI Docs](https://docs.microsoft.com/es-es/power-bi/)  
- [Datascope – BI en diversos sectores](https://datascope.io/es/blog/)  
- [IBM – Business Intelligence](https://www.ibm.com/blogs/systems/es-es/tag/business-intelligence/)  
- [Ceintec – Inteligencia de negocios y Big Data](http://www.ceintec.com/inteligencia-de-negocios-y-big-data)
