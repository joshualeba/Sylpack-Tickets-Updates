# Sylpack Tickets · Canal de actualizaciones

Este repositorio solo contiene los paquetes de instalación y actualización de **Sylpack Tickets**. El código fuente no está aquí.

## Instalar (usuario final)

**Opcion 1 - un solo archivo (recomendado):**

Descarga y ejecuta:

https://github.com/joshualeba/Sylpack-Tickets/releases/latest/download/SylpackTickets_Instalar.exe

Descarga el instalador completo desde GitHub y lo ejecuta automaticamente.

**Opcion 2 - paquete completo (sin internet en el equipo destino):**

https://github.com/joshualeba/Sylpack-Tickets-Updates/releases/latest/download/SylpackTickets_Instalador.zip

Descomprime la carpeta completa y abre `SylpackTickets_Instalador.exe`. Elige **Sede** o **Equipo cliente**.

No hay tokens, cuentas ni configuracion de GitHub.

No hay tokens, cuentas ni configuración de GitHub. La app queda lista para usarse.

## Actualizaciones

La app revisa sola este canal desde **Más → Actualizaciones**. Cuando exista una versión nueva, descarga el paquete, verifica su SHA256 y se aplica conservando `data` y `server\.env`.

- `SylpackTickets_App.zip`: paquete que usa el botón **Actualizaciones**.
- `SylpackTickets_Instalador.zip`: instalación desde cero (Sede o Cliente).
- `latest.json`: manifiesto del canal (versión, notas y SHA256).
- `checksums.txt`: verificación SHA256.

Las releases se generan automáticamente al publicar un tag en el repositorio privado.

Hecho por **Sylpack - Departamento de Sistemas**.
