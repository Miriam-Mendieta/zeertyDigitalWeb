# zeertyDigitalWeb

> **Solución centralizada para el inventario, custodia de credenciales y gestión documental de activos digitales para PYMEs y autónomos.**

---

## 📝 Descripción del Proyecto

Aplicación web desarrollada con **Spring Boot** y **Thymeleaf** orientada a resolver la fragmentación en la gestión de recursos digitales (dominios, certificados SSL, accesos, facturas y licencias). 

Permite organizar recursos, gestionar permisos mediante roles, controlar caducidades y subida de documentos.

---

## 🛠️ Stack Tecnológico

* **Lenguaje:** Java 25
* **Gestor de Dependencias:** Maven
* **Framework Backend:** Spring Boot 4.1.1
* **Módulos Principales:**
  * **Spring Web:** Arquitectura MVC y API REST
  * **Spring Security:** Autenticación y Control de Acceso Basado en Roles (RBAC)
  * **Validation:** Validación de datos en formularios y DTOs
  * **Spring Boot DevTools:** Recarga rápida en entorno de desarrollo
  * **Lombok:** Reducción de código repetitivo (Getters, Setters, Constructors)
* **Frontend:** Thymeleaf + HTML5 / CSS3
* **Base de Datos:** MySQL (En desarrollo local)

---

## 📁 Estructura del Proyecto

```text
zeertyDigitalWeb/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/MiriamMendieta/zeertyDigitalWeb/
│   │   │       ├── config/        # Configuración de Seguridad y Beans
│   │   │       ├── controller/    # Controladores MVC (Thymeleaf)
│   │   │       ├── model/         # Entidades JPA (Usuario, Activo, Rol...)
│   │   │       ├── repository/    # Repositorios Spring Data JPA
│   │   │       └── service/       # Lógica de Negocio
│   │   └── resources/
│   │       ├── static/            # CSS, JS, Imágenes
│   │       ├── templates/         # Vistas Thymeleaf
│   │       └── application.properties # Configuración de entorno local
└── pom.xml                        # Configuración y dependencias Maven


Autora: Miriam Mendieta.-
