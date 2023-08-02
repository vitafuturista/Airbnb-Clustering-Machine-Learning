# Modelo de Clustering y Clasificación con datos de Airbnb
Creación de un modelo de clustering y uno de clasificación utilizando dichos clusters con datos de Airbnb en Madrid

Objetivo: Elaborar un modelo de clasificación en base a una tabla de datos de Airbnb extraídos de la web InsideAirbnb. Las clases para la clasificación se extraerán de un modelo de clustering hecho previamente

Para ello se ha utilizado una tabla con mucha información (21000 filas y 75 columnas), lo que ha implicado una importante tarea de limpieza

Al contrario de lo que pensaba, el precio no ha sido crucial a la hora de definir los clusters. El modelo ha tomado más en cuenta características como el número de habitaciones o número de reviews en lugar del precio.

Entre las principales conclusiones se extrae que existen características no contempladas en las tablas como la decoración, el mobiliario, etc… que pueden influir en la variabilidad de los precios y no han sido considerados en nuestros datos originales. Esto dificulta la construcción de modelos para predecir el precio como una regresión lineal
