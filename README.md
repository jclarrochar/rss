# Proyecto RSS en GitHub Pages

Este proyecto consiste en la creación de una galería multimedia con una estructura HTML alojada en GitHub Pages, junto con un feed RSS para permitir la suscripción a las actualizaciones.

## Estructura del Proyecto

El repositorio contiene los siguientes archivos:

 rss/ index.html # Página principal, videos.html # Sección de vídeos, podcasts.html # Sección de podcasts, rss.xml # Archivo RSS con los enlaces a las páginas README.md # Documentación del proyecto.
 
El sitio web está disponible en la siguiente dirección:

**[https://jclarrochar.github.io/rss/](https://jclarrochar.github.io/rss/)**

## Creación del Feed RSS

El archivo `rss.xml` permite que los usuarios reciban actualizaciones sobre los contenidos de la galería multimedia. Contiene una estructura estándar con un `<channel>` que agrupa varias secciones (`index.html`, `videos.html`, `podcasts.html`), cada una representada con un `<item>` que incluye su título, enlace, descripción y fecha de publicación.

El feed RSS se puede consultar en:

**[https://jclarrochar.github.io/rss/rss.xml](https://jclarrochar.github.io/rss/rss.xml)**

## Pasos Realizados

1. Se crearon las páginas HTML (`index.html`, `videos.html`, `podcasts.html`).
2. Se configuró un repositorio en GitHub y se subieron los archivos.
3. Se activó GitHub Pages para que el sitio web fuera accesible en línea.
4. Se creó el archivo `rss.xml` con los enlaces a las páginas.
5. Se verificó el RSS con un validador y lectores RSS.
6. Se documentó el proyecto con este `README.md`.

## Validación del RSS

Para comprobar que el feed RSS funciona correctamente:
- Se puede validar en [W3C Feed Validator](https://validator.w3.org/feed/)
- Se puede agregar en un lector RSS como Feedly o Inoreader.

## Actualización del RSS

Cada vez que se agregue contenido nuevo, se debe editar `rss.xml`, subirlo al repositorio y GitHub Pages lo actualizará automáticamente.
