# Tema 1: Introducción a Machine Learning

Este directorio contiene el material del primer tema del curso **Machine Learning e Inferencia Bayesiana**, enfocado en proporcionar una introducción práctica a los conceptos fundamentales del aprendizaje automático utilizando Python y Scikit-learn.

## 📋 Contenido del Tema

### Archivos Principales
- **`01_ML_intro.ipynb`** - Notebook principal con ejemplos prácticos y teoría
- **`01_ML_intro_slides.pdf`** - Presentación del tema en formato PDF

## 🎯 Objetivos de Aprendizaje

Al completar este tema, serás capaz de:

- Entender los conceptos fundamentales del Machine Learning
- Conocer la representación de datos en Scikit-learn (matriz de características y vector objetivo)
- Aplicar la API de estimadores de Scikit-learn de manera consistente
- Distinguir entre problemas de regresión y clasificación

## 📚 Contenido Teórico

### 1. Representación de Datos
- **Matriz de características (X)**: Datos organizados en formato tabular donde cada fila representa una observación y cada columna una característica
- **Vector objetivo (y)**: Variable que queremos predecir o analizar
- Formato estándar de Scikit-learn para el manejo de datos

### 2. Estimator API de Scikit-learn
Flujo de trabajo consistente en 4 pasos:
1. **Escoger una clase de modelo** - Importar el algoritmo apropiado
2. **Configurar hiperparámetros** - Instanciar el modelo con sus parámetros
3. **Ajustar el modelo** - Entrenar usando el método `.fit()`
4. **Aplicar el modelo** - Predecir con `.predict()` o transformar con `.transform()`

### 3. Tipos de Aprendizaje Automático

#### Aprendizaje Supervisado
- **Regresión**: Predicción de valores continuos
- **Clasificación**: Predicción de categorías o clases

#### Aprendizaje No Supervisado
- **Reducción de dimensionalidad**: Simplificar datos manteniendo información relevante
- **Clustering**: Agrupar datos similares sin etiquetas previas

## 🚀 Cómo Usar Este Material

1. **Abre el notebook** `01_ML_intro.ipynb` en Jupyter Lab/Notebook
2. **Ejecuta las celdas secuencialmente** para seguir los ejemplos
3. **Experimenta** modificando parámetros y probando con diferentes algoritmos
4. **Consulta las slides** para reforzar conceptos teóricos

## 💡 Conceptos Clave

- **Matriz de características vs Vector objetivo**
- **Entrenamiento vs Predicción**
- **Supervisado vs No supervisado**
- **Overfitting y generalización**
- **Evaluación de modelos**
- **API consistente de Scikit-learn**

## 📖 Bibliografía

- Vanderplas, J. T., & VanderPlas, J. (2016). *Python Data Science Handbook: Essential Tools for Working with Data*. O'Reilly Media
- Documentación oficial de [Scikit-learn](http://scikit-learn.org/)

## 🔗 Navegación del Curso

- **⬅️ Anterior**: [00_intro_python](https://github.com/IvTole/MachineLearning_InferenciaBayesiana_CUGDL/tree/main/00_intro_python) - Introducción a Python
- **➡️ Siguiente**: Tema 2 (próximamente)

---

*Este material forma parte del curso de Machine Learning e Inferencia Bayesiana y está diseñado para proporcionar una base sólida en los fundamentos del aprendizaje automático con Python.*
