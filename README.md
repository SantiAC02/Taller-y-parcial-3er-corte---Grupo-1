Este repositorio contiene los 2 entregables principales correspondiente al .ipynb donde se realizó la limpieza de la base de datos y el .pbix que contiene el dashboard gerencial.

Descripción de nuestro proyecto:

📊 Proyecto de Análisis y Visualización de Ventas
📌 Descripción General del Proyecto

Este proyecto integra lo aprendido en Python para limpiar, transformar y preparar una base de datos comerciales reales, y Power BI para modelarla y construir un dashboard gerencial orientado al análisis estratégico de ventas, rentabilidad y comportamiento geográfico.

La base de datos contiene información detallada de productos, clientes, vendedores, fechas, cantidades, valores de venta y márgenes. A través de un proceso modelación de datos se generó un dashboar interactivo y analítico confiable para la toma de decisiones.

📂 Origen y Naturaleza de los Datos

La base de datos proviene de un archivo Excel, brindado por un ex-ingeniero de sistemas que ha colaborado con la empresa Onix Colombia SAS, de donde provienen los datos, esta incluye campos como:

ID y nombre del producto

Cliente

Vendedor

Fecha de venta

Ciudad

Unidades

Ventas en pesos colombianos

Costos y margen en pesos colombianos

Problemas detectados:

Fechas con maños incorrectos

Valores duplicados

Nombres inconsistentes

Nulos en columnas críticas

Tipos numéricos incorrectos

Erorres de digitación en el estado de la venta

🧽 Limpieza de Datos con Python

El Jupyter Notebook Limpieza_de_datos.ipynb implementa un proceso completo de depuración:

Carga y exploración inicial

Normalización de nombres de columnas

Rellenado de valores nulos con formulas

Conversión y corrección de tipos

Eliminación de duplicados

Limpieza de caracteres en campos

Exportación de dataset "Base de datos ONIX Limpia.xlsx" listo para Power BI

🧩 Modelado en Power BI

El modelo se construyó siguiendo buenas prácticas:

Esquema en estrella

Tabla de hechos: Ventas

Dimensiones: Calendario, Productos, Vendedores, Clientes, Ciudades

Medidas DAX principales utilizadas en los KPIs:

Total Ventas

Unidades Vendidas

Ticket Promedio

Margen %

Participación en Ventas %

Pareto acumulado

📊 Dashboard e Insights

Concentración extrema en pocos clientes
Dos clientes representan más del 40% de las ventas, evidenciando una dependencia comercial relevante.

La línea de televisores es el motor del negocio
Con ventas de $110M, supera al siguiente producto por más del 130%.

Rentabilidad dominada por insumos y consumibles
Productos como Chip SP 3710 (48%) y Toner HP 28B (45%) tienen los márgenes más altos.

Ticket promedio alto: $1,95M
Indica un posicionamiento premium y una base de clientes empresariales.

Bogotá domina el desempeño geográfico
Es la ciudad con mayor participación en ventas y explica los picos del mes de agosto.

Oportunidad estratégica
Combinar productos de alto volumen con los de mayor margen aumentaría significativamente la utilidad global.

🛠️ Herramientas Utilizadas

Visual Studio Code

Python (pandas, numpy, unicodedata, datetime)

Jupyter Notebook

Power BI

DAX

GitHub

🚀 Cómo Ejecutar

Clonar este repositorio

Abrir el notebook de limpieza (.ipynb)

Ejecutar la limpieza con el archvo "Base de datos ONIX Original".xlsx y exportar el dataset "Base de datos ONIX Limpia.xlsx" ya procesado

Abrir el archivo .pbix en Power BI Desktop o acceder al link: https://app.powerbi.com/links/zNd15RiXKG?ctid=aca51631-00fe-490d-91ab-163ef87260ee&pbi_source=linkShare

👥 Integrandtes del grupo

Santiago Acosta Calvo

Guillaume Garey

David Santiago Aragón Mendez
