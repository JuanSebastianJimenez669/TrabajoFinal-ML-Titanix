# Trabajo final - Predicción de Supervivencia — Dataset Titanic
**Curso:** Machine Learning | Institución Universitaria Pascual Bravo

## Descripción
Aplicación del ciclo CRISP-DM completo para predecir la supervivencia
de pasajeros del Titanic usando clasificación binaria supervisada.

## Modelos utilizados
- Naive Bayes Gaussiano (modelo final — Recall: 0.784)
- Árbol de Decisión (max_depth=4)

## Estructura
- `TrabajoFinalML_Final.ipynb` — notebook completo con todo el análisis
- `modelo_titanic_nb.pkl` — modelo entrenado serializado
- `scaler_titanic.pkl` — scaler entrenado serializado

## Dataset
`seaborn.load_dataset('titanic')` — 891 registros, clasificación binaria.
