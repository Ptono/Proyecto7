### Código del Proyecto 7
![Código del Proyecto 7](https://colab.research.google.com/drive/1WwBHniejXklAUIxOBQR3_g8_8sW74cvg#scrollTo=UalEvuqd8s46)

# Proyecto7
# Análisis de Aplicaciones en App Store

## 1. Introducción

El análisis y exploración de datos desplegados en este cuaderno se basan en el conjunto de datos de Google Play Store, que contiene información valiosa sobre más de 3.5 millones de aplicaciones. Inspirado por el trabajo del Dr. Ammar Tufail, este proyecto va más allá de la reproducción, buscando mejorar y expandir las metodologías existentes.

La limpieza y análisis meticuloso de los datos revelan tendencias, narrativas detrás del éxito de las aplicaciones y desafíos enfrentados por los desarrolladores. Este cuaderno está diseñado para entusiastas de los datos, desarrolladores de aplicaciones y usuarios curiosos que deseen adentrarse en el fascinante mundo de las aplicaciones de Google Play Store.

## 2. Descripción

### 2.1 Acerca del conjunto de datos

El conjunto de datos proporciona información detallada sobre aplicaciones en Google Play Store. Cada aplicación está representada por diversas características, como la categoría, calificación, tamaño, instalaciones, y más. Estos datos son esenciales para comprender el ecosistema de aplicaciones y ofrecen información valiosa para desarrolladores y empresas.



### 2.2 Acerca de las columnas

El conjunto de datos incluye 13 columnas que proporcionan información detallada sobre cada aplicación:

1. **Aplicación:** El nombre de la aplicación.
2. **Categoría:** La categoría a la que pertenece la aplicación.
3. **Calificación:** La calificación de la aplicación en Play Store.
4. **Reseñas:** El número de reseñas de la aplicación.
5. **Tamaño:** El tamaño de la aplicación.
6. **Instalar:** El número de instalaciones de la aplicación.
7. **Tipo:** El tipo de aplicación (Gratis/Pago).
8. **Precio:** El precio de la aplicación (0 si es gratuita).
9. **Clasificación del contenido:** La clasificación del público objetivo de la aplicación.
10. **Géneros:** El género de la aplicación.
11. **Última actualización:** La fecha de la última actualización de la aplicación.
12. **Ver actual:** La versión actual de la aplicación.
13. **Versión de Android:** La versión mínima de Android requerida para ejecutar la aplicación.

## 3.PLANTEAMIENTO DE PROYECTO
# NOMBRE: Análisis de Aplicaciones en App Store

## Problema

El desafío es identificar la mejor aplicación en la App Store, considerando diversas métricas como la calificación, el tamaño y el género de la aplicación. Con millones de aplicaciones disponibles, los usuarios a menudo se enfrentan a la dificultad de seleccionar la aplicación que mejor se adapte a sus necesidades.

## Proceso a Solución

Para abordar este problema, implementamos un proceso detallado:

1. **Recopilación de Datos:** Utilizamos datos de la App Store que incluyen información sobre la calificación, tamaño, género y otras métricas de las aplicaciones.

2. **Limpieza y Preprocesamiento:** Se llevaron a cabo acciones para manejar valores nulos, convertir datos a formatos adecuados y normalizar la información.

3. **Análisis Exploratorio de Datos (EDA):** Investigamos las relaciones entre la calificación, el tamaño y el género de las aplicaciones. Esto proporcionó información valiosa sobre las tendencias y patrones del conjunto de datos.

4. **Entrenamiento de Modelo:** Utilizamos un modelo de clasificación (RandomForestClassifier) para predecir la calificación de las aplicaciones en función de sus características.

5. **Visualizaciones:**
   - Gráficas de barras para mostrar la distribución de categorías de aplicaciones.
   - Gráfica de correlación para examinar las relaciones entre variables numéricas.
   - Gráfica de distribución de tamaños de aplicaciones para comprender la diversidad de tamaños.

6. **Rendimiento del Modelo:**
   - Evaluamos el rendimiento del modelo mediante métricas de clasificación.
   - Comparamos las predicciones del modelo con los valores reales para comprender su eficacia.

## Metodologías Usadas

Utilizamos la metodología de ciencia de datos, que incluye:

- Recopilación y exploración de datos.
- Limpieza y preprocesamiento.
- Análisis exploratorio de datos (EDA).
- Entrenamiento de modelo de clasificación.

## Gráficas de Rendimiento

### Distribución de Categorías
![Distribución de Categorías](https://github.com/Ptono/Proyecto7/blob/main/BarrasDeCategoria.png?raw=true)

### Matriz de Correlación
![Matriz de Correlación](https://github.com/Ptono/Proyecto7/blob/main/GraficaDeCorrelacion.png?raw=true)

### Distribución de Tamaños de Aplicaciones
![Distribución de Tamaños de Aplicaciones](https://github.com/Ptono/Proyecto7/blob/main/DistribucionDeTamanos.png?raw=true)

### Rendimiento de Metrica
![Rendimiento de Metrica](https://github.com/Ptono/Proyecto7/blob/main/RendimientoDeMetrica.png?raw=true)


## Demostración del Modelo

La demostración del modelo se realiza mediante la predicción de la calificación de una aplicación específica. Esto proporciona una vista práctica de cómo el modelo puede ayudar a tomar decisiones informadas al elegir una aplicación.

## Aprendizajes Obtenidos

Durante este proyecto, aprendimos la importancia de un análisis exhaustivo de datos para comprender mejor las tendencias y patrones en el mundo de las aplicaciones. Además, observamos cómo el uso de modelos de clasificación puede facilitar la toma de decisiones para los usuarios.


