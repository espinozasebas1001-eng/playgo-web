# PLAYGO — El Nuevo Rico, El Nuevo Pobre

Sitio estático completo de presentación del juego.

## Abrir
Abrí `index.html` en tu navegador o usá Live Server en VS Code. No requiere instalación ni compilación. Para GSAP y Google Fonts se necesita internet; el sitio funciona sin esos recursos.

## Publicar en GitHub Pages
Subí **el contenido de esta carpeta** a un repositorio público. En Settings > Pages elegí Deploy from a branch, rama `main`, carpeta `/ (root)`. Esperá a que aparezca la URL publicada.

## Archivos
- `index.html`: secciones y reglamento completo del documento recibido.
- `css/style.css`: estilos listos para publicar.
- `js/main.js`: menú, animaciones, dados, cartas y ampliación de imágenes.
- `assets/`: tablero, fotografías y láminas de tarjetas extraídas de los PDF originales.

Las cartas aleatorias son una selección demostrativa del material recibido; la galería contiene las láminas completas. El sitio no vende el producto ni permite partidas online.

**Nota:** el reglamento se incorpora a partir del documento proporcionado. Revisar su redacción final con el equipo antes de publicarlo.

## Optimización y publicación
- El tablero se presenta en WebP optimizado (se conserva el PNG original como archivo fuente).
- Se añadieron metadatos sociales, atributos de accesibilidad, carga diferida y archivo `.nojekyll`.
- Para publicar, subí los archivos de `playgo-web/` a la **raíz** del repositorio, no la carpeta contenedora.
- GitHub → Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
- Antes de difundir el enlace, revisá el sitio en Chrome, Firefox, Safari y en un celular real. Estas pruebas visuales no se ejecutaron automáticamente.
- El dominio público no está definido: no se agregó una URL canónica ni sitemap con direcciones inventadas.
