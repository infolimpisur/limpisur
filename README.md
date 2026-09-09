# Limpisur

Landing page estática para la marca Limpisur, pensada para distribución de productos de limpieza profesional en Sevilla.

## Estructura

La web se sirve como un sitio estático sin dependencias:

- `index.html` contiene el contenido HTML, CSS inline y la estructura completa de la página.
- `favicon.ico`, `favicon-32.png` y `icon-192.png` son assets de branding.

## Subir a GitHub

1. Crear un repositorio en GitHub.
2. Inicializar git en la carpeta local:

```bash
git init
git add .
git commit -m "Primer lanzamiento de la landing page"
git branch -M main
git remote add origin https://github.com/<usuario>/<repositorio>.git
git push -u origin main
```

3. Activar GitHub Pages desde la configuración del repositorio usando la rama `main` o la carpeta `/root`.

## GitHub Pages

Como es una página estática, el sitio puede publicarse directamente en GitHub Pages sin construir un proyecto JavaScript o npm.
