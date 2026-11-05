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

## Publicar en GitHub Pages

Repositorio: https://github.com/DanyCabrera/mywebsitedanycabrera

Dirección del sitio después de activar Pages: https://danycabrera.github.io/mywebsitedanycabrera/

1. Abre **Settings → Pages** en el repositorio.
2. En **Build and deployment → Source**, selecciona **Deploy from a branch**.
3. Selecciona la rama **main** y la carpeta **/ (root)**, y pulsa **Save**.
4. Espera a que termine **pages build and deployment** en la pestaña **Actions**.

Los siguientes cambios publicados en `main` actualizarán automáticamente el sitio. No necesitas Node.js, npm ni un comando de compilación.

Mantén `index.html`, `index.css`, `index.js`, `.nojekyll` y la carpeta `assets` en la raíz. Las rutas relativas funcionan dentro de `/mywebsitedanycabrera/`. El archivo `.nojekyll` indica que el contenido debe servirse como archivos estáticos, sin procesamiento de Jekyll.

Si ves una versión anterior después de completar el despliegue, recarga con **Ctrl + F5**. Si aparece un 404, revisa que Pages use `main` y `/ (root)`.

El contenido se actualizó a partir del CV facilitado en noviembre de 2026. Convention incluye enlaces a su aplicación y al repositorio. Los otros proyectos muestran detalles desplegables.
