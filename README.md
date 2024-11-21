# Clasificación de Flores Iris

Este proyecto demuestra la clasificación de flores Iris en tres especies (Setosa, Versicolor y Virginica) basándose en las medidas de sus sépalos y pétalos.

## Resumen del Proyecto

El proyecto utiliza un enfoque de aprendizaje automático con los siguientes pasos:

1. **Carga de Datos:** Carga el conjunto de datos Iris desde una base de datos SQLite (`database.sqlite`).
2. **Preprocesamiento de Datos:** Extrae las características relevantes (longitud del sépalo, ancho del sépalo, longitud del pétalo, ancho del pétalo) y prepara los datos para el entrenamiento del modelo.
3. **Entrenamiento del Modelo:** Entrena un modelo de Regresión Logística utilizando los datos de entrenamiento.
4. **Evaluación del Modelo:** Evalúa el rendimiento del modelo utilizando la precisión como métrica.
5. **Predicción:** Demuestra cómo utilizar el modelo entrenado para predecir la especie de nuevas flores Iris.

## Requisitos

- Python 3.x
- Librerías:
    - sqlite3
    - pandas
    - numpy
    - scikit-learn (sklearn)
    - IPython

Para instalar las librerías necesarias, puedes usar pip:

``bash pip install sqlite3 pandas numpy scikit-learn ipython``

## Uso

1. **Datos:** Asegúrate de que el archivo `database.sqlite` esté en el mismo directorio que el código.
2. **Ejecución:** Ejecuta el código Python proporcionado en el notebook (por ejemplo, `iris_classification.ipynb`).
3. **Predicción:** Utiliza la función `predecir_flor` para predecir la especie de una nueva flor Iris proporcionando las medidas de su sépalo y pétalo.

## Detalles del Modelo

- **Modelo:** Regresión Logística (multiclase, multinomial)
- **Solucionador:** 'lbfgs'
- **Métrica de Evaluación:** Precisión

## Resultados

El modelo logró una precisión de 0.9777777777777777 en los datos de prueba.

## Contribuciones

Siéntete libre de contribuir a este proyecto:

- Mejorando el rendimiento del modelo
- Añadiendo nuevas características
- Mejorando la documentación

## Licencia

Este proyecto está bajo la Licencia MIT.

