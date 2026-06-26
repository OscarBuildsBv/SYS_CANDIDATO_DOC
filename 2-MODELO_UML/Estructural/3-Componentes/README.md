# Diagrama de Componentes

Muestra la **organización de los componentes de software** del sistema en capas.

## Capas

| Capa | Descripción |
|------|-------------|
| **Presentación** | Frontend Web con módulos específicos (Cliente, Admin) |
| **Servicios** | API Gateway + 7 microservicios (Auth, Citas, Consultas, Casos, Perfil, Publicaciones, Notificaciones) |
| **Datos** | Repositorios que abstraen el acceso a la base de datos PostgreSQL |
| **Integración** | Clientes para servicios externos (SMS, Email, Pago) |
