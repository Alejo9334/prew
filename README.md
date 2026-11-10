# prew — Copia independiente del visor y editor AR

Repositorio independiente con una copia del **visor y editor de ANTÁRTIDA STUDIO**, su catálogo, capas PNG/WebP, referencias y archivo `targets.mind`.

## Enlaces (después de activar GitHub Pages)
- Visor: https://alejo9334.github.io/prew/
- Editor: https://alejo9334.github.io/prew/editor.html
- Optimizador: https://alejo9334.github.io/prew/optimizar.html

## Activación
1. **Settings → Pages → Build and deployment → Source → GitHub Actions**
2. **Actions → Instalar copia independiente AR en prew → Run workflow**.
3. Comprueba desde el teléfono el permiso de cámara, el reconocimiento de imágenes y los movimientos.

El workflow copia los archivos de ANTÁRTIDA **solo la primera vez**, los guarda en `prew/public/` y publica exclusivamente el contenido local de `prew`. Los cambios futuros de ANTÁRTIDA o Code-fuente **no actualizan** esta copia de forma automática.

## Notas
- Es una réplica inicial con el tema **ANTÁRTIDA** y los cuadros de demostración Minecraft y Carnet.
- El editor conserva las herramientas de capas y los efectos de realidad aumentada, pero **no tiene autenticación independiente**; no compartas el enlace de edición públicamente.
- Las experiencias se editan en el navegador y se exportan como JSON. Para publicar experiencias nuevas necesitas actualizar el catálogo en este repositorio.
