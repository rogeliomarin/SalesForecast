# Forecast de Ventas Usando SARIMA

## Introducción

Este repositorio contiene el proyecto de forecast de ventas para las tiendas @WM USA. El objetivo del proyecto es predecir las ventas para las próximas 28 semanas utilizando el modelo SARIMA (Seasonal AutoRegressive Integrated Moving Average).

## Descripción del Dataset

El dataset utilizado en este proyecto incluye un total de 421,570 registros de venta correspondientes a un período de 143 semanas. Los datos comprenden las ventas totales de varias tiendas de @WM USA. Cada registro incluye información relevante sobre las ventas semanales, lo que permite analizar y modelar las tendencias y patrones estacionales de las ventas.

## Objetivo

El objetivo principal de este proyecto es generar un forecast de ventas para las siguientes 28 semanas. Este forecast es crucial para la planificación y toma de decisiones estratégicas en las tiendas @WM USA, permitiendo optimizar el inventario, la logística y las estrategias de marketing.

## Metodología

Para lograr el forecast de ventas, se ha utilizado el modelo SARIMA, que es una extensión del modelo ARIMA capaz de manejar componentes estacionales en los datos de series temporales. El proceso incluye los siguientes pasos:

1. **Análisis Exploratorio de Datos (EDA)**: Evaluación inicial de los datos para comprender las características y patrones presentes.
2. **Preprocesamiento de Datos**: Limpieza y transformación de los datos para adecuarlos al modelo.
3. **Descomposición de la Serie Temporal**: Identificación de los componentes de tendencia, estacionalidad y ruido.
4. **Entrenamiento del Modelo SARIMA**: Ajuste del modelo SARIMA a los datos históricos de ventas.
5. **Validación del Modelo**: Evaluación del desempeño del modelo utilizando métricas adecuadas y validación cruzada.
6. **Generación del Forecast**: Predicción de las ventas para las siguientes 28 semanas.

## Resultados

Los resultados del modelo SARIMA están en el archivo FCST_SARIMA.xlsx
---

Data Source: https://www.kaggle.com/datasets/divyajeetthakur/walmart-sales-prediction
