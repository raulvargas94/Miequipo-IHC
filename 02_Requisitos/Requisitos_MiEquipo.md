# MiEquipo — Requisitos iniciales

**Asignatura:** Interacción Humano Computador  
**Proyecto:** MiEquipo — Organización de partidos de fútbol amateur  
**Estado:** Propuesta inicial de diseño; pendiente de validación con usuarios.

## Problema de interacción

La coordinación de partidos mediante aplicaciones de mensajería puede dispersar la información sobre fecha, hora, lugar y asistencia. MiEquipo propone centralizar los datos del encuentro y facilitar la confirmación de participación mediante una interfaz clara.

## Usuarios considerados

| Perfil | Necesidad principal | Contexto de uso |
|---|---|---|
| Organizador de partido | Definir fecha, hora, cancha y cupos | Teléfono móvil; coordinación previa al encuentro |
| Jugador invitado | Consultar los datos y confirmar asistencia | Teléfono móvil; consulta rápida entre actividades |
| Jugador con poca experiencia digital | Identificar botones y estados sin confusión | Pantalla pequeña y conexión variable |

## Requisitos funcionales

| ID | Requisito | Prioridad | Criterio de aceptación propuesto |
|---|---|---|---|
| RF01 | Mostrar fecha, hora, lugar y cupos del próximo partido. | Alta | La pantalla de inicio presenta los cuatro datos de forma clara. |
| RF02 | Permitir crear un partido. | Alta | El formulario solicita fecha, hora, cancha y cupos, y permite guardar los datos ingresados. |
| RF03 | Mostrar la lista de jugadores y su estado. | Alta | Cada participante aparece identificado como confirmado o pendiente. |
| RF04 | Permitir confirmar asistencia. | Alta | Al seleccionar la opción correspondiente, aparece un mensaje visible de confirmación. |

## Requisitos no funcionales

| ID | Requisito | Prioridad | Criterio de aceptación propuesto |
|---|---|---|---|
| RNF01 | Mantener una navegación sencilla. | Alta | El usuario puede confirmar su asistencia mediante un recorrido breve y comprensible. |
| RNF02 | Presentar textos legibles y contraste suficiente. | Alta | Los botones, textos y estados se distinguen visualmente en las cuatro pantallas. |
| RNF03 | Ofrecer retroalimentación inmediata. | Alta | El prototipo informa al usuario cuando guarda un partido o confirma su asistencia. |

## Tareas principales

- **Jugador:** Inicio → Ver jugadores → Revisar estado → Confirmar asistencia → Detalle del partido → Mensaje de confirmación.
- **Organizador:** Inicio → Crear partido → Completar datos → Guardar partido → Detalle del partido.

## Alcance y validación

Estos requisitos se formularon a partir del análisis inicial del problema y de perfiles potenciales. **No constituyen resultados de entrevistas ni pruebas de usabilidad.** Su cumplimiento deberá contrastarse con el prototipo y, posteriormente, con usuarios reales.
