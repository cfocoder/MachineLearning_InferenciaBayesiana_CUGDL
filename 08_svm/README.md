# Support Vector Machines (SVM)

Esta a la sección de **Support Vector Machines** del curso de Machine Learning e Inferencia Bayesiana.

## ¿Qué son las Support Vector Machines?

Las Support Vector Machines son algoritmos de aprendizaje supervisado que pueden utilizarse tanto para clasificación como para regresión. Su principal fortaleza radica en encontrar el hiperplano óptimo que mejor separa las clases en el espacio de características, maximizando el margen entre ellas.

### Conceptos clave que aprenderás:

- **Hiperplano de separación**: La frontera de decisión que divide las clases
- **Vectores de soporte**: Los puntos de datos más críticos que definen la frontera
- **Margen**: La distancia entre el hiperplano y los puntos más cercanos de cada clase
- **Truco del kernel**: Técnica para trabajar en espacios de alta dimensionalidad
- **Parámetros de regularización**: Control del balance entre sesgo y varianza

## Contenido de la sección

###  Material teórico
- **`08_svm_slides.pdf`**: Presentación completa con los fundamentos teóricos, matemáticas detrás del algoritmo y ejemplos visuales

###  Notebooks prácticos

1. **`08_svm_intro.ipynb`** - Introducción a SVM
   - Conceptos fundamentales
   - Visualización del hiperplano de separación
   - Comprensión intuitiva del algoritmo
   - Ejemplos básicos en 2D
   - Análisis con diferentes kernels

2. **`08_svm_implementacion_clasificacion_comparacion.ipynb`** - Clasificación con SVM
   - Implementación práctica para problemas de clasificación
   - Comparación con otros algoritmos de clasificación
   - Evaluación de rendimiento

3. **`08_svm_implementacion_regresion.ipynb`** - Regresión con SVM
   - Support Vector Regression (SVR)
   - Aplicación a problemas de regresión
   
## Objetivos de aprendizaje

Al completar esta sección, serás capaz de:

- Entender la intuición matemática detrás de las SVM
- Implementar SVM para problemas de clasificación y regresión
- Seleccionar y configurar diferentes tipos de kernels
- Optimizar hiperparámetros para mejorar el rendimiento
- Comparar SVM con otros algoritmos de machine learning
- Interpretar los resultados y vectores de soporte


## Cómo usar este material

1. **Comienza con las slides** (`08_svm_slides.pdf`) para obtener una base teórica sólida
2. **Ejecuta el notebook de introducción** para ver los conceptos en acción
3. **Practica con los notebooks de implementación** siguiendo los ejemplos paso a paso
4. **Experimenta** modificando parámetros y probando con tus propios datos


## Consejos para el estudio

- Las SVM pueden ser matemáticamente intensivas, pero no te desanimes. Enfócate primero en la intuición
- Practica visualizando los resultados en 2D antes de trabajar con datos de alta dimensionalidad
- Experimenta con diferentes kernels (linear, polynomial, RBF, sigmoid) para entender sus efectos
- Presta atención a la importancia del escalado de características en SVM
- Los vectores de soporte son clave: siempre examina cuáles son y por qué fueron seleccionados
