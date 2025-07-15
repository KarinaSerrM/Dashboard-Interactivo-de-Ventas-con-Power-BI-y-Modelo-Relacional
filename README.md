# Dashboard Interactivo de Ventas con Power BI y Modelo Relacional

Este repositorio documenta un proyecto desarrollado en Power BI que permite explorar datos de ventas a través de un modelo relacional bien estructurado. Se integran múltiples tablas y se aplican transformaciones en Power Query para construir un dashboard interactivo que facilita el análisis por país, tienda, producto y tendencia temporal.

## Objetivo

Construir un sistema visual para el análisis de ventas que permita entender el comportamiento comercial a través de filtros interactivos, gráficos dinámicos y visualizaciones geográficas.

## Flujo de trabajo

### 1. Conexión de datos
- Integración de archivos fuente mediante Power BI Desktop
- Importación de las tablas:  
  - `t_customer_KS`  
  - `t_product_KS`  
  - `t_store_KS`  
  - `t_countries_KS`  
  - `Sales_KS`

### 2. Limpieza y transformación (Power Query)
- Eliminación de registros innecesarios
- Cambios de tipos de datos para compatibilidad
- Renombrado de columnas para claridad
- Validación de integridad entre tablas relacionadas

### 3. Modelado relacional
- Definición de claves primarias y foráneas
- Creación de relaciones entre dimensiones y tabla de hechos (`Sales_KS`)
- Diseño lógico del modelo estrella con entidades conectadas

### 4. Diseño de visualizaciones
- Gráficos:
  - Mapa interactivo por país
  - Tendencia temporal de ventas
  - Composición por categoría de producto
  - Gráfico circular por tienda
- Segmentaciones interactivas por producto, país y categoría

## Herramientas utilizadas

- Power BI Desktop  
- Power Query  
- DAX básico  
- Archivos CSV / Excel como fuente

## Conclusiones

- El modelo de datos relacional permite una navegación fluida entre entidades.
- La limpieza de datos en Power Query garantiza la precisión del análisis.
- Las visualizaciones permiten comprender la distribución de ventas, patrones temporales y comportamiento por categoría.
- El uso de filtros y segmentaciones mejora la experiencia del usuario final.

