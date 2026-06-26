# Nivel 2 - Diagrama de Contenedores

Desglosa el sistema en contenedores (aplicaciones, servicios, bases de datos) que se ejecutan en tiempo de ejecución.

## Contenedores

| Contenedor | Tecnología | Descripción |
|------------|------------|-------------|
| Aplicación Web | React.js | Interfaz de usuario accesible desde el navegador |
| API Gateway | Spring Boot / Java 26 | Punto de entrada único para peticiones del frontend |
| Servicio Autenticación | Spring Security / JWT | Gestión de identidad y tokens |
| Servicio Citas | Spring Boot | Agenda y programación de citas |
| Servicio Consultas | Spring Boot | Solicitudes de consulta legal |
| Servicio Casos | Spring Boot | Gestión de casos y documentos |
| Servicio Perfil | Spring Boot | Datos de usuario y preferencias |
| Servicio Publicaciones | Spring Boot | Gestión de contenido y noticias |
| Base de Datos | PostgreSQL | Almacenamiento persistente |
