# Geolocalización

Proyecto sencillo en HTML, CSS y JavaScript para obtener la ubicación actual del usuario con la API de geolocalización del navegador.

## Cómo abrirlo

1. Abre la carpeta del proyecto.
2. Ejecuta un servidor local, por ejemplo:
   ```bash
   python -m http.server 8000
   ```
3. En el navegador visita:
   ```text
   http://localhost:8000
   ```

## Funcionalidad

- Solicita acceso a la ubicación del usuario.
- Muestra latitud, longitud, precisión y hora.
- Genera un enlace para ver la posición en Google Maps.

## Nota

La geolocalización solo funciona con permiso del usuario y desde un navegador que la soporte.
