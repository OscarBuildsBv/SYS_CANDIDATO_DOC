# Diagrama de Despliegue

Describe la **infraestructura física** del sistema: servidores, dispositivos y conexiones de red.

## Nodos

| Nodo | Descripción |
|------|-------------|
| **Dispositivo Cliente** | Navegador web o app móvil del usuario |
| **Servidor Web** | Nginx + Aplicación React |
| **Servidor API** | API Gateway y microservicios Spring Boot |
| **Servidor Base de Datos** | PostgreSQL con PgBouncer |
| **Servidor de Archivos** | Almacenamiento S3 + CDN |
| **Servicios Externos** | Gateway SMS y servidor SMTP |
