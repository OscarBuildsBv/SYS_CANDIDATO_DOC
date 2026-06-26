# Nivel 3 - Diagrama de Componentes

Desglosa el API Gateway en sus componentes internos y muestra la relación con cada microservicio.

## Componentes del API Gateway

- **Service Discovery** (Eureka): Registro y descubrimiento de microservicios
- **API Gateway Service** (Spring Cloud Gateway): Enrutamiento, filtros y balanceo
- **Authentication Filter**: Filtro JWT para autenticación y autorización
- **Rate Limiter** (Resilience4j): Control de tasa de peticiones
- **Circuit Breaker** (Resilience4j): Protección contra fallos en cascada

## Microservicios internos

Cada microservicio (Auth, Citas, Consultas, Casos, Perfil, Publicaciones) se conecta a la base de datos PostgreSQL para su persistencia.
