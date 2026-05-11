# Privacidad y datos locales

Abre **Ajustes → Privacidad y datos**.

## Qué permanece local

La app insiste en que tus **datos se quedan en tu ordenador**. La pantalla de ajustes muestra:

- **Almacenamiento** aproximado usado bajo el área de datos de usuario.
- Recuento de **apps** y **espacios de trabajo**.
- Ruta al archivo principal de base de datos local (mostrado como `weballoon.json` bajo tu carpeta de datos de usuario).
- **Abrir carpeta** — abre ese directorio de datos en el gestor de archivos del sistema.

## Borrar datos

- **Borrar datos** (por app) — Elimina cookies, caché y datos del sitio almacenados de esa sesión aislada. La app puede recargarse la próxima vez que la abras.
- **Borrar todos los datos** — Elimina cookies, caché y almacenamiento **de todas las apps**. Es destructivo; weballoon pide confirmación.

## Limpieza automática (al salir)

Dos interruptores persisten entre reinicios:

1. **Borrar automáticamente al salir** — Al cerrar weballoon se borran los datos de navegación de las apps (cookies, caché y los tipos de almacenamiento que la app limpia al salir).
2. **Borrar caché automáticamente** — Aunque en algún texto antiguo diga «periódicamente», la implementación borra la **caché al cerrar weballoon** (no con un temporizador durante el día). Si ambas opciones automáticas están activas, prevalece el camino más fuerte de «borrar datos de navegación al salir».

Úsalos si quieres empezar limpio tras cada sesión.

## No rastrear

**Enviar cabecera Do-Not-Track** pide a los sitios que respeten DNT. No todos lo hacen; es una petición, no una garantía.

## Informes de fallos y errores

**Compartir informes de fallos y errores** está **desactivado por defecto**. Si lo activas, la app describe el envío de **diagnósticos técnicos anonimizados** para mejorar la estabilidad, **no** tu contenido de navegación, credenciales ni historial.

## Aislamiento de apps (recordatorio)

Cada app tiene **almacenamiento aislado**. Borrar o el borrado automático afecta **esa partición**, no tus otras apps.

Ver [Sesiones aisladas](isolated-sessions.md).
