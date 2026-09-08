# Geolocalización

Proyecto sencillo en HTML, CSS y JavaScript para obtener la ubicación actual del usuario con la API de geolocalización del navegador.

## Cómo abrirlo

1. Abre PowerShell en la carpeta del proyecto.
2. Ejecuta el servidor compartido:
   ```bash
   node server.js
   ```
3. En la PC visita:
   ```text
   http://localhost:8000
   ```
4. Conecta el celular a la misma red Wi-Fi, busca la IPv4 de la PC con `ipconfig` y abre:
   ```text
   http://IP-DE-LA-PC:8000
   ```

No abras `index.html` directamente con `file://`: en ese modo cada dispositivo usa su propio almacenamiento y no puede compartir el código.

## Funcionalidad

- Solicita acceso a la ubicación del usuario.
- Muestra latitud, longitud, precisión y hora.
- Genera un enlace para ver la posición en Google Maps.
- Comparte el código de vinculación entre dispositivos mediante el servidor GMAC.

## Nota

La geolocalización solo funciona con permiso del usuario y desde un navegador que la soporte.
