Proyecto ETL en Python: Food Delivery

Descripción

Proyecto de extracción, transformación y carga (ETL) de datos de restaurantes y menús de una plataforma de delivery.

Objetivo

Integrar, limpiar y analizar información de restaurantes y sus menús para identificar patrones de categorías y precios que apoyen el análisis comercial.

Tecnologías utilizadas

Python

Pandas y NumPy

Matplotlib

SQLite

Jupyter Notebook

Visual Studio Code

Fuentes de datos

restaurants.csv: información de restaurantes.

Diez archivos CSV con información de menús.

Proceso ETL

Extract: lectura de los archivos CSV.

Transform: limpieza de textos, revisión de valores faltantes y conversión de precios a formato numérico.

Integración: unión de los diez archivos de menús y relación con la tabla de restaurantes.

Load: almacenamiento de las tablas procesadas en SQLite.

Análisis: consultas SQL y visualizaciones de categorías y precios.

Resultados principales

63,469 restaurantes.

836,350 registros de menús.

100% de coincidencia de identificadores entre los menús y los restaurantes.

Precio promedio de los platos: US$ 9.90.

Mediana de precios: US$ 7.99.

Archivos principales

TPI_Python_ETL.ipynb: notebook con el desarrollo del proyecto.

Data/: archivos CSV originales.

food_delivery.db: base de datos SQLite generada durante el proceso.

Ejecución

Abrir TPI_Python_ETL.ipynb en Jupyter Notebook o Visual Studio Code y ejecutar las celdas en orden. La carpeta Data/ debe estar disponible en la ubicación esperada por el notebook.