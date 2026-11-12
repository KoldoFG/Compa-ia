# Compañía · visor 3D

Visor web de la propuesta de reforma de cocina y aseo (modelo `261102_base.3dm`).

## Contenido

| Archivo | Qué es |
|---|---|
| `index.html` | El visor (three.js r170 desde jsDelivr) |
| `modelo.glb` | Modelo 3D exportado desde Rhino |
| `.nojekyll` | Hace que GitHub Pages sirva los archivos tal cual |

## Publicar con GitHub Pages

1. En GitHub, crea un repositorio nuevo (por ejemplo `compania-visor`).
2. Pulsa **Add file → Upload files** y arrastra **todos** los archivos de esta carpeta (incluido `.nojekyll`). Pulsa **Commit changes**.
3. Ve a **Settings → Pages**. En *Build and deployment* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. En uno o dos minutos la web estará en `https://<tu-usuario>.github.io/compania-visor/`.

Con una cuenta gratuita, GitHub Pages solo funciona con repositorios **públicos**: cualquiera que tenga el enlace podrá ver el modelo.

## Actualizar el modelo

Sustituye `modelo.glb` (e `index.html` si cambia) subiendo los archivos nuevos al repositorio. La web se actualiza sola.

## Notas

- Para probarlo en local hay que servir la carpeta (por ejemplo `python -m http.server`) y abrir `http://localhost:8000`. Al abrir `index.html` con doble clic, el navegador bloquea la carga de `modelo.glb`.
- Las notas compartidas solo funcionan en la versión publicada en Claude. Aquí no aparecen.
- Las mediciones y el presupuesto están ocultos de momento.
