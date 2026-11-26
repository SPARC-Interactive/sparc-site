# SPARC Interactive · sitio web

Sitio oficial de SPARC Interactive: https://sparc-interactive.com

Es una página estática (HTML, CSS y JavaScript en `index.html`), publicada con GitHub Pages desde la rama `main`.

## Estructura

| Ruta | Qué es |
|---|---|
| `index.html` | La página completa |
| `404.html` | Página que se muestra cuando un enlace no existe |
| `assets/logo`, `assets/logo-v2` | Logo, favicon |
| `assets/proyectos` | Portadas (`.webp`) y videos (`clips/*.mp4`) del portafolio |
| `assets/og-sparc.jpg` | Imagen que aparece al compartir el enlace |
| `CNAME` | Dominio propio (sparc-interactive.com). **No borrar**: sin él la web deja de verse en el dominio |
| `robots.txt`, `sitemap.xml` | Para que Google encuentre la página |

## Cómo actualizar

1. Edita los archivos y súbelos a la rama `main`.
2. GitHub Pages publica los cambios solo, en uno o dos minutos.

Los proyectos del portafolio están en `index.html`, en la lista `PROYECTOS`. Cada uno usa `assets/proyectos/<id>.webp` y `assets/proyectos/clips/<id>.mp4`.
