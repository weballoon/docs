# Solución de problemas

Pasos tranquilos y prácticos. Si nada ayuda, anota la **versión de weballoon** (Ajustes → Actualizaciones de la app) y el **SO** al pedir soporte.

## El enlace mágico no vincula el dispositivo

- Confirma que abriste el enlace en la **misma máquina** donde está instalado weballoon.
- macOS / Windows: asegúrate de que los enlaces **`weballoon://`** abren weballoon (ajustes del sistema del «manejador por defecto»).
- Prueba **Reenviar enlace** en **Ajustes → Cuenta** tras la espera.
- Revisa carpetas de spam.

## «Límite del plan gratuito alcanzado»

Tienes **10 apps** o intentas crear más de **2** espacios en Free. Quita una app o espacio, o mejora el plan en **Planes** ([Planes y facturación](plans-and-billing.md)).

## El sitio se ve roto o en blanco

- **Recargar** en la barra de título.
- **Ajustes → Bloqueador de anuncios** — prueba a desactivar el bloqueo **solo para esa app**.
- **Ajustes → Proxy** — revisa host, puerto y exclusiones; guarda y deja que la app recargue.

## No hay notificaciones de un sitio

- Activa **Ejecutar en segundo plano** para esa app en **Ajustes → Notificaciones**.
- El sitio debe usar de verdad **notificaciones web**; algunos solo usan avisos dentro de la página.
- Si **estás dentro** de esa app con foco, weballoon puede omitir duplicar entradas en la campana interna (las notificaciones del SO pueden seguir apareciendo según el sitio).

## El atajo no funciona

- Haz clic fuera de los campos del sitio (barra de título o cromo de weballoon) y prueba de nuevo ([Atajos de teclado](keyboard-shortcuts.md)).
- Los saltos **Ctrl/Cmd+número** al espacio solo se registran **dentro** de una app web abierta; desde **Mis apps** o **Ajustes** usa el botón de espacio o **Mayús+W**.

## CPU o RAM altos

- **Ajustes → Administrador de tareas** — ordena por memoria o CPU.
- Reduce apps con **Ejecutar en segundo plano**.
- Cierra vistas de app que no uses.

## Las actualizaciones nunca aparecen

La tarjeta **Actualizaciones de la app** explica cuándo las comprobaciones automáticas están **desactivadas** (builds de desarrollo, algunas configuraciones Linux o variables de entorno). Instala un **release** oficial cuando puedas.

## Cerré la ventana pero weballoon «sigue ahí» (Windows / Linux)

Puede haber un **icono en bandeja**. **Clic derecho → Salir** para cerrar del todo, o clic en el icono para mostrar la ventana de nuevo ([Resumen de ajustes](settings.md)).

## Tema incorrecto tras cambiar el sistema

El tema de weballoon es **manual** (oscuro / claro) en Ajustes, no «seguir al sistema» en el selector actual: elige el tema que quieras en **Apariencia**.
