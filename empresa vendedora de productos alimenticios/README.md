# Proyecto integrado 2: empresa vendedora de productos alimenticios

## Objetivo del proyecto

Investigar el comportamiento del usuario para la aplicación de la empresa.

El proyecto se desarrollará en dos partes. La primera tendrá el análisis del embudo de ventas. Analizaré la cantidad de eventos que se producen, la cantidad de usuarios que hay y cuantos pasan de evento en evento. La segunda etapa, tendrá el análisis del test A/A/B. En este tenemos dos grupos de control(A/A) y un grupo de prueba (B).

## Descripción de los datos 

La tabla con la cual trabajaré contiene la siguiente información:
- EventName: nombre del evento.
- DeviceIDHash: identificador de usuario unívoco.
- EventTimestamp: hora del evento.
- ExpId: número de experimento: 246 y 247 son los grupos de control, 248 es el grupo de prueba.

## Librerías utilizadas

Pandas, scipy, numpy, math, plotly (graph_objects)
