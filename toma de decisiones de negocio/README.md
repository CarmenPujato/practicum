# Proyecto 8: toma de decisiones de negocio

## Objetivo del proyecto

Analizaré junto con el departamento de marketing de una tienda en línea una lista de hipótesis que hemos recopilado con el objetivo de ayudar a aumentar los ingresos en la tienda.

El trabajo será realizado en dos partes, la primera donde haré un análisis de las hipótesis recopiladas y priorizaré una de ellas y en la segunda parte, realizaré un análisis de test A/B

## Descripción de los datos
Datos utilizados en la primera parte del proyecto:
Usaré una tabla con los siguientes datos:
- Hypotheses: breves descripciones de las hipótesis
- Reach: alcance del usuario, en una escala del uno a diez
- Impact: impacto en los usuarios, en una escala del uno al diez
- Confidence: confianza en la hipótesis, en una escala del uno al diez
- Effort: los recursos necesarios para probar una hipótesis, en una escala del uno al diez. Cuanto mayor sea el valor Effort, más recursos requiere la prueba.

Datos utilizados en la segunda parte del proyecto:
Usaré dos tablas:

Tabla Orders:
- transactionId: identificador de pedido
- visitorId: identificador del usuario que realizó el pedido
- date: fecha del pedido
- revenue: ingresos del pedido
- group: el grupo del test A/B al que pertenece el usuario

Tabla Visits:
- date: la fecha
- group: grupo del test A/B
- visits: el número de visitas en la fecha especificada para el grupo de test A/B especificado

## Librerías

Pandas, numpy, scipy.stats, datetime, matplotlib.pyplot. 
