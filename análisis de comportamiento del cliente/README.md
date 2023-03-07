# Proyecto 7: análisis del comportamiento del cliente.

## Objetivo del proyecto

Durante la investigación analizaré el comportamiento de los clientes de una empresa. Como la gente usa el producto, cuándo empiezan a comprar, cuánto dinero trae cada cliente, cuándo pagan.

El objetivo del proyecto es ayudar a optimizar los gastos de marketing. 

## Descripción de los datos

La tabla visits (registros del servidor con datos sobre las visitas al sitio web):
- Uid: identificador único del usuario;
- Device: dispositivo del usuario;
- Start Ts: fecha y hora de inicio de la sesión;
- End Ts: fecha y hora de término de la sesión;
- Source Id: identificador de la fuente de anuncios de la que proviene el usuario.

La tabla orders (datos sobre pedidos):
- Uid: identificador único del usuario que realiza un pedido;
- Buy Ts: fecha y hora del pedido;
- Revenue: ingresos de Y.Afisha de este pedido.

La tabla costs (datos sobre gastos de marketing):
- source_id: identificador de la fuente de anuncios
- dt: fecha;
- costs: gastos en esta fuente de anuncios en este día.

## Librerías

Pandas, numpy, seaborn, matplotlib.
