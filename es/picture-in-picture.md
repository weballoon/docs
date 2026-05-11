# Imagen en imagen (vídeo)

weballoon incluye un **panel de vídeo flotante** (en inglés puede mostrarse como **PiP Video**) para ver un stream mientras usas otras partes de la app.

## Abrir el panel

Pulsa **Mayús+S** (o el mismo atajo desde dentro de una app incrustada).

## Uso

1. Se abre una ventana flotante pequeña.
2. Pega o escribe una **URL de página de vídeo** y pulsa **Reproducir** (o envía el formulario).
3. En hosts habituales, weballoon convierte enlaces a un reproductor **incrustado** cuando puede:
   - **YouTube** (`youtube.com/watch?v=…` o `youtu.be/…`)
   - **Vimeo**
   - **Dailymotion**
4. Otras URLs se cargan **directamente en el iframe**; si reproducen depende de las reglas de incrustación del sitio (algunos bloquean iframes).

## Controles

- **Cerrar** — cierra el flotante y borra la URL.
- **Cambiar URL** (con vídeo activo) — vuelve al paso de introducir URL.
- **Restablecer posición** — si moviste la ventana, un control puede restablecer el diseño (icono con flechas tipo expandir en la barra de controles).
- Puedes **arrastrar** el panel por el cromo vacío (no por campos, botones ni el iframe).

## Notas

- **No** es la API nativa de imagen en imagen del navegador para pestañas arbitrarias; es el **flotante PiP** dedicado de weballoon con reproducción en iframe.
- La reproducción automática puede depender del sitio y de la configuración de audio del sistema.
