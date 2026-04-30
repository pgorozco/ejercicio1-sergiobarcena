# Curso de visualización de datos - TEC - Uniandes

En este segundo módulo del curso vamos a desarrollar dos habilidades fundamentales:

1. Reconocer y usar el ecosistema de publicación abierto y gratuito. Con esto, quiero dejarles unos insumos para que puedan desarrollar y publicar proyectos de visualización de datos, u otros proyectos similares de publicación digital, de forma profesional, sostenible y accesible.
2. Desarrollar una publicación para internet que narre los datos. En el primer módulo desarrollaron habilidades de visualización; ahora vamos a pensar en las formas como esas visualizaciones se articulan en narrativas persuasivas, elocuentes y útiles para que sus públicos objetivo puedan sacarle el mayor provecho al trabajo.

## Instrucciones básicas

Antes de empezar, cada estudiante debe preparar estas herramientas:

1. Instalar [Visual Studio Code](https://code.visualstudio.com/). Este será el editor principal para abrir, modificar y revisar los archivos HTML, CSS y JavaScript del curso.
2. Instalar la extensión [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) en Visual Studio Code. Live Server no viene instalado por defecto; es una extensión que permite abrir una página local en el navegador y ver los cambios al guardar.
3. Crear una cuenta gratuita en [GitHub](https://github.com/). La usaremos para guardar los proyectos y publicarlos como sitios web gratuitos con GitHub Pages.
4. Instalar [GitHub Desktop](https://desktop.github.com/). Esta aplicación facilita descargar repositorios, guardar cambios y subirlos a GitHub sin usar la terminal.

## Flujo de trabajo

Este repositorio funciona como una biblioteca de plantillas del curso. Para evitar confusiones con GitHub Pages, lo recomendado es crear un repositorio nuevo por cada proyecto y copiar allí el contenido de la plantilla elegida.

La guía completa está en [flujo-de-trabajo.md](flujo-de-trabajo.md).

## Plantillas

Las plantillas están en la carpeta [plantillas](plantillas/README.md). Están pensadas como puntos de partida para pasar de una visualización aislada a una publicación web con estructura narrativa.

- [01 - Sitio estático con iframe](plantillas/01-sitio-estatico-iframe/index.html): estructura mínima para publicar una visualización de Observable dentro de una página HTML.
- [02 - Artículo narrativo](plantillas/02-articulo-narrativo/index.html): página larga para combinar contexto, visualizaciones, hallazgos y cierre argumental.
- [03 - Datos locales](plantillas/03-datos-locales/index.html): ejemplo para cargar datos desde CSV/JSON y convertirlos en componentes de una página.
- [04 - Componentes dinámicos](plantillas/04-componentes-dinamicos/index.html): interfaz con filtros y estados para proyectos que necesitan exploración.
- [05 - Paralaje narrativo](plantillas/05-paralaje-narrativo/index.html): relato tipo scrollytelling donde el desplazamiento activa escenas, capas visuales y comparaciones.
- [06 - Desplazamiento horizontal](plantillas/06-desplazamiento-horizontal/index.html): relato en paneles laterales donde el scroll vertical mueve una secuencia horizontal.

## Cronograma

### Semana 1 - 15 abril

Introducción: mostrar, visualizar, narrar. Del efecto al afecto.

### Semana 2 - 22 abril

Taller de publicación: el sitio estático más allá de lo básico. Estructura de HTML e inserción de visualizaciones usando iframe.

### Semana 3 - 29 abril

Componentes: narrativa y flujo de elementos en la pantalla. Estructura de HTML y diseño básico en CSS.

### Semana 4 - 6 mayo

Conectar nuestro sitio con fuentes de datos tanto estáticas como dinámicas: JSON, CSV, Baserow, CMS.

### Semana 5 - 13 mayo

Componentes dinámicos: JavaScript.

### Semana 6 - 20 mayo

Narrativas en pantalla: pasar de la presentación bonita al argumento persuasivo.

### Semana 7 - 27 mayo

Trabajo en clase sobre los proyectos, oportunidad para resolver dudas y ver adelantos.

### Semana 8 - 3 junio

Presentaciones finales.

## Ejemplos

Estos referentes muestran distintas formas de narrar, explorar y publicar información en internet.

<!-- prettier-ignore-start -->

<table>
  <tr>
    <td width="33%" valign="top"><a href="https://heartsandminds.odi.digital/"><img src="https://heartsandminds.odi.digital/assets/images/thumb.jpg" alt="Vista previa de Hearts and Minds" width="260"></a><br><strong><a href="https://heartsandminds.odi.digital/">Hearts and Minds</a></strong><br><sub>Narrativa visual interactiva</sub></td>
    <td width="33%" valign="top"><a href="https://www.why-expensive.com/"><img src="https://why-expensive.com/share.png" alt="Vista previa de Why Expensive" width="260"></a><br><strong><a href="https://www.why-expensive.com/">Why Expensive?</a></strong><br><sub>Explicación interactiva</sub></td>
    <td width="33%" valign="top"><a href="https://neal.fun/deep-sea/"><img src="https://neal.fun/share-cards/deep-sea.png" alt="Vista previa de scroll" width="260"></a><br><strong><a href="https://neal.fun/deep-sea/">The Deep Sea</a></strong><br><sub>Scroll vertical exploratorio</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://histography.io/"><img src="http://histography.io/histography.jpg" alt="Vista previa de Histography" width="260"></a><br><strong><a href="https://histography.io/">Histography</a></strong><br><sub>Línea de tiempo interactiva</sub></td>
    <td width="33%" valign="top"><a href="https://cerosetenta.uniandes.edu.co/especiales/siete-horas/"><img src="https://cerosetenta.uniandes.edu.co/especiales/siete-horas/imgs/siete-horas.png" alt="Vista previa de Siete horas" width="260"></a><br><strong><a href="https://cerosetenta.uniandes.edu.co/especiales/siete-horas/">Siete horas</a></strong><br><sub>Especial narrativo</sub></td>
    <td width="33%" valign="top"><a href="https://cerosetenta.uniandes.edu.co/especiales/veinticuatro-siete/"><img src="https://api.enflujo.com/assets/c74b66f6-1f61-44cc-a2c9-89f32c631a4c?width=667&height=350&quality=90&format=webp" alt="Vista previa de Veinticuatro siete" width="260"></a><br><strong><a href="https://cerosetenta.uniandes.edu.co/especiales/veinticuatro-siete/">Veinticuatro siete</a></strong><br><sub>Narrativa horizontal</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://pudding.cool/2023/07/songwriters/"><img src="https://pudding.cool/2023/07/songwriters/assets/facebook.jpg" alt="Vista previa de Songwriters" width="260"></a><br><strong><a href="https://pudding.cool/2023/07/songwriters/">Songwriters</a></strong><br><sub>Análisis cultural con datos</sub></td>
    <td width="33%" valign="top"><a href="https://pudding.cool/2024/03/greatest-music/"><img src="https://pudding.cool/2024/03/greatest-music/assets/social-facebook.jpg" alt="Vista previa de Greatest Music" width="260"></a><br><strong><a href="https://pudding.cool/2024/03/greatest-music/">Greatest Music</a></strong><br><sub>Visualización editorial</sub></td>
    <td width="33%" valign="top"><a href="https://pudding.cool/2024/03/teenagers/"><img src="https://pudding.cool/2024/03/teenagers/assets/social-facebook.jpg" alt="Vista previa de Teenagers" width="260"></a><br><strong><a href="https://pudding.cool/2024/03/teenagers/">Teenagers</a></strong><br><sub>Historia guiada por scroll</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://pudding.cool/2022/11/upward-mobility/"><img src="https://pudding.cool/2022/11/upward-mobility/assets/social-facebook.jpg" alt="Vista previa de Upward Mobility" width="260"></a><br><strong><a href="https://pudding.cool/2022/11/upward-mobility/">Upward Mobility</a></strong><br><sub>Exploración social con datos</sub></td>
    <td width="33%" valign="top"><a href="https://pudding.cool/2017/03/hamilton/index.html"><img src="https://pudding.cool/2017/03/hamilton/meta.png" alt="Vista previa de Hamilton" width="260"></a><br><strong><a href="https://pudding.cool/2017/03/hamilton/index.html">Hamilton</a></strong><br><sub>Análisis visual de texto</sub></td>
    <td width="33%" valign="top"><a href="http://www.storiesbehindaline.com/"><img src="http://www.storiesbehindaline.com/assets/social/share.jpg" alt="Vista previa de Stories Behind a Line" width="260"></a><br><strong><a href="http://www.storiesbehindaline.com/">Stories Behind a Line</a></strong><br><sub>Dibujo, memoria y recorrido</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://moebio.com/research/rayuela/"><img src="https://edgargonzalez.com/wp-content/uploads/2013/07/moebio_rayuela_02.jpg" alt="Vista previa de Rayuela" width="260"></a><br><strong><a href="https://moebio.com/research/rayuela/">Rayuela</a></strong><br><sub>Exploración literaria</sub></td>
    <td width="33%" valign="top"><a href="https://moebio.com/iliad/"><img src="https://moebio.com/iliad/resources/iliad_wordsBIG.png" alt="Vista previa de Iliad" width="260"></a><br><strong><a href="https://moebio.com/iliad/">Iliad</a></strong><br><sub>Visualización textual</sub></td>
    <td width="33%" valign="top"><a href="https://selfiecity.net/selfiexploratory/"><img src="https://selfiecity.net/selfiexploratory/assets/tour/chartinteraction.png" alt="Vista previa de Selfiexploratory" width="260"></a><br><strong><a href="https://selfiecity.net/selfiexploratory/">Selfiexploratory</a></strong><br><sub>Interfaz de exploración</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://parametric.press/issue-02/carbon-history/"><img src="https://parametric.press/issue-02/carbon-history/static/images/share.png" alt="Vista previa de Carbon History" width="260"></a><br><strong><a href="https://parametric.press/issue-02/carbon-history/">Carbon History</a></strong><br><sub>Ensayo interactivo</sub></td>
    <td width="33%" valign="top"><a href="https://therefugeeproject.org/"><img src="https://therefugeeproject.org/TRP-Share.jpg" alt="Vista previa de The Refugee Project" width="260"></a><br><strong><a href="https://therefugeeproject.org/">The Refugee Project</a></strong><br><sub>Mapa y datos históricos</sub></td>
    <td width="33%" valign="top"><a href="https://blueheart.patagonia.com/truth/"><img src="http://blueheart.patagonia.com/static/images/social/share.png" alt="Vista previa de Blue Heart" width="260"></a><br><strong><a href="https://blueheart.patagonia.com/truth/">Blue Heart</a></strong><br><sub>Especial ambiental</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://laciudadcomotexto.cl/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0Zb1UhZsX82iUGJP8Oh3So6Ik05tmeC6BqQ&s" alt="Vista previa de mapa" width="260"></a><br><strong><a href="https://laciudadcomotexto.cl/">La ciudad como texto</a></strong><br><sub>Archivo urbano interactivo</sub></td>
    <td width="33%" valign="top"><a href="https://www.sbs.com.au/theboat/"><img src="http://www.sbs.com.au/theboat/images/fb-image.jpg" alt="Vista previa de The Boat" width="260"></a><br><strong><a href="https://www.sbs.com.au/theboat/">The Boat</a></strong><br><sub>Relato inmersivo</sub></td>
    <td width="33%" valign="top"><a href="https://arte.estadao.com.br/brasil/adocao/criancas/"><img src="https://arte.estadao.com.br/brasil/adocao/criancas/media/images/share/1200x1200.png?v=0.2.25" alt="Vista previa de Crianças" width="260"></a><br><strong><a href="https://arte.estadao.com.br/brasil/adocao/criancas/">Crianças</a></strong><br><sub>Periodismo de datos</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://pasadoimpreso.uniandes.edu.co/mujeres-de-prensa"><img src="http://pasadoimpreso.uniandes.edu.co/uploads/attachments/cjl9sulez00idmn1xgg69slkh-mujeres-de-prensa.full.jpg" alt="Vista previa de Mujeres de prensa" width="260"></a><br><strong><a href="https://pasadoimpreso.uniandes.edu.co/mujeres-de-prensa">Mujeres de prensa</a></strong><br><sub>Archivo y narrativa histórica</sub></td>
    <td width="33%" valign="top"><a href="https://historiasinternet.uniandes.edu.co/"><img src="https://historiasinternet.uniandes.edu.co//portada_historia_internet.jpg" alt="Vista previa de Historias de internet" width="260"></a><br><strong><a href="https://historiasinternet.uniandes.edu.co/">Historias de internet</a></strong><br><sub>Narrativa web</sub></td>
    <td width="33%" valign="top"><a href="https://haciendocaminos.uniandes.edu.co/"><img src="http://haciendocaminos.uniandes.edu.co//imagen_OG.png" alt="Vista previa de Haciendo caminos" width="260"></a><br><strong><a href="https://haciendocaminos.uniandes.edu.co/">Haciendo caminos</a></strong><br><sub>Proyecto interactivo</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://intuitionanalytics.com/other/knowledgeDatabase/#i=1024"><img src="http://moebio.com/research/knowledgeDatabase/resources/knowledge.png" alt="Vista previa de Knowledge Database" width="260"></a><br><strong><a href="https://intuitionanalytics.com/other/knowledgeDatabase/#i=1024">Knowledge Database</a></strong><br><sub>Mapa de conocimiento</sub></td>
    <td width="33%" valign="top"><a href="https://enflujo.com/proyectos/"><img src="https://enflujo.com//imgs/og-EnFlujo-predeterminado.jpg" alt="Vista previa de proyectos de EnFlujo" width="260"></a><br><strong><a href="https://enflujo.com/proyectos/">Proyectos de EnFlujo</a></strong><br><sub>Portafolio de proyectos digitales</sub></td>
    <td width="33%" valign="top"><a href="https://www.dddrawings.com/lab/"><img src="https://dddrawings.com/estaticos/defunciones.D-gt_fNX_2gdGoG.jpeg" alt="Vista previa de dddrawings lab" width="260"></a><br><strong><a href="https://www.dddrawings.com/lab/">dddrawings lab</a></strong><br><sub>Experimentos de visualización de datos y animación</sub></td>
  </tr>
</table>
<!-- prettier-ignore-end -->
