# Proyecto 4: empresa de telecomunicaciones

## Objetivo del proyecto 

Este proyecto se realizará con el objetivo de analizar los datos provistos por una empresa de telecomunicaciones, específicamente dos tarifas distintas de prepago, para determinar si alguno de ellos genera mayores ingresos y en base a eso ajustar el presupuesto de publicidad.
Realizaré dos pruebas de hipótesis. La primera, ver si el ingreso promedio de los usuarios de cada tarifa difiere. La segunda, ver si el ingreso promedio de los usuarios en el área de New York/New Jersey es diferente a la de los usuarios en otras regiones.
## Descripción de los datos

Voy a utilizar 5 tablas enviadas por la empresa:

La tabla 'users' (datos sobre los usuarios):

- user_id — identificador único del usuario
- first_name — nombre del usuario
- last_name — apellido del usuario
- age — edad del usuario (en años)
- reg_date — fecha de suscripción (dd, mm, aa)
- churn_date — la fecha en que el usuario dejó de usar el servicio (si el valor es ausente, la tarifa se estaba usando cuando se recuperaron estos datos)
- city — ciudad de residencia del usuario
- plan — nombre de la tarifa

La tabla 'calls' (datos sobre las llamadas):

- id — identificador único de la llamada
- call_date — fecha de la llamada
- duration — duración de la llamada (en minutos)
- user_id — el identificador del usuario que realiza la llamada

La tabla 'messages' (datos sobre los SMS):

- id — identificador único del SMS
- message_date — fecha del SMS
- user_id — el identificador del usuario que manda el SMS

La tabla 'internet' (datos sobre las sesiones web):

- id — identificador único de la sesión
- mb_used — el volumen de datos gastados durante la sesión (en megabytes)
- session_date — fecha de la sesión web
- user_id — identificador del usuario

La tabla 'plans' (datos sobre las tarifas):

- plan_name — nombre de la tarifa
- usd_monthly_fee — pago mensual en dólares estadounidenses
- minutes_included — minutos incluidos al mes
- messages_included — SMS incluidos al mes
- mb_per_month_included — datos incluidos al mes (en megabytes)
- usd_per_minute — precio por minuto tras exceder los límites del paquete (por ejemplo, si el paquete incluye 100 minutos el operador cobrará el minuto 101)
- usd_per_message — precio por SMS tras exceder los límites del paquete
- usd_per_gb — precio por gigabyte de los datos extra tras exceder los límites del paquete (1 GB = 1024 megabytes)

## Librerías utilizadas

Pandas, numpy, scipy, matplotlib.pyplot, scipy.stats
