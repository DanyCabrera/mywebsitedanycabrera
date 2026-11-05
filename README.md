# Portafolio de Dany Cabrera

Sitio estático en HTML, CSS y JavaScript, sin frameworks ni proceso de compilación.

## Abrir localmente

Abre `index.html` en un navegador. Para probar todas las funciones, incluida la copia al portapapeles, inicia un servidor local desde esta carpeta:

```sh
python -m http.server 5500 --bind 127.0.0.1
```

Después visita http://127.0.0.1:5500.

## Archivos

- `index.html`: contenido, proyectos y trayectoria.
- `index.css`: diseño y adaptación a pantallas pequeñas.
- `index.js`: navegación móvil, sección activa y copia de correo.
- `assets/`: fotografía, capturas reales y favicon.

Las fuentes DM Sans y Manrope se cargan desde Google Fonts. Si no hay conexión, el sitio utiliza las fuentes del sistema. El contenido y las imágenes están disponibles localmente.

## Publicar

Sube `index.html`, `index.css`, `index.js` y la carpeta `assets` a la raíz del alojamiento estático. Las rutas relativas son compatibles con GitHub Pages y su subdirectorio `/Portafolio/`.

El contenido se actualizó a partir del CV facilitado en noviembre de 2026. Convention incluye enlaces a su aplicación y al repositorio. Los otros proyectos muestran detalles desplegables.
