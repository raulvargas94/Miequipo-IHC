# MiEquipo — Modelo conceptual y metáfora de interfaz

**Fuente:** Informe IHC01, secciones 3 y 4.  
**Estado:** Modelo propuesto para el prototipo académico.

## Elementos principales

| Elemento | Descripción |
|---|---|
| Organizador | Crea el partido y establece fecha, horario, lugar y cupos. |
| Partido | Encuentro con fecha, hora, cancha y participantes. |
| Jugador | Consulta encuentros y puede confirmar su participación. |
| Confirmación de asistencia | Respuesta asociada a un jugador y a un partido, con estado de participación. |

## Relación entre elementos

```text
Organizador ── crea ──> Partido
                         │
                         ├── contiene datos del encuentro
                         │
Jugador ── registra ──> Confirmación de asistencia
                         │
                         └── corresponde a un Partido y a un Jugador
```

El organizador ingresa los datos de un partido; los jugadores consultan el encuentro y registran su asistencia. La confirmación permite distinguir estados como **Confirmado** y **Pendiente**.

## Metáfora de interfaz

La aplicación utiliza como referencia la **organización tradicional de un equipo de fútbol amateur**: una convocatoria con información del partido y una lista de jugadores que confirman su participación. Las tarjetas funcionan como convocatorias y la sección de jugadores como lista de asistencia.

Se proponen tonos verdes, fondos claros, botones identificables y términos familiares: *partido*, *jugadores*, *cupos* y *asistencia*.

## Alcance

El modelo explica cómo se espera que las personas comprendan las acciones de MiEquipo. No constituye una implementación de base de datos ni acredita validación con usuarios.
