# Proyecto final A/B test 

## Objetivo del proyecto
Durante este proyecto trabajaré con los datos de una tienda internacional en línea con el objetivo de probar si existen cambios relacionados con la introducción de un sistema de recomendaciones mejorado.

Analizaré específicamente una prueba A/B que lanzaron los miembros de la compañía para ver si se cumple el objetivo deseado o no.

## Descripción de los datos utilizados

Utilizaré las siguientes tablas:

ab_project_marketing_events_us: contiene el calendario de eventos de marketing para 2020

Estructura ab_project__marketing_events_us:

- name — el nombre del evento de marketing
- regions — regiones donde se llevará a cabo la campaña publicitaria
- start_dt — fecha de inicio de la campaña
- finish_dt — fecha de finalización de la campaña

final_ab_new_users_upd_us: contiene todos los usuarios que se registraron en la tienda en línea desde el 7 hasta el 21 de diciembre de 2020

Estructura final_ab_new_users_upd_us:

- user_id
- first_date — fecha de inscripción
- region
- device — dispositivo utilizado para la inscripción

final_ab_events_upd_us: contiene todos los eventos de los nuevos usuarios en el período comprendido entre el 7 de diciembre de 2020 y el 1 de enero de 2021

Estructura final_ab_events_upd_us:

- user_id
- event_dt — fecha y hora del evento
- event_name — nombre del tipo de evento
- details — datos adicionales sobre el evento (por ejemplo, el pedido total en USD para los eventos purchase)

final_ab_participants_upd_us: tabla con los datos de los participantes de la prueba

Estructura final_ab_participants_upd_us:

- user_id
- ab_test — nombre de la prueba
- group — el grupo de prueba al que pertenecía el usuario

## Librerías utilizadas

Pandas, plotly.express, plotly(graph_objects), scipy (stats), numpy, math
