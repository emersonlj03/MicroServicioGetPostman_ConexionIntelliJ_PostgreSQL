# 🚀 API REST: Conexión Java Spring Boot & PostgreSQL

Este proyecto es un **microservicio funcional** desarrollado en Java que demuestra la integración completa entre un backend robusto y una base de datos relacional. Fue diseñado para servir como puente de datos, permitiendo la gestión de información mediante una arquitectura escalable y probada a través de Postman.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Java 17+
* **Framework:** Spring Boot (Spring Data JPA, Spring Web)
* **Base de Datos:** PostgreSQL
* **IDE:** IntelliJ IDEA
* **Pruebas de API:** Postman
* **Gestor de Dependencias:** Maven / Gradle

---

## 📌 Características Principales

* **Persistencia de Datos:** Implementación de JPA/Hibernate para el mapeo objeto-relacional (ORM), facilitando la comunicación con PostgreSQL.
* **Arquitectura por Capas:** Organización limpia del código mediante controladores, servicios y repositorios.
* **Endpoint GET:** Implementación de rutas RESTful para la recuperación eficiente de registros desde la base de datos.
* **Validación con Postman:** Configuración de colecciones para pruebas de integración y verificación de respuestas JSON.

---

## 🏗️ Estructura del Proyecto

* `Controller`: Define los puntos de entrada (endpoints) de la API.
* `Model / Entity`: Representación de las tablas de PostgreSQL como clases de Java.
* `Repository`: Interfaz para operaciones CRUD automáticas mediante Spring Data.
* `Resources`: Configuración de la cadena de conexión (JDBC) y parámetros del servidor.

  Proy


