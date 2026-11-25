# Web Abogada Rebeca Girotti

Sitio institucional del estudio de la Dra. Rebeca Girotti en Chivilcoy. [Visitar la web](https://www.abogadarebecagirotti.com.ar/).

La página principal presenta el perfil profesional, las áreas de práctica y los canales de contacto. El sitio usa HTML, CSS y JavaScript estáticos. Las consultas se coordinan mediante enlaces externos.

## Desarrollo local

Desde la raíz del repositorio, ejecutá `python -m http.server 8080` y abrí `http://localhost:8080`.

Para verificar el sitio con Node.js 20 o superior:

```sh
node --check js/main.js
node --test tests/check-site.mjs
```

## Publicación

GitHub Pages publica la raíz de la rama `master`. El archivo `CNAME` define el dominio. Conservá los archivos de verificación de Google y Bing y los recursos referenciados desde `site.webmanifest` y `browserconfig.xml`.

La página principal está en `index.html`, la política de privacidad en `privacidad.html` y la página de error en `404.html`. La imagen que se muestra al compartir el sitio está en `assets/images/og-image.png`.
