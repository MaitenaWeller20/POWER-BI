# POWER-BI - Dashboard ficticio de Ventas E-commerce - PyME Argentina 📈
<img width="480" height="272" alt="1" src="https://github.com/user-attachments/assets/1d71b050-0958-48ce-bd30-da570f29ecc7" />
<img width="563" height="302" alt="2" src="https://github.com/user-attachments/assets/91109c39-8709-44d8-8bfa-382b2d373970" />
<img width="559" height="302" alt="3" src="https://github.com/user-attachments/assets/a8b27088-a42b-4d1c-97cd-d4f7ebddb61a" />

**Descripción del Proyecto**
Este repositorio contiene un tablero de control interactivo desarrollado en Power BI para analizar el rendimiento comercial de una PyME de E-commerce en Argentina. El análisis abarca un histórico de datos ficticios (2024-2026) diseñado para simular escenarios reales de ventas, estacionalidad y jerarquías de productos.

El objetivo principal es transformar datos transaccionales crudos en insights estratégicos que faciliten la toma de decisiones sobre inventario, logística y performance de ventas.

**📊 Visualizaciones Principales**
El tablero se enfoca en resolver las siguientes preguntas de negocio:
- Evolución Mensual: Comparativa de facturación y unidades a través del tiempo (2024, 2025, 2026).
- Análisis de Jerarquías: Distribución de ventas mediante la estructura Cluster > Familia > Subfamilia.
- Distribución Geográfica: Ventas segmentadas por provincias argentinas.
- Comparativa por Local: Análisis de stock y ventas entre los dos nodos logísticos disponibles (Local 1 y Local 2).

**🛠️ Tecnologías y Herramientas**
- Power BI: Para el modelado de datos y visualización.
- DAX (Data Analysis Expressions): Creación de medidas dinámicas para métricas de facturación, unidades y variaciones temporales.
- Power Query: Limpieza, transformación de datos y normalización (eliminación de tildes y caracteres especiales para asegurar compatibilidad).
- Dataset: Archivo CSV con 100 registros optimizados para análisis de tendencias.

**📋 Métricas Implementadas**
Se desarrollaron medidas específicas para el análisis dinámico:
- Facturación Total: Cálculo basado en Cantidad * Precio Unitario.
- Total Unidades: Sumatoria de volumen de ventas.

**🚀 Cómo utilizar este repositorio**
- Descargá el archivo .pbix y el dataset .csv.
- Abrí el archivo en Power BI Desktop.
- Si el origen de datos se rompe, redirigí la conexión al archivo .csv local en tu computadora.
