# Diagramas de Estado

Los diagramas de estado muestran el **ciclo de vida** de los objetos del sistema, los estados por los que transitan y las transiciones entre ellos.

## Módulos

| Archivo | Módulo | Estados principales |
|---------|--------|---------------------|
| `Estado-area_cliente.puml` | Área Cliente | Desconectado → Autenticando → SesiónActiva → ... |
| `Estado-citas.puml` | Sistema de Citas | Disponible → Seleccionando → Confirmando → Registrada → Finalizado |
| `Estado-consulta.puml` | Consulta Legal | NuevaSolicitud → EnRevisión → Asignada → Respondida → Cerrada |
| `Estado-gestionar-perfil.puml` | Gestionar Perfil | NoAutenticado → Autenticado → Visualizando → Editando → ... |
| `Estado-publicacion.puml` | Publicaciones | Borrador → Editando → VistaPrevia → Publicado → Archivado |
| `Estado-servicio_legales.puml` | Servicios Legales | Inicio → Navegando → Solicitando → Gestionando → Finalizado |
