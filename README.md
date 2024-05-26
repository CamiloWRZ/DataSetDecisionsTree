# DataSetDecisionsTree

# Proyecto de Clasificación con Árbol de Decisión

## Descripción del Proyecto

Este proyecto implementa un modelo de clasificación utilizando un árbol de decisión para predecir la supervivencia de los pasajeros del Titanic. El dataset utilizado es el famoso Titanic dataset, el cual contiene información sobre los pasajeros como su clase, edad, sexo, entre otros.

## Contenido del Proyecto

1. [Preparación del entorno](#preparación-del-entorno)
2. [Carga y preparación de datos](#carga-y-preparación-de-datos)
3. [División del conjunto de datos](#división-del-conjunto-de-datos)
4. [Codificación de variables categóricas](#codificación-de-variables-categóricas)
5. [Entrenamiento del modelo de árbol de decisión](#entrenamiento-del-modelo-de-árbol-de-decisión)
6. [Evaluación del modelo](#evaluación-del-modelo)
7. [Visualización del árbol de decisión](#visualización-del-árbol-de-decisión)
8. [Notas](#notas)
9. [Contribuciones](#contribuciones)
10. [Licencia](#licencia)

## Preparación del Entorno

En esta sección, se indican los pasos necesarios para instalar las librerías necesarias para ejecutar el proyecto, incluyendo pandas, numpy, matplotlib, seaborn y scikit-learn.

## Carga y Preparación de Datos

Se explica cómo cargar el dataset de Titanic y preparar los datos para el análisis. Esto incluye la selección de columnas relevantes y el manejo de valores faltantes en la columna 'Age'.

## División del Conjunto de Datos

Se detalla cómo dividir el conjunto de datos en características (X) y etiqueta (y), y cómo dividir estos conjuntos en subconjuntos de entrenamiento y prueba utilizando `train_test_split`.

## Codificación de Variables Categóricas

Se describe el proceso de codificación de las variables categóricas, específicamente la columna 'Sex', utilizando `OneHotEncoder`. También se explica cómo eliminar las columnas originales después de la codificación y cómo concatenar las columnas codificadas con el resto del conjunto de datos.

## Entrenamiento del Modelo de Árbol de Decisión

En esta sección, se detalla cómo entrenar el modelo de árbol de decisión utilizando el conjunto de datos de entrenamiento.

## Evaluación del Modelo

Se explica cómo realizar predicciones con el modelo entrenado y cómo evaluar su precisión utilizando la métrica de `accuracy_score`.

## Visualización del Árbol de Decisión

Se muestra cómo visualizar el árbol de decisión utilizando `plot_tree` de `matplotlib`, proporcionando una representación visual del modelo entrenado.








