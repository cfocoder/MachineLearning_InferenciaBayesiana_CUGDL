# Tema 6: Regresión Logística

En esta sección del curso exploraremos uno de los algoritmos más fundamentales y útiles en machine learning para problemas de clasificación.

## ¿Qué aprenderás?

La regresión logística actúa como puerta de entrada al tema de clasificación supervisada. A diferencia de la regresión lineal que predice valores continuos, la regresión logística te permite predecir **probabilidades** y tomar decisiones binarias (sí/no, spam/no spam, compra/no compra).

### Conceptos clave que dominarás:

- **Función logística (sigmoide)**: Cómo transformar cualquier valor real en una probabilidad entre 0 y 1
- **Maximum Likelihood Estimation**: El método matemático detrás del entrenamiento del modelo
- **Interpretación de coeficientes**: Qué significan realmente los parámetros de tu modelo
- **Métricas de evaluación**: Más allá de la precisión - matriz de confusión, F1-score, AUC-ROC
- **Aplicación práctica**: Resolver un problema real de marketing bancario

## Contenido de la unidad

### 1. Presentación teórica
- **`06_regresion_logistica_slides.pdf`**: Fundamentos matemáticos y conceptuales
  - Derivación de la función logística
  - Interpretación probabilística
  - Comparación con regresión lineal
  - Ventajas y limitaciones

### 2. Implementación desde cero
- **`06_regresion_logistica_implementacion_manual.ipynb`**: Construye el algoritmo paso a paso
  - Implementación manual del método de máxima verosimilitud
  - Comprende la matemática detrás del algoritmo
  - Visualiza cómo converge el modelo durante el entrenamiento

### 3. Aplicación práctica
- **`06_regresion_logistica_implementacion_dataset.ipynb`**: Caso real con dataset bancario
  - Análisis exploratorio de datos
  - Preprocesamiento y codificación de variables categóricas
  - Entrenamiento con scikit-learn
  - Evaluación completa del modelo
  - Interpretación de resultados para toma de decisiones

## Caso de estudio: Predicción de éxito en campañas bancarias

Trabajarás con un dataset real de una institución financiera portuguesa que realizó campañas de telemarketing. Tu misión: **predecir si un cliente aceptará o no una oferta de depósito a plazo fijo**.

### ¿Por qué este caso es perfecto para aprender?
- **Relevancia práctica**: Problema real que enfrentan las empresas diariamente
- **Complejidad adecuada**: Variables categóricas, numéricas y desbalanceo de clases
- **Interpretabilidad**: Podrás explicar qué factores influyen en la decisión del cliente
- **Métricas diversas**: Aprenderás cuándo usar precisión, recall, F1-score o AUC


## Algunos consejos

### Antes de empezar:
- Repasa conceptos de probabilidad y estadística básica
- Asegúrate de entender la regresión lineal

### Durante el estudio:
- **No te saltes la implementación manual**: Es donde realmente entenderás el algoritmo
- **Experimenta con los parámetros**: Cambia valores y observa qué sucede
- **Interpreta siempre los resultados**: No solo busques la mejor métrica
- **Relaciona con casos reales**: Piensa en otros problemas donde aplicarías esto

### Para profundizar:
- Investiga sobre regresión logística multinomial
- Explora técnicas de regularización (L1 y L2)
- Estudia el impacto del desbalanceo de clases