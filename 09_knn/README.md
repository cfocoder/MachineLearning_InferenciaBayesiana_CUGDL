# K-Vecinos Cercanos (K-Nearest Neighbors)

Este módulo de **K-Vecinos Cercanos (KNN)** del curso de Machine Learning e Inferencia Bayesiana.

## ¿Qué encontrarás aquí?

Este módulo te llevará desde los conceptos básicos del algoritmo KNN hasta su implementación práctica con datos reales. A diferencia de otros temas del curso, aquí nos enfocamos completamente en la práctica a través de notebooks interactivos, ya que la naturaleza intuitiva del algoritmo se comprende mejor experimentando directamente con él.

## Contenido del módulo

### `09_knn_intro.ipynb` - Introducción al K-NN
En este notebook aprenderás:

- **Fundamentos teóricos**: Comprenderás cómo funciona el algoritmo KNN y por qué es considerado un método "perezoso" (lazy learning)
- **Matemáticas del algoritmo**: Explorarás las métricas de distancia y cómo se toman las decisiones de clasificación
- **Implementación desde cero**: Desarrollo de una versión propia del algoritmo para entender cada paso del proceso
- **Efectos del parámetro K**: Experimentarás con diferentes valores de K y observarás cómo afecta las fronteras de decisión
- **Visualizaciones interactivas**: Verás representaciones gráficas que te ayudarán a intuir el comportamiento del modelo

### `09_knn_comparacion.ipynb` - Implementación y Comparación con Datos Reales
Este notebook te permitirá:

- **Aplicación práctica**: Trabajarás con el dataset real de marketing bancario de Portugal
- **Preprocesamiento de datos**: Aprenderás la importancia de la estandarización en KNN
- **Implementación manual vs. scikit-learn**: Compararás tu implementación con la biblioteca estándar
- **Análisis de resultados**: Evaluarás el rendimiento del modelo y comprenderás sus limitaciones

## ¿Por qué estudiar K-NN?

El algoritmo de K-Vecinos Cercanos es especial por varias razones:

1. **Simplicidad conceptual**: Es uno de los algoritmos más fáciles de entender intuitivamente
2. **No paramétrico**: No hace suposiciones sobre la distribución de los datos
3. **Versatilidad**: Funciona tanto para clasificación como para regresión
4. **Baseline perfecto**: Excelente punto de partida para cualquier problema de clasificación
5. **Interpretabilidad**: Las decisiones son completamente transparentes y explicables


## Estructura recomendada de estudio

1. **Comienza con la introducción** (`09_knn_intro.ipynb`): Dedica tiempo a entender la intuición detrás del algoritmo
2. **Experimenta con los parámetros**: Modifica los valores de K y observa los cambios
3. **Implementa tu versión**: No te saltes la implementación manual, es clave para el entendimiento
4. **Aplica a datos reales** (`09_knn_comparacion.ipynb`): Conecta la teoría con la práctica
5. **Reflexiona sobre las limitaciones**: Piensa en qué situaciones KNN podría no ser la mejor opción

## Algunos consejos

- **Visualiza siempre que puedas**: KNN es un algoritmo muy visual, aprovecha las gráficas para desarrollar intuición
- **Experimenta con diferentes datasets**: Prueba el algoritmo con datos de diferentes dimensiones y tamaños
- **Presta atención al preprocesamiento**: La escala de las variables es crucial en KNN
- **Considera la eficiencia computacional**: Reflexiona sobre cuándo KNN es práctico y cuándo no

## Recursos adicionales

Si quieres profundizar más en el tema, considera explorar:

- Variantes del algoritmo (KNN ponderado por distancia)
- Estructuras de datos para acelerar la búsqueda (KD-trees, Ball trees)
- Métricas de distancia alternativas (Manhattan, Minkowski, etc.)
- Aplicaciones de KNN en sistemas de recomendación