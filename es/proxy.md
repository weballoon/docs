# Configuración del proxy

Abre **Ajustes → Proxy**.

## Enrutado por aplicación

Cada app puede enrutarse por su **propio** proxy o **ninguno**. Útil para:

- Proxies HTTP corporativos solo en apps de trabajo.
- Acceso SOCKS para herramientas concretas.
- Pruebas regionales combinadas con sesiones aisladas.

## Campos (con proxy activado)

- **Protocolo** — HTTP, HTTPS, SOCKS4 o SOCKS5.
- **Host** y **Puerto**.
- **Usuario** (opcional).
- **Contraseña** (opcional). La interfaz explica que puedes dejar en blanco una contraseña guardada para conservar la anterior, y hay una acción para **borrar contraseña guardada**.
- **Reglas de exclusión** — Lista tipo comas (ejemplo en la app: `localhost, 127.0.0.1, *.internal`).

## Guardar

**Guardar y recargar** guarda la configuración y **recarga esa aplicación** para que las conexiones nuevas usen la ruta. La app advierte que los cambios de proxy **cierran las conexiones existentes** de la app afectada.

## Nota de seguridad

En **Cuenta** se indica que las **contraseñas del proxy** se cifran en este dispositivo y **no** se sincronizan con la nube.

## Si la lista está vacía

Añade al menos una aplicación primero; la pantalla del proxy lo indica.
