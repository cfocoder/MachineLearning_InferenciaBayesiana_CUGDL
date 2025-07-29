# Tema 4: Regresión Lineal

Este directorio contiene los materiales del **Tema 4** del curso de **Machine Learning e Inferencia Bayesiana**.

## Contenido

### Notebooks

**`04_regresion_lineal_datos_ficticios.ipynb`**
- Exploración de regresión lineal simple con datos simulados
- Generación de datos artificiales para entender el comportamiento del modelo
- Análisis del efecto del ruido gaussiano en los datos
- Visualización de la relación entre datos y la recta verdadera subyacente

**`04_regresion_lineal_simple_multiple.ipynb`**
- Fundamentos de regresión lineal simple y múltiple
- Trabajo con el dataset clásico "Advertising" del libro "An Introduction to Statistical Learning"
- Implementación manual de algoritmos paso a paso
- Cálculo de coeficientes, residuos, R² y RSE
- Comparación entre implementación manual y librerías (scikit-learn, statsmodels)
- Interpretación de coeficientes y evaluación del desempeño

**`04_regresion_lineal_datos_categoricos_transformaciones.ipynb`**
- Tratamiento de variables categóricas en regresión lineal
- Codificación de variables categóricas para modelos de ML
- Trabajo con dataset simulado de comercio electrónico
- Interpretación de coeficientes con variables categóricas
- Aplicación de transformaciones logarítmicas en variables numéricas
- Casos prácticos con el dataset mtcars

### Material de apoyo

**`04_regresion_lineal_slides.pdf`**
- Presentación teórica del tema

## Objetivos

Al completar este tema podrás:
- Comprender los fundamentos teóricos de la regresión lineal simple y múltiple
- Implementar algoritmos de regresión desde cero
- Manejar variables categóricas en modelos de regresión
- Aplicar transformaciones para mejorar el ajuste del modelo
- Interpretar correctamente coeficientes y métricas de evaluación
- Diagnosticar supuestos del modelo de regresión lineal

## Datasets

**Advertising Dataset**
- Dataset clásico del libro "An Introduction to Statistical Learning"
- Variables: gasto en TV, radio, periódico vs ventas
- Ubicación: `../data/advertising/`

**Dataset E-commerce Simulado**
- Datos simulados de comercio electrónico
- Incluye variables categóricas y numéricas

**Dataset MTCars**
- Dataset clásico para análisis de transformaciones
- Variables relacionadas con características de automóviles

## Orden recomendado

1. `04_regresion_lineal_datos_ficticios.ipynb` - Para entender conceptos básicos
2. `04_regresion_lineal_simple_multiple.ipynb` - Para aplicar con datos reales
3. `04_regresion_lineal_datos_categoricos_transformaciones.ipynb` - Para casos avanzados

## Requisitos previos

- Conocimientos básicos de Python
- Conceptos fundamentales de estadística
- Familiaridad con Jupyter Notebooks

## Conceptos clave

- **Regresión Lineal Simple** - Relación entre una variable independiente y una dependiente
- **Regresión Lineal Múltiple** - Múltiples variables predictoras
- **Coeficiente de Determinación (R²)** - Medida de bondad de ajuste
- **Error Estándar de Residuos (RSE)** - Medida de precisión del modelo
- **Variables Dummy** - Codificación de variables categóricas
- **Transformaciones** - Técnicas para mejorar el ajuste del modelo
- **Diagnóstico de Residuos** - Validación de supuestos del modelo

---