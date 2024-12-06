# Tarea 5 - Análisis de Datos: Predicción de Supervivencia en el Titanic

## Descripción
En esta tarea se ha realizado un análisis de datos utilizando el dataset de los pasajeros del Titanic para predecir quiénes sobrevivieron al naufragio. Se ha implementado un modelo de aprendizaje automático de regresión logística, siguiendo una serie de pasos clave de preprocesamiento, entrenamiento y evaluación del modelo.

## Pasos realizados:

1. **Análisis Exploratorio de Datos (EDA)**: 
   - Se exploraron las variables del dataset, se identificaron relaciones entre variables, tendencias y valores atípicos.

2. **Preprocesamiento de Datos**: 
   - Se limpiaron los datos, manejando valores nulos y transformando las variables categóricas utilizando `LabelEncoder`.
   - Las características se estandarizaron mediante `StandardScaler` para asegurar que el modelo funcione correctamente.

3. **Selección de Características**: 
   - Se seleccionaron las columnas relevantes para el modelo, excluyendo la variable objetivo `Survived`.

4. **División de Datos**: 
   - El conjunto de datos se dividió en un 80% para entrenamiento y un 20% para prueba.

5. **Entrenamiento del Modelo**: 
   - Se entrenó un modelo de regresión logística utilizando los datos de entrenamiento.

6. **Evaluación del Modelo**: 
   - Se evaluó el desempeño del modelo utilizando métricas como precisión, recall y F1-score.

## Requisitos

- Python 3.x
- Bibliotecas necesarias:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Instrucciones para ejecutar

1. Clona este repositorio o descarga el archivo con el dataset.
2. Instala las bibliotecas necesarias utilizando pip:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
