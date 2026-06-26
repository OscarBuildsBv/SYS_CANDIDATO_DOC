# Diagrama de Clases

Modelo de dominio completo del Sistema de Gestión Legal.

## Clases principales

| Clase | Tipo | Descripción |
|-------|------|-------------|
| `Usuario` | Abstracta | Clase base con atributos comunes (id, nombre, email, password) |
| `Cliente` | Hereda de Usuario | Usuario que solicita servicios legales |
| `Abogado` | Hereda de Usuario | Profesional legal que atiende casos |
| `Administrador` | Hereda de Usuario | Gestor del sistema |
| `Caso` | Entidad | Caso legal con documentos asociados |
| `Cita` | Entidad | Cita agendada por el cliente |
| `Consulta` | Entidad | Consulta legal realizada por el cliente |
| `Publicación` | Entidad | Contenido creado por el abogado |
| `Documento` | Entidad | Archivo asociado a un caso |
| `Notificación` | Entidad | Notificación enviada al usuario |
| `Token` | Entidad | Token de autenticación JWT |
