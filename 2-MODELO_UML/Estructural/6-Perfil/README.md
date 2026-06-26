# Diagrama de Perfil

Define los **estereotipos y enumeraciones** utilizados en el modelo UML del sistema.

## Estereotipos

| Estereotipo | Descripción |
|-------------|-------------|
| `EntidadBase` | Clase abstracta con id, fechaCreacion, fechaActualización |
| `Auditable` | Clase abstracta con creadoPor, modificadoPor |
| `SoftDeletable` | Clase abstracta con eliminación lógica |
| `ApiResponse` | Estructura estándar de respuesta API |
| `PageableResponse` | Estructura para respuestas paginadas |

## Enumeraciones

- `TipoUsuario`: CLIENTE, ABOGADO, ADMINISTRADOR
- `EstadoCaso`: ABIERTO, EN_PROCESO, PENDIENTE, RESUELTO, CERRADO, ARCHIVADO
- `EstadoCita`: SOLICITADA, CONFIRMADA, REPROGRAMADA, CANCELADA, COMPLETADA
- `ModalidadCita`: PRESENCIAL, VIRTUAL, TELEFONICA
- `TipoDocumento`: DNI, CARNET_EXTRANJERIA, PASAPORTE
- `TipoNotificacion`: EMAIL, SMS, PUSH, IN_APP
- `TipoPublicacion`: ARTICULO, NOTICIA, EVENTO, RECURSO
