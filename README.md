🚀 API REST: Conexión Java Spring Boot & PostgreSQL
Este proyecto es un microservicio funcional desarrollado en Java que demuestra la integración completa entre un backend robusto y una base de datos relacional. Fue diseñado para servir como puente de datos, permitiendo la gestión de información mediante una arquitectura escalable y probada a través de Postman.

🛠️ Tecnologías Utilizadas
Lenguaje: Java 17+
Framework: Spring Boot (Spring Data JPA, Spring Web)
Base de Datos: PostgreSQL
IDE: IntelliJ IDEA
Pruebas de API: Postman
Gestor de Dependencias: Maven / Gradle

📌 Características Principales
Persistencia de Datos: Implementación de JPA/Hibernate para el mapeo objeto-relacional (ORM), facilitando la comunicación con PostgreSQL.
Arquitectura por Capas: Organización limpia del código mediante controladores, servicios y repositorios.
Endpoint GET: Implementación de rutas RESTful para la recuperación eficiente de registros desde la base de datos.
Validación con Postman: Configuración de colecciones para pruebas de integración y verificación de respuestas JSON.

🏗️ Estructura del Proyecto
Controller: Define los puntos de entrada (endpoints) de la API.
Model / Entity: Representación de las tablas de PostgreSQL como clases de Java.
Repository: Interfaz para operaciones CRUD automáticas mediante Spring Data.
Resources: Configuración de la cadena de conexión (JDBC) y parámetros del servidor.

🚀 Instalación y Configuración
Clonar el repositorio:
Bash
git clone https://github.com/emersonlj03/MicroServicioGetPostman_ConexionIntelliJ_PostgreSQL.git

Configurar la Base de Datos: Modifica el archivo src/main/resources/application.properties con tus credenciales locales:
Properties
spring.datasource.url=jdbc:postgresql://localhost:5432/tu_base_de_datos
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña

Ejecutar la aplicación: Abre el proyecto en IntelliJ IDEA y ejecuta la clase principal o usa el comando:
Bash
./mvnw spring-boot:run

🧪 Pruebas en Postman
Para verificar el funcionamiento, realiza una petición GET a la URL local: GET http://localhost:8080/api/v1/recurso

💡 Nota sobre el Proyecto
Este repositorio forma parte de mi portafolio de desarrollo backend, donde aplico principios de Ingeniería de Sistemas para la optimización de flujos de datos y arquitectura de software.



💡 Nota sobre el ProyectEste repositorio forma parte de mi portafolio de desarrollo backend, donde aplico principios de Ingeniería de Sistemas para la optimización de flujos de datos y arquitectura de software.
