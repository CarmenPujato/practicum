# Proyecto final: servicio de telefonía virtual

## Objetivo del proyecto

Analizar la base de datos de la compañía para identificar aquellos operadores que son ineficaces. 

## Descripción de los datos 

El dataset telecom_dataset_us contiene las siguientes columnas:

- user_id: ID de la cuenta de cliente
- date: fecha en la que se recuperaron las estadísticas
- direction: "dirección" de llamada (out para saliente, in para entrante)
- internal: si la llamada fue interna (entre los operadores de un cliente o clienta)
- operator_id: identificador del operador
- is_missed_call: si fue una llamada perdida
- calls_count: número de llamadas
- call_duration: duración de la llamada (sin incluir el tiempo de espera)
- total_call_duration: duración de la llamada (incluido el tiempo de espera)

El conjunto de datos telecom_clients_us tiene las siguientes columnas:
- user_id: ID de usuario/a
- tariff_plan: tarifa actual de la clientela
- date_start: fecha de registro de la clientela

## Librerías utilizadas

Pandas, plotly.express, seaborn, matplotlib.pyplot 

## Visualización de datos
Tableau
