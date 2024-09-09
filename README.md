# Practical Application Assignment 11.1: What Drives the Price of a Car?

## Descripción

En esta práctica, se explora un dataset de autos usados con el objetivo de comprender los factores que influyen en el precio de un automóvil. Utilizando un subconjunto de 426,000 registros del dataset original, se aplica el marco CRISP-DM para identificar qué características afectan el precio y se proporcionan recomendaciones prácticas para que un concesionario de autos usados ajuste su inventario de manera efectiva.

## Estructura del Repositorio

- **`notebook.ipynb`**: Jupyter Notebook que contiene el análisis completo, incluyendo la preparación de datos, modelado, y evaluación.
- **`model_performance_report.csv`**: Archivo CSV con el rendimiento de los modelos.
- **`model_performance_visualization.png`**: Imagen con visualizaciones del rendimiento de los modelos.
- **`model_performance_summary.txt`**: Resumen en texto del rendimiento de los modelos y recomendaciones.
- **`requirements.txt`**: Lista de dependencias necesarias para ejecutar el análisis.

## Instrucciones de Ejecución

1. **Instalar Dependencias**: Asegúrate de tener las bibliotecas necesarias instaladas. Puedes instalar las dependencias listadas en `requirements.txt` con el siguiente comando:
    ```bash
    pip install -r requirements.txt
    ```

2. **Ejecutar el Notebook**: Abre el archivo `notebook.ipynb` en Jupyter Notebook y ejecuta las celdas para reproducir el análisis.

3. **Revisar Resultados**: Los resultados del análisis, incluyendo las visualizaciones y recomendaciones, están disponibles en los archivos generados.

## Resultados

El análisis proporciona:

- **Modelos de Predicción**: Comparación de modelos de regresión lineal, Random Forest y XGBoost.
- **Evaluación de Modelos**: Métricas como MAE, RMSE y R^2 para cada modelo.
- **Importancia de Características**: Identificación de las características más influyentes en el precio de los autos.
- **Recomendaciones**: Consejos prácticos para ajustar el inventario basado en los hallazgos.
