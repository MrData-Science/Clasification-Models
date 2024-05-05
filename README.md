# Clasification Models
## Detector de Fake News

Este repositorio contiene un proyecto de detección de noticias falsas utilizando varios modelos de clasificación. Se exploran los siguientes algoritmos:

- **Support Vector Machine (SVM)**: Un algoritmo que encuentra el hiperplano óptimo que mejor separa los datos en clases.
- **Árbol de Decisión**: Un método de aprendizaje supervisado utilizado para clasificación y regresión.
- **Random Forest**: Un ensamble de árboles de decisión que combina múltiples modelos para mejorar la precisión y evitar el sobreajuste.
- **Red Neuronal**: Un modelo inspirado en el cerebro humano que aprende a partir de datos para realizar tareas de clasificación.
- **AdaBoost**: Un algoritmo de ensamble que combina múltiples clasificadores débiles para crear un clasificador fuerte.
- **K-Nearest Neighbors (KNN)**: Un método de clasificación que asigna una etiqueta a un punto basándose en las etiquetas de los puntos vecinos más cercanos.

### Dataset

El conjunto de datos utilizado en este proyecto consta de noticias representadas por varias características numéricas.

- **ID**: Identificador único para cada artículo.
- **Word_Count**: Número total de palabras en el artículo.
- **Sentence_Length**: Longitud promedio de las oraciones en el artículo.
- **Unique_Words**: Número de palabras únicas en el artículo.
- **Average_Word_Length**: Longitud promedio de las palabras en el artículo.
- **Label**: Etiqueta binaria que indica si el artículo es real (1) o falso (0).

### Resultados

Los modelos entrenados fueron validados utilizando el `roc_auc_score`, que mide el área bajo la curva ROC (Receiver Operating Characteristic). Esta métrica evalúa la capacidad de discriminación del modelo, es decir, su capacidad para distinguir entre clases positivas y negativas.


