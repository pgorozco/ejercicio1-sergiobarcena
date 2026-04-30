# Plantillas para publicar proyectos de visualización

Estas plantillas son puntos de partida. La idea no es llenarlas como un formulario, sino usarlas para tomar decisiones de publicación: qué entra primero, qué necesita contexto, qué parte se explora, qué parte se argumenta y qué debe recordar la persona lectora al salir.

## Cómo usarlas

Este directorio funciona como una biblioteca de plantillas. Para trabajar en un proyecto propio, lo más claro es crear un repositorio nuevo y copiar allí el contenido de la plantilla elegida.

La guía completa para descargar plantillas, crear un repositorio propio y publicar con GitHub Pages está en [flujo-de-trabajo.md](../flujo-de-trabajo.md).

### Paso a paso

1. Elige la plantilla que mejor se ajuste a tu proyecto.
2. Crea un repositorio nuevo en GitHub Desktop. Ese será el repositorio de tu proyecto.
3. Copia los archivos que están dentro de la plantilla elegida.
4. Pégalos en la raíz del repositorio nuevo, de forma que `index.html` quede directamente dentro de la carpeta principal del proyecto.
5. Abre esa carpeta nueva en Visual Studio Code.
6. Abre `index.html` con Live Server para revisar la página.
7. Cambia los textos de ejemplo por el problema, los datos, las preguntas y los hallazgos de tu investigación.
8. Reemplaza los enlaces de visualizaciones de Observable, imágenes o archivos de datos.
9. Sube el proyecto a GitHub y publícalo con GitHub Pages desde la rama `main` y la carpeta `/root`.

La estructura recomendada para publicar en GitHub Pages es esta:

```text
mi-proyecto/
  index.html
  style.css
  script.js
  datos.csv
```

No todas las plantillas tienen todos esos archivos. Algunas solo tienen `index.html` y `style.css`.

## Qué archivo se edita

- `index.html`: cambia textos, títulos, estructura, enlaces, créditos e iframes.
- `style.css`: cambia colores, tamaños, espaciados, tipografías y distribución.
- `script.js`: cambia datos de ejemplo, filtros, interacciones y comportamiento dinámico.
- `datos.csv`: cambia datos tabulares. Evita usar comas dentro de una celda de texto.
- `datos.json`: cambia datos estructurados cuando necesites más detalle que una tabla simple.

## Plantillas incluidas

### 01 - Sitio estático con iframe

Para la semana 2. Sirve cuando ya existe una visualización en Observable y el objetivo es aprender a envolverla en una página web propia con título, contexto, créditos y una estructura básica.

### 02 - Artículo narrativo

Para la semana 3 y la semana 6. Sirve para proyectos que necesitan construir un argumento: presentar el tema, situar los datos, llevar a la persona lectora por varios hallazgos y cerrar con una interpretación.

### 03 - Datos locales

Para la semana 4. Sirve para practicar el paso de datos a componentes dentro de una página. Incluye un CSV y un JSON de ejemplo, más una pequeña visualización hecha con HTML, CSS y JavaScript.

Importante: esta plantilla debe revisarse con Live Server para que el navegador pueda cargar `datos.csv`.

### 04 - Componentes dinámicos

Para la semana 5. Sirve para proyectos donde la persona lectora debe filtrar, comparar o elegir vistas. Incluye controles, estados vacíos y actualización de contenido con JavaScript.

### 05 - Paralaje narrativo

Para proyectos inspirados en formatos de scrollytelling, donde el desplazamiento de la página activa cambios visuales. Sirve para presentar capas, contrastes, cambios temporales o acercamientos progresivos al detalle.

### 06 - Desplazamiento horizontal

Para proyectos que funcionan como recorrido lateral: líneas de tiempo, rutas, secuencias de decisiones, comparaciones por territorio o series de casos. El scroll vertical mueve una pista horizontal de paneles narrativos.

## Criterios de revisión

- La página tiene una pregunta o propósito claro.
- Las visualizaciones no aparecen solas: tienen contexto antes y lectura después.
- La estructura visual ayuda a jerarquizar, no solo a decorar.
- Los datos tienen fuente y fecha.
- El cierre deja una idea, una decisión o una tensión abierta.
