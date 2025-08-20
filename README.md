# 💬 ForoHub 

ForoHub es una plataforma educativa basada en Spring Boot que permite crear, gestionar y participar en foros.
Con un sistema seguro y robusto, facilita la interacción entre usuarios, temas, cursos y respuestas.

## ✨ Características

✅ Gestión de Usuarios: Autenticación y autorización con JWT.
✅ Gestión de Foros: Creación, listado y participación en temas y respuestas.
✅ Gestión de Cursos: Asociación de cursos con foros y categorías.
✅ Documentación de la API: Generada automáticamente con Swagger.
✅ Seguridad: Roles y permisos implementados con Spring Security.

## 🏗️ Arquitectura del Sistema

Diseñada con una arquitectura en capas:

API Layer: Controladores REST + configuración de seguridad.

Domain Layer: Entidades, repositorios y DTOs.

Infrastructure Layer: Configuración de BD, manejo de errores y documentación.



## 🛠️ Tecnologías Utilizadas

☕ Java 17

⚡ Spring Boot

🔐 Spring Security + JWT

🗂️ Spring Data JPA + Hibernate

🐬 MySQL 8.0+

📖 SpringDoc OpenAPI (Swagger)

⚙️ Configuración e Instalación
🔧 Prerrequisitos

JDK 17

Maven 3.8+

MySQL 8.0+

## 🚀 Pasos
1. Clonar el repositorio
git clone https://github.com/laura1saavedra/Challenge-forohub

# 2. Configurar la base de datos en application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/forohub
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña

# 3. Compilar y ejecutar
mvn clean install
mvn spring-boot:run
