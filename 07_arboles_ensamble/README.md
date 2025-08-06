# Tema 7: Árboles de Decisión y Métodos de Ensamble

En esta sección exploraremos uno de los algoritmos más intuitivos y versátiles del aprendizaje automático: los **árboles de decisión** y sus extensiones mediante **métodos de ensamble**.

## ¿Qué encontrarás aquí?

Este módulo te llevará desde los conceptos fundamentales de los árboles de decisión hasta técnicas avanzadas de ensamblado que mejoran significativamente el rendimiento predictivo. El contenido está diseñado para que puedas tanto entender la teoría como implementar estos algoritmos en problemas reales.

### Contenido del módulo

#### 📚 Material teórico
- **`07_arboles_ensamble_slides.pdf`**: Presentación completa con la teoría fundamental, conceptos clave y ejemplos visuales

#### 💻 Notebooks prácticos

1. **`07_arboles_decision_implementacion.ipynb`**: Implementación detallada para clasificación
   - Construcción paso a paso de árboles de decisión
   - Evaluación y métricas de desempeño
   - Interpretación de resultados

2. **`07_arboles_regresion_implementacion.ipynb`**: Árboles para problemas de regresión
   - Adaptación de árboles para variables continuas
   - Implementación con el dataset Diabetes
   - Comparación de modelos individuales vs. ensambles
   - Random Forest y Gradient Boosting para regresión

## Conceptos clave que dominarás

### Árboles de Decisión
Los árboles de decisión son modelos que toman decisiones mediante una serie de preguntas binarias sobre las características de los datos. Son especialmente valiosos porque:

- **Interpretabilidad**: Cada predicción puede explicarse como una secuencia de reglas lógicas
- **Versatilidad**: Funcionan tanto para clasificación como regresión
- **No requieren preprocesamiento**: Manejan naturalmente variables categóricas y numéricas
- **Capturan relaciones no lineales**: Sin necesidad de transformaciones complejas

### Medidas de Impureza
Aprenderás a utilizar las dos métricas principales para construir árboles:

- **Índice de Gini**: Mide la probabilidad de clasificación incorrecta
- **Entropía**: Cuantifica la incertidumbre o desorden en los datos

### Métodos de Ensamble
Los ensambles combinan múltiples modelos para obtener predicciones más robustas:

#### Random Forest
- Combina múltiples árboles entrenados en paralelo
- Utiliza bootstrap sampling y selección aleatoria de características
- Reduce la varianza y mejora la generalización
- Proporciona estimaciones de importancia de características

#### Gradient Boosting
- Entrena árboles de forma secuencial
- Cada nuevo árbol corrige los errores del anterior
- Mayor precisión pero más sensible al sobreajuste
- Requiere ajuste cuidadoso de hiperparámetros

## Datasets utilizados

### Iris Dataset (Clasificación)
- **Objetivo**: Clasificar especies de flores iris
- **Características**: Medidas de pétalos y sépalos
- **Ideal para**: Entender conceptos básicos y visualización

### Diabetes Dataset (Regresión)
- **Objetivo**: Predecir progresión de la enfermedad
- **Características**: Indicadores médicos normalizados (edad, IMC, presión arterial, etc.)
- **Ideal para**: Comparar modelos de regresión y técnicas de ensamble

## Estructura del material

1. Comienza con las slides para entender la teoría
2. Practica con la implementación de clasificación
3. Avanza hacia los métodos de ensamble


## Algunos consejos

1. **Visualiza siempre que puedas**: Los árboles son naturalmente interpretables
2. **Experimenta con la profundidad**: Encuentra el equilibrio entre sesgo y varianza
3. **Compara múltiples modelos**: Un solo árbol vs. ensambles
4. **Presta atención a las características importantes**: Te dan insights valiosos sobre tus datos
5. **Practica la validación cruzada**: Es esencial para evaluar correctamente estos modelos
