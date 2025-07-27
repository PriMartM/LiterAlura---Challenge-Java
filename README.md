# 📖LiterAlura Challenge Java
 Es una aplicación de consola escrita en Java que permite organizar y consultar una colección personal de libros. Este proyecto fue desarrollado como parte de un reto académico propuesto por Alura Latam.

---

## 🚀 Funcionalidades

- Consulta información de libros a través de la API pública **Gutendex**.  
- Convierte los datos en formato JSON a objetos Java utilizando la librería **Jackson**.  
- Guarda la información en una base de datos **PostgreSQL** mediante **JPA/Hibernate**.  
- Presenta un menú interactivo para navegar y gestionar el contenido de la biblioteca.

---

## ⚙️ Tecnologías utilizadas

- **Java 17 o superior** – Lenguaje principal del desarrollo.  
- **Spring Boot** – Framework que facilita la configuración y la gestión de componentes.  
- **Jackson** – Para convertir datos JSON en objetos Java y viceversa.  
- **JPA/Hibernate** – Solución ORM para el manejo de persistencia de datos.  
- **PostgreSQL** – Sistema de base de datos relacional.  
- **Maven** – Herramienta para la construcción del proyecto y la gestión de dependencias.

---

## 🧭 Menú principal

Al iniciar la aplicación, se despliega un menú con diversas opciones para interactuar con el sistema:

- **Buscar libro por título** – Permite consultar la API de Gutendex e insertar los resultados en la base de datos.  
- **Mostrar libros guardados** – Lista todos los libros almacenados localmente.  
- **Mostrar autores registrados** – Despliega la lista de autores en la base de datos.  
- **Filtrar autores vivos en un año específico** – Muestra qué autores estaban vivos en un determinado año.  
- **Filtrar libros por idioma** – Lista los libros según el código del idioma (por ejemplo: `en`, `es`, `fr`, `pt`).

---

## 🌍 Fuente de datos
Este sistema se alimenta de la API [Gutendex](https://gutendex.com/), que proporciona acceso a un amplio catálogo de libros de dominio público.
