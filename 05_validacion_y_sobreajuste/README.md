# Tema 5: Validación y Control de Sobreajuste

## ¿De qué va esta unidad?

En esta unidad vas a aprender técnicas esenciales para evaluar tus modelos de manera correcta y evitar uno de los problemas más comunes en machine learning: el sobreajuste.

Aquí cubriremos tres temas clave: cómo dividir tus datos correctamente, qué es la validación cruzada y cómo usar técnicas de regularización para que tus modelos generalicen mejor.

## Lo que vas a aprender

Al terminar esta unidad, podrás:

- Entender qué es el sobreajuste y por qué es un problema serio
- Dividir correctamente tus datos en conjuntos de entrenamiento y prueba
- Implementar validación cruzada para evaluar tus modelos de forma más confiable
- Usar técnicas de regularización como Ridge y Lasso para controlar el sobreajuste
- Comparar diferentes enfoques y decidir cuál funciona mejor para tu problema

## Contenido de la Unidad

### 📚 Materiales Disponibles

1. **Presentación Teórica**
   - `05_validacion_y_sobreajuste_slides.pdf` - Slides con fundamentos teóricos

2. **Notebooks Prácticos**
   - `05_validación_y_sobreajuste_validacion_cruzada.ipynb` - División de datos y validación cruzada
   - `05_validacion_y_sobreajuste_ridge_lasso.ipynb` - Técnicas de regularización

### 🎯 Temas Principales

#### 1. División de Datos y Validación Cruzada
- **El problema del sobreajuste**: Por qué evaluar solo en datos de entrenamiento te puede engañar
- **División train-test**: Cómo reservar datos para una buena evaluación
- **Validación cruzada**: Una técnica más robusta para saber qué tan bueno es tu modelo
- **Dataset de práctica**: Trabajaremos con California Housing (viene incluido en scikit-learn)

#### 2. Regularización: Ridge y Lasso
- **Funciones de costo**: Qué son y por qué importan
- **Regresión Ridge (L2)**: Una forma de "castigar" coeficientes muy grandes
- **Regresión Lasso (L1)**: Otra técnica que además puede eliminar variables irrelevantes
- **Comparación práctica**: Veremos cuándo usar cada una

## Conceptos Clave

### Sobreajuste (Overfitting)
Es cuando tu modelo se vuelve demasiado "específico" con los datos de entrenamiento. Imagínate que memorizas las respuestas de un examen de práctica en lugar de entender los conceptos - vas a fallar cuando te enfrentes a preguntas nuevas. Lo mismo pasa con los modelos: aprenden el ruido y las particularidades específicas de los datos, pero no generalizan bien a datos nuevos.

### Validación Cruzada
Es una técnica inteligente para evaluar tu modelo de forma más confiable. En lugar de dividir tus datos una sola vez, los divides en múltiples partes y entrenas/evalúas varias veces. Esto te da una mejor idea de qué tan bueno es realmente tu modelo.

### Regularización
Agregan una "penalización" a la función de costo cuando los coeficientes se vuelven muy grandes, forzando al modelo a ser más simple y generalizar mejor.


## Cómo está organizado todo

1. **Primero la teoría** (Slides)
   - Los conceptos importantes que necesitas saber
   - Las matemáticas detrás de Ridge y Lasso (no te preocupes, las explicamos bien)

2. **Después la práctica** (Notebooks)
   - Código paso a paso que puedes seguir
   - Ejercicios para que practiques
   - Comparaciones para que veas qué funciona mejor

3. **Finalmente el análisis**
   - Cómo interpretar los resultados
   - Qué técnica usar en cada situación
   - Tips para aplicar en tus propios proyectos