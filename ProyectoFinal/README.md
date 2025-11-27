# Proyecto Final:
## Prediciendo la magnitud de terremotos a lo largo de la historia
El cinturón de fuego del Pacífico es una de las zonas de subducción más activas del planeta. Chile, ubicado en este cinturón, es víctima de más de 7000 sismos al año, unos 20 por día que normalmente pasan desapercibidos para el chileno promedio. Pero, ¿Qué pasa cuando estos pasan a ser un peligro para la ciudadanía?

Predecir los sismos de gran magnitud con una ventana suficiente para activar las alertas ciudadanas es un desafío persistente para los centros simológicos, normalmente la ventana es de unos segundos o a lo más unos pocos minutos, por lo que poder desarrollar herramientas que amplien la ventana pueden ser muy beneficiosas para la prevención de tragedias y daños.

En este proyecto trabajamos con el dataset de Kaggle [Significant Earthquakes, 1965-2016](https://example.com](https://www.kaggle.com/datasets/usgs/earthquake-database/code)), intentado encontrar una forma de predecir la magnitud de un terremoto en función de su posición geográfica (latitud, longitud) y su profundidad.

## Pipeline:

### Eda
Revisión de distribuciones, datos faltantes, manejor de outliers, filtrado de datos, etc.

### Modelos
* RandomForestRegressor: Testeado con parámetros básicos y también con hiperparámetros optimizados mediante GridSearch
* kNN : Testeado de la misma forma que el RamdomForest

### Métricas de evaluación
* MAE
* MSE
* RMSE
* $R^2$

### Conclusiones
Analizando las curvas de aprendizaje de ambos modelos y comparando los resultados de las distintas métricas, como era de esperarse, los modelos de regresión no lograron predecir adecuadamente la magnitud basandose en las características utilizadas.

### Contacto
- justine.haefele@usm.cl
- javiera.rojasma@sansano.usm.cl
- joseph.dabre@usm.cl


