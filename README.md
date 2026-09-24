# Sebastián Villafuerte Rojas

Web estática bilingüe: textos seleccionados, perfiles de autor y contacto. Sin instalaciones, dependencias, fuentes externas, analítica ni JavaScript.

## Abrir

Abre `index.html` en un navegador. El selector EN/ES enlaza con `es.html`; funciona también sin conexión. Las publicaciones y redes necesitan Internet.

## Publicar en GitHub Pages

1. Copia **el contenido** de esta carpeta (no la carpeta contenedora) a la raíz de tu repositorio `sebastianvr888.github.io`. Conserva una copia de los archivos anteriores si quieres poder recuperarlos.
2. Guarda los cambios en la rama que utilices para publicar.
3. En el repositorio, abre **Settings → Pages**, selecciona **Deploy from a branch**, elige esa rama y la carpeta **/(root)**, y guarda.
4. Cuando GitHub termine de publicar, visita `https://sebastianvr888.github.io/`. La edición española estará en `https://sebastianvr888.github.io/es.html`.

También funciona dentro de un repositorio de proyecto: todos los enlaces internos son relativos. No necesita un proceso de compilación. La publicación no se ha realizado automáticamente.

## Editar

- `index.html`: versión inglesa.
- `es.html`: versión española.
- `styles.css`: estilos compartidos; los colores están al principio.
- `favicon.svg`: icono de la pestaña.
- `.nojekyll`: permite servir los archivos directamente con GitHub Pages.

Para añadir una publicación, copia un `<li>` dentro de `<ul class="works">` en **ambos HTML**. Cambia título, enlace, tema, medio, idioma y símbolo del medio. Conserva `lang` en el título y `hreflang` en el enlace de acuerdo con el idioma del artículo original. Los títulos se mantienen en su idioma de publicación para no sugerir traducciones que no existen.

El correo, LinkedIn, X y los enlaces de medios se tomaron de la web de referencia. Si deseas usar otro correo profesional, cambia tanto el texto como `mailto:` en los dos HTML.

## Contenido y fuentes

Referencia visual y enlaces profesionales: https://sebastianvr888.github.io/

Diseño negro con tipografía sans serif moderna, nombre de gran formato con «Sebastián» en morado y descriptor monoespaciado «Analista / Escritor / Creativo» (en inglés, «Analyst / Writer / Creative»). Los símbolos de cada publicación utilizan azul (El Nacional), naranja (Substack), verde (NewsBTC), amarillo (Bitcoinist) y morado (X / Aerodrome). Cada medio tiene además un símbolo distinto y su nombre escrito. Los perfiles de El Nacional y Substack reemplazan la bio.

Los dos ensayos de Substack se verificaron en sus páginas originales:

- https://soysebastian888.substack.com/p/oswaldo-vigas-y-la-raiz-de-una-figura (destino del enlace `p-208492592` compartido).
- https://soysebastian888.substack.com/p/un-mapa-inesperado-del-arte-cubano

La selección contiene ocho piezas. Cada edición muestra primero los textos de su propio idioma. Dentro de cada idioma se mantiene la prioridad editorial: El Nacional → X / Aerodrome → Substack → NewsBTC → Bitcoinist. Dentro de cada medio, las publicaciones van de más reciente a más antigua. Los tres textos de El Nacional se verificaron en el perfil de autor el 24 de septiembre de 2026: 17/09/2026, 07/09/2026 y 21/08/2026. Los ensayos de Substack son del 17/09/2026 y 20/08/2026. En los demás medios se conserva una pieza por medio de la selección anterior. La sección de perfiles enlaza a El Nacional y Substack. No se han añadido credenciales. Los destinos externos pueden cambiar o requerir acceso en sus respectivas plataformas.

## Accesibilidad

HTML semántico, jerarquía de encabezados, idioma por página y por título, enlace para saltar al contenido, navegación por teclado, foco visible, contraste alto, selector de idioma con estado actual y adaptación a pantallas pequeñas. Se respeta la preferencia de movimiento reducido. Los enlaces externos se abren en la misma pestaña, sin ventanas inesperadas.

Instrucciones de publicación contrastadas con la documentación oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
