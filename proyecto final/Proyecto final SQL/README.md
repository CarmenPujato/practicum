# Proyecto  final SQL

## Objetivo del proyecto

En este proyecto trabajaré con una base de datos de uno de los servicios que compiten en el mercado de aplicaciones de librosnanalizando su actividad. Este dataset, contiene datos sobre libros, editoriales, autores y calificaciones de clientes y reseñas de libros.

## Descrpción de los datos

Tabla **books**

Contiene datos sobre libros:

- `book_id`: identificación del libro
- `author_id`: identificación del autor o autora
- `title`: título
- `num_pages`: número de páginas
- `publication_date`: fecha de la publicación
- `publisher_id`: identificación de la editorial

Tabla **authors**

Contiene datos sobre autores:

- `author_id`: identificación del autor o autora
- `author`: el autor o la autora

Tabla **publishers**

Contiene datos sobre editoriales:

- `publisher_id`: identificación de la editorial
- `publisher`: la editorial

Tabla **ratings**

Contiene datos sobre las calificaciones de usuarios:

- `rating_id`: identificación de la calificación
- `book_id`: identificación del libro
- `username`: el nombre del usuario que revisó el libro
- `rating`: calificación

Tabla **reviews**

Contiene datos sobre las reseñas de los y las clientes:

- `review_id`: identificación de la reseña
- `book_id`: identificación del libro
- `username`: el nombre del usuario que revisó el libro
- `text`: el texto de la reseña

## Diagrama de datos


![der](https://concrete-web-bad.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F5a5cff26-7d06-45cb-8333-37837bbd1a81%2FUntitled.png?id=e1f8ab17-67c0-49e7-9a68-bc20d5ce977c&table=block&spaceId=9e4bd47b-c6e6-4ca3-bcee-279794b47315&width=1640&userId=&cache=v2)


## Librerías utilizadas

Pandas, sqlalchemy (create_engine)
