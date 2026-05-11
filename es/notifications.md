# Notificaciones

weballoon gestiona dos ideas relacionadas: **notificaciones del sistema** de sitios que usan la API de notificaciones del navegador, y una **lista de notificaciones dentro de la app** para ponerte al día sin buscar toasts.

## Centro de notificaciones en la app

- Pulsa la **campana** del dock, o **Mayús+N** (cuando el foco lo permita; ver [Atajos de teclado](keyboard-shortcuts.md)).
- Puedes **marcar todo como leído**, abrir un elemento para ir a la app o descartar entradas.
- Mientras **ya estás viendo** una app, las notificaciones nuevas de esa misma app **no se duplican** en la lista interna (la app puede seguir usando la notificación del SO si el sitio lo soporta).

Se guarda una lista corta (hasta 100 elementos recientes) para que el panel siga siendo útil.

## «Ejecutar en segundo plano» (por app)

En **Ajustes → Notificaciones**, cada app tiene un interruptor etiquetado **Run in background** en la interfaz en inglés. Si está activado:

- La sesión de esa app puede mantenerse activa para que cosas como **websockets** sigan funcionando mientras miras otra app u otro espacio.
- weballoon muestra un recordatorio de que **cada** app en segundo plano usa unos **50–150 MB** de memoria aproximadamente (el uso real varía según el sitio).

Si aún no tienes apps, el panel indica que añadas apps primero y luego elijas cuáles deben seguir ejecutándose.

## Uso práctico

- Activa **Ejecutar en segundo plano** en chat o correo donde quieras alertas mientras usas otras partes de weballoon.
- Déjalo desactivado en sitios pesados o poco usados para ahorrar RAM.

Ver también [Hibernación y memoria](hibernation-and-memory.md).
