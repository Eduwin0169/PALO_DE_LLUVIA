# Palo de Lluvia

Sitio estático en HTML, CSS y JavaScript, preparado para publicarse en GitHub Pages y administrar contenido con [Pages CMS](https://pagescms.org/).

## Publicar en GitHub Pages

1. Sube el contenido de esta carpeta a la rama principal de un repositorio de GitHub.
2. En el repositorio, abre **Settings → Pages** y configura la publicación desde la rama principal y la carpeta raíz (`/(root)`).
3. Espera a que GitHub Pages publique el sitio. `index.html` abre la página principal, que también está disponible como `palo_de_lluvia.html`.

## Abrir el panel de contenido

1. Inicia sesión en [Pages CMS](https://pagescms.org/) con la cuenta de GitHub que tenga acceso al repositorio.
2. Selecciona el repositorio y la rama que publica el sitio. Pages CMS lee `.pages.yml` y muestra las secciones editables.
3. Administra los ajustes, canciones, noticias, galería y equipo desde el panel. Guarda los cambios para que se escriban en el repositorio y GitHub Pages vuelva a publicar el sitio.

El CMS edita los archivos del repositorio directamente; no requiere una base de datos ni un servidor adicional. La cuenta de GitHub debe tener permiso para editar el repositorio.

## Contenido y reproducción

- Los datos del sitio están en `content/` y sus campos se definen en `.pages.yml`.
- Las imágenes que se suben desde el CMS se guardan en `media/`.
- Para publicar una canción, añade el artista, país, género y un enlace válido de YouTube. El reproductor se carga dentro de la ficha y muestra los controles estándar de YouTube; algunos videos pueden tener la inserción desactivada por su propietario.
- El buscador y el filtro de género recorren el catálogo curado que Palo de Lluvia añade desde el panel. No son una búsqueda global de YouTube.
- Las publicaciones de Instagram necesitan un enlace público a un post, reel o video. La vista previa depende de que Instagram permita su inserción y conexión.
- Añade las URL reales de los perfiles sociales en **Ajustes del sitio** para convertir los iconos en enlaces. Hasta entonces se muestra el identificador `@palo_de_lluvia`.
- El logo se puede subir desde **Ajustes del sitio**; mientras no haya uno configurado, el espacio queda reservado.

No se incluyeron artistas, publicaciones, fotos, cuentas o enlaces inventados. Completa esos datos desde Pages CMS cuando estén disponibles.
