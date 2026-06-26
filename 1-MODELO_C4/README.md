# Modelo C4 de Arquitectura

Esta carpeta contiene el **Modelo C4** de arquitectura de software para el Sistema de Gestión Legal SYS-SISTEMA-ABOGADO. El modelo C4 permite visualizar la arquitectura del sistema en 3 niveles de abstracción.

## Niveles

| Nivel | Archivo | Descripción |
|-------|---------|-------------|
| [Nivel 1 - Contexto](Nivel_1_Contexto/) | `dsd.puml` | Diagrama de contexto del sistema: actores externos, sistema principal y sistemas externos |
| [Nivel 2 - Contenedores](Nivel_2_Contenedores/) | `dsd.puml` | Diagrama de contenedores: aplicaciones web, microservicios, base de datos y servicios externos |
| [Nivel 3 - Componentes](Nivel_3_Componentes/) | `sdd.puml` | Diagrama de componentes: desglose interno del API Gateway y microservicios |

## Cómo visualizar los diagramas

1. Copia el contenido de cada archivo `.puml` en [PlantUML Online Server](https://www.plantuml.com/plantuml/)
2. O usa la extensión PlantUML en VS Code / IntelliJ IDEA
3. O ejecuta: `plantuml archivo.puml`
