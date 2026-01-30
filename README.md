# Alura Store Latam - Análisis de Datos 📊

Este proyecto contiene un análisis detallado de ventas y desempeño de cuatro tiendas de **Alura Store Latam**. El análisis se realiza utilizando un notebook en **Google Colab** (`AluraStoreLatam.ipynb`) y procesa datos provenientes de archivos CSV alojados en GitHub.

## 📋 Descripción del Proyecto

El objetivo principal de este notebook es extraer insights valiosos sobre el comportamiento de las ventas, las preferencias de los clientes y el desempeño individual de cada tienda. A través de la manipulación de datos con **Pandas** y la visualización con **Matplotlib**, se responden preguntas clave sobre el negocio.

## �️ Estructura del Proyecto

*   `AluraStoreLatam.ipynb`: Notebook principal que contiene todo el código de análisis y visualizaciones.
*   `README.md`: Este archivo, con documentación general del proyecto.

## �🚀 Características del Análisis

El notebook cubre los siguientes aspectos:

1.  **Importación y Limpieza de Datos**:
    - Carga de datasets de 4 tiendas diferentes.
    - Unificación y exploración inicial de la estructura de datos.

2.  **Análisis de Facturación 💰**:
    - Cálculo del ingreso total por tienda.
    - Visualización comparativa de la facturación.

3.  **Ventas por Categoría 📦**:
    - Conteo de ventas por categoría de producto.
    - Identificación de la categoría líder en ventas por sucursal.

4.  **Calificación de Tiendas ⭐**:
    - Análisis de satisfacción del cliente (promedio de calificaciones).

5.  **Análisis de Productos 🏆**:
    - Identificación de los productos más vendidos.

## 📊 Ejemplos de Insights Obtenidos

Algunos de los hallazgos clave del análisis incluyen:

*   **Líder en Facturación**: La **Tienda 1** genera los mayores ingresos totales.
*   **Categoría Dominante**: La categoría **"Muebles"** es consistentemente la más vendida en todas las tiendas analizadas.
*   **Satisfacción del Cliente**: La **Tienda 3** posee la calificación promedio más alta (**4.05/5**), seguida muy de cerca por la Tienda 2 (4.04).
*   **Top Sellers**: Productos como **"Armario"** y **"TV LED UHD 4K"** destacan entre los más vendidos (Ej. 60 unidades c/u en Tienda 1).

## 🛠️ Tecnologías Utilizadas

*   **Python**: Lenguaje principal.
*   **Pandas**: Para la manipulación y análisis de estructuras de datos (DataFrames).
*   **Matplotlib**: Para la generación de gráficos y visualizaciones.

## 📂 Fuente de Datos

Los datos son obtenidos directamente desde el repositorio de GitHub de Alura Latam:
*   `tienda_1.csv`
*   `tienda_2.csv`
*   `tienda_3.csv`
*   `tienda_4.csv`

## 💻 Cómo Usar este Proyecto

1.  **Requisitos**: Asegúrate de tener instalado Python y las librerías necesarias:
    ```bash
    pip install pandas matplotlib
    ```
2.  **Ejecución**:
    - Abre el archivo `AluraStoreLatam.ipynb` en **Google Colab**.
    - Ejecuta las celdas en orden secuencial para reproducir el análisis y las visualizaciones.
