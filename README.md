# Alura Store Latam - Análisis de Datos 📊

Este proyecto contiene un análisis detallado de ventas y desempeño de cuatro tiendas de **Alura Store Latam**. El análisis se realiza utilizando un notebook de Jupyter (`.ipynb`) y procesa datos provenientes de archivos CSV alojados en GitHub.

## 📋 Descripción del Proyecto

El objetivo principal de este notebook es extraer insights valiosos sobre el comportamiento de las ventas, las preferencias de los clientes y el desempeño individual de cada tienda. A través de la manipulación de datos con **Pandas** y la visualización con **Matplotlib**, se responden preguntas clave sobre el negocio.

## 🚀Características del Análisis

El notebook `AluraStoreLatam.ipynb` cubre los siguientes aspectos:

1.  **Importación y Limpieza de Datos**:
    - Carga de datasets de 4 tiendas diferentes.
    - Unificación y exploración inicial de la estructura de datos (columnas como Producto, Categoría, Precio, Vendedor, Ubicación, etc.).

2.  **Análisis de Facturación 💰**:
    - Cálculo del ingreso total por tienda.
    - Visualización comparativa de la facturación mediante gráficos de barras.

3.  **Ventas por Categoría 📦**:
    - Conteo de ventas por categoría de producto (Muebles, Electrónicos, Juguetes, etc.) para cada tienda.
    - Identificación de la categoría líder en ventas por sucursal.

4.  **Calificación de Tiendas ⭐**:
    - Cálculo del promedio de satisfacción del cliente (Calificación de 1 a 5) por tienda.
    - Gráficos de dispersión para visualizar el desempeño en calificaciones.

5.  **Análisis de Productos 🏆**:
    - Identificación de los productos más vendidos.
    - (Opcional) Análisis de los productos con menor desempeño.

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
    - Abre el archivo `AluraStoreLatam.ipynb` en Jupyter Notebook, JupyterLab o Google Colab.
    - Ejecuta las celdas en orden secuencial para reproducir el análisis y las visualizaciones.

---
