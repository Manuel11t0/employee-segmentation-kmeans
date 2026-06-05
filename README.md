# Employee Segmentation K-Means

Este proyecto realiza una segmentación de empleados usando técnicas de Machine Learning no supervisado, principalmente el algoritmo **K-Means**.

El objetivo es identificar grupos de empleados con características similares para entender mejor distintos perfiles dentro de la organización.

## Descripción del proyecto

En este proyecto se trabaja con un dataset de empleados.  
Se limpian y transforman los datos para poder aplicar clustering y encontrar segmentos con características parecidas.

El análisis incluye variables numéricas y categóricas, por lo que se aplican técnicas de preprocesamiento como imputación de valores faltantes, estandarización y codificación One-Hot.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Objetivos

- Cargar y explorar el dataset de empleados.
- Eliminar columnas de identificación que no aportan al modelo.
- Detectar variables numéricas y categóricas.
- Aplicar imputación para valores faltantes.
- Estandarizar variables numéricas.
- Codificar variables categóricas con OneHotEncoder.
- Probar diferentes valores de K.
- Usar el método Elbow y Silhouette Score.
- Entrenar un modelo final de K-Means.
- Analizar los perfiles encontrados por cluster.
- Exportar el dataset con la segmentación final.

## Flujo del proyecto

1. Importación de librerías.
2. Carga manual del archivo CSV.
3. Exploración inicial del dataset.
4. Eliminación de columnas tipo ID.
5. Separación de variables numéricas y categóricas.
6. Preprocesamiento con pipelines.
7. Aplicación del método Elbow.
8. Cálculo del Silhouette Score.
9. Selección del número óptimo de clusters.
10. Entrenamiento del modelo final con K-Means.
11. Creación de la columna `Cluster`.
12. Análisis resumen por grupo.
13. Visualización de la distribución de empleados.
14. Visualización de variables numéricas por cluster.
15. Exportación del archivo final.

## Modelo utilizado

El algoritmo principal utilizado fue:

```text
K-Means Clustering
