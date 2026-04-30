# Flujo de trabajo recomendado

Este repositorio funciona como una biblioteca de plantillas del curso. No es necesario entregar el proyecto final dentro de este mismo repositorio. Para evitar confusiones con GitHub Pages, recomendamos que cada proyecto tenga su propio repositorio.

## 1. Obtener estas plantillas en el computador

Hay dos formas posibles:

1. Con GitHub Desktop: entra al repositorio del curso en GitHub, haz clic en **Code** y luego en **Open with GitHub Desktop**. GitHub Desktop descargará una copia local.
2. Con descarga directa: entra al repositorio del curso en GitHub, haz clic en **Code**, luego en **Download ZIP** y descomprime el archivo.

Después de este paso deberías tener una carpeta local con este contenido:

```text
enflujo-curso-vis-tec/
  README.md
  plantillas/
    01-sitio-estatico-iframe/
    02-articulo-narrativo/
    03-datos-locales/
    ...
```

## 2. Crear un repositorio nuevo para tu proyecto

En GitHub Desktop, crea un repositorio nuevo para tu proyecto. Por ejemplo:

```text
mi-proyecto-visualizacion/
```

Ese repositorio nuevo será el que vas a editar, subir y publicar. Este repo del curso queda como referencia.

## 3. Copiar una plantilla al repositorio nuevo

Elige una plantilla y copia su contenido, no solo la carpeta completa. Por ejemplo, si eliges `01-sitio-estatico-iframe`, copia los archivos que están adentro:

```text
plantillas/01-sitio-estatico-iframe/
  index.html
  style.css
```

Y pégalos en la raíz de tu repositorio nuevo:

```text
mi-proyecto-visualizacion/
  index.html
  style.css
```

La idea es que `index.html` quede directamente en la raíz del proyecto. Esto hace que GitHub Pages pueda publicar el sitio sin pasos extra.

## 4. Abrir el proyecto en Visual Studio Code

Abre la carpeta de tu proyecto, no la carpeta completa del curso:

```text
mi-proyecto-visualizacion/
```

Desde VS Code, abre `index.html` con Live Server. Esto es importante porque algunas plantillas cargan archivos locales, como `datos.csv`, y pueden fallar si se abren con doble clic desde el explorador de archivos.

## 5. Editar, guardar y revisar

Empieza por cambiar textos en `index.html`. Luego ajusta estilos en `style.css`. Si la plantilla tiene interacción, revisa también `script.js`.

Cada vez que guardes, vuelve al navegador y verifica:

- que la página cargue;
- que no haya textos de ejemplo sin reemplazar;
- que las visualizaciones se vean;
- que funcione en una ventana angosta, como celular;
- que estén la fuente de datos, la fecha y los créditos.

## 6. Subir el proyecto a GitHub

En GitHub Desktop:

1. Revisa los cambios.
2. Escribe un mensaje corto, por ejemplo `Primera versión del sitio`.
3. Haz clic en **Commit**.
4. Haz clic en **Publish repository** o **Push origin**.

## 7. Publicar con GitHub Pages

En GitHub, entra al repositorio de tu proyecto y ve a:

```text
Settings > Pages
```

En la sección **Build and deployment**:

1. En **Source**, elige **Deploy from a branch**.
2. En **Branch**, elige `main`.
3. En la carpeta, elige `/root`.
4. Guarda los cambios.

GitHub Pages funciona mejor si tu archivo `index.html` está en la raíz del repositorio. Por eso copiamos el contenido de la plantilla directamente dentro del proyecto.

Si decides usar la carpeta `/docs`, entonces `index.html` debe estar dentro de `docs/`. Para este curso, la opción recomendada es publicar desde `/root`.

## Qué archivo edito

- `index.html`: estructura, textos, títulos, enlaces, créditos e iframes.
- `style.css`: colores, tipografías, tamaños, márgenes y distribución visual.
- `script.js`: interacciones, filtros, cambios por scroll o lectura de datos.
- `datos.csv`: datos tabulares simples. Es útil para empezar, pero evita poner comas dentro de las celdas de texto.
- `datos.json`: datos estructurados. Es útil cuando necesitas listas, categorías o información más compleja.

## Problemas comunes

- La página no carga datos: abre el proyecto con Live Server, no con doble clic.
- La visualización de Observable no aparece: revisa que el cuaderno esté publicado o compartido, y que la celda tenga nombre.
- GitHub Pages muestra una página vacía o un error: revisa que `index.html` esté en la raíz del repositorio si publicaste desde `/root`.
- Los cambios no aparecen en la web publicada: espera unos minutos, recarga con fuerza el navegador o revisa si hiciste **Push** desde GitHub Desktop.
- La galería del README se daña al guardar: este proyecto desactiva el formato automático para Markdown en `.vscode/settings.json`.
