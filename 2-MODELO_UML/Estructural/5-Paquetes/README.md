# Diagrama de Paquetes

Muestra la **organización del código fuente** siguiendo una arquitectura en capas.

## Paquetes

| Paquete | Propósito |
|---------|-----------|
| `presentation` | Controladores REST (punto de entrada de las peticiones) |
| `service` | Lógica de negocio del sistema |
| `repository` | Acceso a datos (interfaces JPA) |
| `model` | Entidades del dominio |
| `security` | Configuración JWT y Spring Security |
| `config` | Configuraciones generales (CORS, Swagger, etc.) |
| `dto` | Objetos de transferencia de datos |
| `exception` | Manejo global de excepciones |
| `util` | Utilidades generales |
