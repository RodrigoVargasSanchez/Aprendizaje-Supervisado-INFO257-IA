# Aprendizaje-Supervisado-INFO257-IA

# Proyecto de Modelos de Predicción: Puntos de Jugadores de la NBA y Diagnóstico de Cáncer

Este repositorio contiene dos proyectos principales: un modelo de regresión lineal para predecir los puntos de los jugadores de la NBA en un partido y un conjunto de modelos de clasificación binaria para predecir si una persona tendrá o no cáncer.

## Modelo de Regresión Lineal: Predicción de Puntos en la NBA

### Descripción
En este proyecto, desarrollamos un modelo de regresión lineal para predecir los puntos anotados por los jugadores de la NBA en un partido utilizando diversas estadísticas de los jugadores. Utilizamos un conjunto de datos que incluye estadísticas de los jugadores durante la temporada 2022-2023.

### Dataset
El dataset contiene las siguientes columnas:
- `Player Name`: Nombre del jugador.
- `Salary`: Salario del jugador.
- `Position`: Posición en la que juega el jugador.
- `Age`: Edad del jugador.
- `Team`: Equipo en el que juega el jugador.
- Estadísticas de juego y tiro (`GP`, `GS`, `MP`, `FG`, `FGA`, `3P`, `3PA`, `2P`, `2PA`, `FT`, `FTA`, etc.)
- Estadísticas avanzadas (`PER`, `TS%`, `USG%`, `OWS`, `DWS`, `WS`, `WS/48`, `OBPM`, `DBPM`, `BPM`, `VORP`)

### Métricas de Evaluación
Evaluamos nuestro modelo utilizando las siguientes métricas:
- **MSE**: Mean Squared Error
- **RMSE**: Root Mean Squared Error
- **MAE**: Mean Absolute Error
- **R²**: Coeficiente de Determinación

### Resultados
Probamos tres modelos distintos:
1. **Modelo Básico**: Utiliza un subconjunto reducido de características.
2. **Modelo Avanzado**: Utiliza un conjunto más amplio de características.
3. **Modelo Completo**: Utiliza todas las características disponibles.

Los resultados muestran que el **Modelo Completo** ofrece el mejor rendimiento en términos de MSE, RMSE, MAE y R².

## Clasificación Binaria: Predicción de Diagnóstico de Cáncer

### Descripción
En este proyecto, abordamos el problema de clasificación binaria para predecir si una persona tiene o no cáncer. Utilizamos varios algoritmos de clasificación para este propósito:

1. **Regresión Logística**
2. **Máquina de Soporte Vectorial (SVM)**
3. **Árbol de Decisión**
4. **Ensemble: Bagging**

### Dataset
El dataset utilizado contiene diversas características clínicas y demográficas de los pacientes, junto con una etiqueta binaria indicando la presencia o ausencia de cáncer.

### Algoritmos de Clasificación
- **Regresión Logística**: Modelo lineal para clasificación.
- **Máquina de Soporte Vectorial (SVM)**: Modelo que encuentra el hiperplano que mejor separa las clases.
- **Árbol de Decisión**: Modelo que utiliza un árbol de decisiones para realizar la clasificación.
- **Ensemble: Bagging**: Técnica que combina múltiples modelos de árboles de decisión para mejorar la precisión.

### Métricas de Evaluación
Evaluamos los modelos utilizando las siguientes métricas:
- **Accuracy**: Precisión del modelo.
- **Precision**: Precisión de las predicciones positivas.
- **Recall**: Cobertura de las predicciones positivas.
- **F1 Score**: Media armónica de precisión y recall.

