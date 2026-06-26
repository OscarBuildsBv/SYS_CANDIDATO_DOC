# SYS-SISTEMA-ABOGADO

Sistema integral de gestión legal para bufetes de abogados. Plataforma web que permite la gestión de clientes, citas, consultas legales, casos, publicaciones y perfiles de usuario.

## Diagramas del sistema

### Modelo C4 (Arquitectura)

| Nivel | Descripción |
|-------|-------------|
| [Contexto](1-MODELO_C4/Nivel_1_Contexto/) | Visión general del sistema, actores y sistemas externos |
| [Contenedores](1-MODELO_C4/Nivel_2_Contenedores/) | Aplicaciones, microservicios y base de datos |
| [Componentes](1-MODELO_C4/Nivel_3_Componentes/) | Componentes internos del API Gateway |

### UML Comportamiento (Diagramas dinámicos)

| Tipo | Descripción | Módulos cubiertos |
|------|-------------|-------------------|
| [Casos de Uso](2-MODELO_UML/Comportamiento/1-Casos_Uso/) | Funcionalidades del sistema | Área Cliente, Citas, Consultas, Gestionar Perfil, Publicaciones, Servicios Legales |
| [Secuencia](2-MODELO_UML/Comportamiento/2-Secuencia/) | Interacción temporal entre actores y sistema | Los 6 módulos |
| [Actividades](2-MODELO_UML/Comportamiento/3-Actividades/) | Flujo de procesos de negocio | Los 6 módulos |
| [Estado](2-MODELO_UML/Comportamiento/4-Estado/) | Ciclo de vida de objetos | Los 6 módulos |
| [Tiempo](2-MODELO_UML/Comportamiento/5-Tiempos/) | Estados a lo largo del tiempo | Los 6 módulos |
| [Comunicación](2-MODELO_UML/Comportamiento/6-Comunicacion/) | Intercambio de mensajes entre componentes | Los 6 módulos |

### UML Estructural (Diagramas estáticos)

| Tipo | Descripción |
|------|-------------|
| [Clases](2-MODELO_UML/Estructural/1-Clases/) | Modelo de dominio completo del sistema |
| [Objetos](2-MODELO_UML/Estructural/2-Objetos/) | Instancias concretas del modelo |
| [Componentes](2-MODELO_UML/Estructural/3-Componentes/) | Organización del software en capas |
| [Despliegue](2-MODELO_UML/Estructural/4-Despliegue/) | Infraestructura física del sistema |
| [Paquetes](2-MODELO_UML/Estructural/5-Paquetes/) | Organización del código fuente |
| [Perfil](2-MODELO_UML/Estructural/6-Perfil/) | Estereotipos y enumeraciones del modelo |

## Tecnología

- **Backend**: Java 26 con Spring Boot
- **Frontend**: React.js
- **Base de datos**: PostgreSQL
- **Arquitectura**: Microservicios con API Gateway

## Equipo

| Integrante | Rol | Contribuciones |
|------------|-----|----------------|
| Hrems | Desarrollador | Casos de uso, secuencias, consultas, README inicial |
| Juan Diego | Analista | Diagramas de comunicación, estado, tiempo, documentación |
| Witmer17 | Analista | Secuencias, actividades, comportamientos |
| Aldo-Ct | Analista | Organización UML, casos de uso |
| Oscar | Líder | Setup inicial, C4, gestión de perfil, integración final |
