# Sylpack Tickets · Canal de actualizaciones

Este repositorio solo contiene los paquetes de instalación y actualización de **Sylpack Tickets**. El código fuente no está aquí.

## Instalar (usuario final)

1. Descarga el instalador más reciente:

   **https://github.com/joshualeba/Sylpack-Tickets-Updates/releases/latest/download/SylpackTickets_Instalador.zip**

2. Descomprime el `.zip` completo (no abras nada desde dentro del `.zip`).
3. Abre `SylpackTickets_Instalador.exe`.
4. Elige **Sede** o **Equipo cliente** y espera a que termine.

No hay tokens, cuentas ni configuración de GitHub. La app queda lista para usarse.

## Actualizaciones

La app revisa sola este canal desde **Más → Actualizaciones**. Cuando exista una versión nueva, descarga el paquete, verifica su SHA256 y se aplica conservando `data` y `server\.env`.

- `SylpackTickets_App.zip`: paquete que usa el botón **Actualizaciones**.
- `SylpackTickets_Instalador.zip`: instalación desde cero (Sede o Cliente).
- `latest.json`: manifiesto del canal (versión, notas y SHA256).
- `checksums.txt`: verificación SHA256.

Las releases se generan automáticamente al publicar un tag en el repositorio privado.

Hecho por **Sylpack - Departamento de Sistemas**.
