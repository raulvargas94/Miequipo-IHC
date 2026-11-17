# MiEquipo — Arquitectura de información y flujos de usuario

**Fuente:** Informe IHC01, secciones 5, 6 y 7.  
**Estado:** Flujos propuestos, pendientes de verificación mediante pruebas.

## Estructura de contenidos

- **Inicio:** próximo partido y accesos a Crear partido, Jugadores y Detalle.
- **Crear partido:** campos de fecha, hora, lugar y cupos; acción Guardar.
- **Jugadores:** nombres, estados de asistencia y opción Confirmar asistencia.
- **Detalle:** resumen del encuentro y mensaje de confirmación.

## Flujo principal: confirmar asistencia

1. Ingresar a **Inicio** y consultar fecha, horario, lugar y cupos del próximo partido.
2. Seleccionar **Ver jugadores**.
3. Revisar la lista y el estado de participación.
4. Seleccionar **Confirmar asistencia**.
5. Visualizar el **Detalle** del partido.
6. Recibir un mensaje visible que indique que la asistencia fue confirmada.

```text
Inicio → Ver jugadores → Revisar estado → Confirmar asistencia
      → Detalle del partido → Mensaje de confirmación
```

## Flujo alternativo: crear un partido

```text
Inicio → Crear partido → Completar fecha, hora, lugar y cupos
      → Guardar partido → Detalle del partido
```

Si falta un campo obligatorio, el formulario solicita completarlo antes de continuar.

## Navegación e interacción

Se utilizan etiquetas directas como **Crear partido**, **Ver jugadores** y **Confirmar asistencia**, además de una opción visible para volver a Inicio. Las acciones principales se distinguen con botones verdes y las secundarias con fondo blanco y borde verde.

La interfaz prioriza fondo claro, tarjetas blancas, jerarquía visual y retroalimentación textual; los estados no dependen solamente del color.

## Alcance

Los recorridos describen el comportamiento esperado. La prueba de usabilidad y la verificación del funcionamiento están pendientes, según el informe.
