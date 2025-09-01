# Naive Bayes - Machine Learning e Inferencia Bayesiana

Esta es la sección sobre el modelo **Naive Bayes**, uno de los algoritmos de clasificación más elegantes y fundamentales del machine learning, basado en el famoso teorema de Bayes.

## ¿Qué vas a aprender?

El clasificador Naive Bayes es perfecto para entender cómo las matemáticas se convierten en predicciones útiles. A lo largo de esta sección, vas a:

- **Comprender la teoría**: Desde el teorema de Bayes hasta la "ingenua" suposición de independencia
- **Implementar desde cero**: Crear tu propio clasificador para entender cada paso del proceso
- **Aplicar en casos reales**: Trabajar con datasets del mundo real como detección de spam y supervivencia del Titanic
- **Comparar variantes**: Explorar MultinomialNB, BernoulliNB y CategoricalNB de scikit-learn

## Contenido de la sección

### 📊 Materiales disponibles

- **`10_naive_bayes_slides.pdf`**: Presentación teórica con los fundamentos matemáticos
- **`10_naive_bayes_spam_ficticio.ipynb`**: Implementación manual paso a paso con datos sintéticos
- **`10_naive_bayes_titanic_comparacion_manual.ipynb`**: Comparación entre implementación manual y scikit-learn
- **`10_naive_bayes_spam_real.ipynb`**: Aplicación completa con dataset real de SMS spam

### 🎯 Casos de estudio

#### 1. Detección de SPAM (Datos ficticios)
Empezarás con un ejemplo sencillo donde implementarás el algoritmo desde cero. Vas a:
- Entender cómo calcular probabilidades condicionales
- Aplicar el teorema de Bayes manualmente
- Ver cómo se toman las decisiones de clasificación

#### 2. Supervivencia del Titanic
Un clásico del machine learning donde compararás:
- Tu implementación manual vs. scikit-learn
- Diferentes variantes del algoritmo (Multinomial, Bernoulli, Categorical)
- Métricas de evaluación y matrices de confusión

#### 3. Detección de SPAM (Datos reales)
El proyecto más completo donde trabajarás con:
- **5,572 mensajes SMS reales** etiquetados como spam/ham
- Preprocesamiento de texto (limpieza, stopwords, vectorización)
- Optimización de hiperparámetros
- Evaluación exhaustiva del modelo

## Conceptos clave

### Fundamentos teóricos
- **Teorema de Bayes**: P(A|B) = P(B|A) × P(A) / P(B)
- **Suposición de independencia**: Por qué es "naive" pero efectivo
- **Probabilidades a priori y posteriori**
- **Verosimilitud (likelihood)**

### Aspectos prácticos
- **Preprocesamiento de texto**: Tokenización, limpieza, vectorización
- **Manejo de stopwords**: Eliminación de palabras comunes
- **Suavizado (smoothing)**: Evitar probabilidades cero
- **Evaluación de modelos**: Accuracy, precision, recall, matriz de confusión

### Variantes del algoritmo
- **MultinomialNB**: Para datos de conteo (frecuencia de palabras)
- **BernoulliNB**: Para datos binarios (presencia/ausencia)
- **CategoricalNB**: Para variables categóricas
- **GaussianNB**: Para datos continuos (no cubierto en esta sección)

## Flujo de trabajo recomendado

1. **Comienza con la teoría**: Revisa las slides para entender los fundamentos
2. **Implementación básica**: Trabaja el notebook de spam ficticio
3. **Comparación práctica**: Explora el caso del Titanic
4. **Proyecto completo**: Finaliza con el dataset real de SMS

## Resultados esperados

Al completar esta sección, habrás:

**Implementado** tu propio clasificador Naive Bayes desde cero  
**Aplicado** el algoritmo a problemas reales de clasificación  
**Comparado** diferentes variantes y sus casos de uso  
**Evaluado** modelos usando métricas apropiadas  
**Procesado** texto para tareas de NLP básicas  

## Tips para el éxito

- **No te saltes la implementación manual**: Es donde realmente entiendes el algoritmo
- **Experimenta con los hiperparámetros**: Especialmente el parámetro alpha (smoothing)
- **Analiza las matrices de confusión**: Te dan insights valiosos sobre el rendimiento
- **Compara siempre**: Manual vs. scikit-learn, diferentes variantes entre sí