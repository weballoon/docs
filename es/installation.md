# Instalación y plataformas compatibles

Los builds oficiales de escritorio cubren **macOS**, **Windows** y **Linux**, en **Intel 64 bits (x64)** y **Apple Silicon / ARM64** cuando aplica.

## macOS

Los instaladores se publican como **DMG** y **ZIP** (ambas arquitecturas en builds de release). Tras abrir el DMG, arrastra **weballoon** a Aplicaciones (o tu flujo habitual).

**Enlace profundo:** la app registra el esquema `weballoon://` para que los **enlaces mágicos** del correo vuelvan a la app al hacer clic.

## Windows

El formato de release es **NSIS** (instalador) para x64 y arm64.

El mismo esquema **`weballoon://`** sirve para completar el enlace mágico.

## Linux

Los releases usan **AppImage** (x64 y arm64). Las actualizaciones automáticas dentro de la app en Linux pueden funcionar solo si instalaste desde un paquete de release compatible (la app indica si las actualizaciones no están disponibles en tu entorno).

## Actualizaciones

En **Ajustes**, junto a la zona de cuenta, la tarjeta **Actualizaciones de la app** permite **buscar actualizaciones** y, cuando hay una descarga lista, **reiniciar para actualizar**. Si una actualización se descarga en segundo plano, weballoon puede pedirte reiniciar cuando te convenga.

Algunos entornos (por ejemplo builds de desarrollo local) no ofrecen actualizaciones automáticas; la tarjeta indicará que no están disponibles y el motivo.

## Requisitos del sistema

weballoon es un runtime web de escritorio. Para un uso fluido basta un equipo moderno normal con varios GB de RAM libre; cada app abierta o en segundo plano consume memoria adicional (ver [Hibernación y memoria](hibernation-and-memory.md)).
