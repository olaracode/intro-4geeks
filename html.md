# Introducción a HTML5

Indice

- [Qué es HTML](#qué-es-html)
- [Qué es HTML5](#qué-es-html5)
- [Qué es un elemento HTML](#qué-es-un-elemento-html)
- [Qué es una etiqueta HTML](#qué-es-una-etiqueta-html)
- [Qué es un atributo HTML](#qué-es-un-atributo-html)
- [Jerarquía en HTML](#jerarquía-en-html)
- [Qué es un elemento anidado](#qué-es-un-elemento-anidado)
- [Cómo funcionan las listas en HTML](#cómo-funcionan-las-listas-en-html)
- [Qué es una tabla en HTML](#qué-es-una-tabla-en-html)
- [Qué es un hipervínculo](#qué-es-un-hipervínculo)
- [Qué es un hipervínculo interno](#qué-es-un-hipervínculo-interno)
- [Qué es HTML semántico](#qué-es-html-semántico)
- [Tips para escribir HTML semántico](#tips-para-escribir-html-semántico)
- [Qué etiquetas son buenas para hacer HTML semántico](#qué-etiquetas-son-buenas-para-hacer-html-semántico)
- [Qué son las etiquetas meta](#qué-son-las-etiquetas-meta)
- [Qué son etiquetas de auto cierre](#qué-son-etiquetas-de-auto-cierre)
- [Qué son los formularios y qué etiquetas se usan](#qué-son-los-formularios-y-qué-etiquetas-se-usan)
- [Tips de HTML](#tips-de-html)

## Documentación

- [MDN oficial](https://developer.mozilla.org/es/docs/HTML/HTML5)
- [W3Schools](https://www.w3schools.com/html/default.asp)
- [HTML5 Doctor](http://html5doctor.com/)

## Qué es HTML

HTML es un lenguaje de marcado que se utiliza para el desarrollo de páginas de Internet. Se trata de la sigla que corresponde a HyperText Markup Language, es decir, Lenguaje de Marcas de Hipertexto.

Un lenguaje de marcado es un conjunto de etiquetas que se utilizan para marcar el comienzo y el final de cada elemento en un documento. El desarrollo de un sitio web se hace en base a un lenguaje de marcado que luego se traduce a la forma visual que vemos en el navegador.

## Historia de HTML

HTML fue creado en 1990 por Tim Berners-Lee. Desde entonces se han ido publicando diferentes versiones, siendo la última HTML5.

## Qué es HTML5

HTML5 es la última evolución de HTML, el estándar que sirve de referencia para la elaboración de páginas web. HTML5 es una nueva versión de HTML, con nuevos elementos, atributos y comportamientos, y un conjunto más amplio de tecnologías que permite a los sitios web y a las aplicaciones ser más diversas y de gran alcance. Este conjunto más amplio de tecnologías a veces se denomina HTML5 y amigos y a menudo se abrevia como HTML5.

## Qué es un elemento HTML

Un elemento HTML es un tipo de componente de un documento, que puede ser representado en la pantalla de una forma distinta a la del texto normal, como por ejemplo, un párrafo, una imagen o una tabla. Los elementos HTML son los bloques de construcción de las páginas HTML.

Un elemento HTML se define mediante una etiqueta HTML, tiene cero o más atributos y puede contener contenido.

Un elemento HTML es todo, desde la etiqueta de inicio hasta la etiqueta de finalización:

```html
<p>Este es un párrafo</p>
```

## Qué es una etiqueta HTML

Una etiqueta HTML es un nombre rodeado de corchetes angulares, como `<html>`, que se utiliza para marcar el comienzo o el final de un elemento. Las etiquetas HTML pueden rodear a palabras o imágenes para hacerlas hipervínculos a otras páginas web. Las etiquetas HTML básicas son las siguientes:

- `<html>`: Define un documento HTML
- `<head>`: Contiene información de encabezado del documento
- `<title>`: Define el título del documento
- `<body>`: Define el cuerpo del documento
- `<h1>`: Define un encabezado
- `<p>`: Define un párrafo
- `<br>`: Inserta un salto de línea
- `<hr>`: Define una ruptura temática
- `<a>`: Define un hipervínculo
- `<!--...-->`: Define un comentario

## Qué es un atributo HTML

Los atributos proporcionan información adicional sobre los elementos HTML. Los atributos siempre se especifican en la etiqueta de inicio y generalmente se presentan en pares nombre/valor, como por ejemplo: name="value".

Algunos ejemplos de atributos son:

- `href`: Especifica la URL (dirección web) de un enlace
- `src`: Especifica la URL (dirección web) de una imagen
- `width`: Especifica el ancho de una imagen
- `height`: Especifica la altura de una imagen
- `alt`: Proporciona un texto alternativo para una imagen
- `style`: Especifica un estilo CSS para un elemento
- `lang`: Especifica el idioma de un elemento
- `class`: Especifica una o más clases para un elemento (se refiere a la clase CSS con el mismo nombre)

## Jerarquía en HTML

Los elementos HTML pueden tener padres e hijos. Un elemento puede ser hijo de otro elemento y a su vez ser padre de otro elemento. Por ejemplo, el elemento `<body>` es hijo del elemento `<html>` y padre de los elementos `<h1>` y `<p>`.

```html
<html>
  <!-- Padre -->
  <body>
    <!-- Hijo de html | Padre -->
    <h1>Este es un encabezado</h1>
    <!-- Hijo -->
    <p>Este es un párrafo</p>
    <!-- Hijo -->
  </body>
</html>
```

## Qué es un elemento anidado

Un elemento anidado es un elemento que está dentro de otro elemento. Por ejemplo, el elemento `<p>` está anidado dentro del elemento `<body>`.

```html
<body>
  <p>Este es un párrafo</p>
</body>
```

## Como funcionan las listas en HTML

Las listas HTML permiten a los desarrolladores web agrupar un conjunto de elementos relacionados en listas ordenadas y no ordenadas.

- Las listas ordenadas se utilizan para enumerar los elementos.
- Las listas no ordenadas se utilizan para agrupar un conjunto de elementos relacionados, en ningún orden particular.

```html
<h2>Lista ordenada</h2>
<ol>
  <li>Mango</li>
  <li>Manzana</li>
  <li>Plátano</li>
</ol>

<h2>Lista no ordenada</h2>
<ul>
  <li>Manzana</li>
  <li>Plátano</li>
  <li>Mango</li>
</ul>
```

## Qué es una tabla en HTML

Las tablas HTML permiten a los desarrolladores web agrupar un conjunto de datos en filas y columnas.

```html
<table>
  <tr>
    <th>Nombre</th>
    <th>Apellido</th>
    <th>Edad</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>30</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
    <td>25</td>
  </tr>
</table>
```

## Qué es un hipervínculo Un hipervínculo es un elemento HTML que permite a

los usuarios saltar de una página a otra simplemente haciendo clic en el enlace.
Los hipervínculos utilizan la etiqueta `<a

```html
<a href="https://www.google.com">Google</a>
```

## Qué es un hipervínculo interno

Un hipervínculo interno es un hipervínculo que apunta a otra página en el mismo sitio web. Los hipervínculos internos utilizan la etiqueta `<a>` y el atributo `href="#id"`, donde `id` es el valor del atributo `id` del elemento al que se está vinculando.

```html
<a href="#section1">Ir a la sección 1</a>
```

## Que es html semantico

HTML semántico es una forma de escribir HTML que hace que tu contenido web sea más legible para los humanos y los robots de búsqueda. La semántica en HTML significa que el código que escribes describe el contenido que contiene.

## Tips para escribir HTML semántico

- Usa etiquetas HTML que describan con precisión el contenido que contienen.
- Usa etiquetas HTML que tengan un significado semántico en lugar de usar etiquetas genéricas `<div>` o `<span>`.
- Usa etiquetas HTML que comuniquen claramente la estructura del documento.
- Usa etiquetas HTML que sean ampliamente admitidas en todos los navegadores.

## Que etiquetas son buenas para hacer html semantico

- `<header>`: Define un encabezado para un documento o una sección
- `<nav>`: Define un conjunto de enlaces de navegación
- `<main>`: Define el contenido principal de un documento
- `<section>`: Define una sección en un documento
- `<article>`: Define un artículo
- `<aside>`: Define contenido que está relacionado con el contenido que lo rodea
- `<footer>`: Define un pie de página para un documento o una sección

## Que son las etiquetas meta

Las etiquetas meta son elementos HTML que proporcionan información sobre una página web. Los metadatos no se muestran en la página web, sino que se utilizan por los navegadores (como la información de la página que se muestra en los resultados de búsqueda) y por los motores de búsqueda.

Las etiquetas meta siempre se colocan en la sección `<head>` de un documento HTML.

```html
<head>
  <meta charset="UTF-8" />
  <meta name="description" content="Free Web tutorials" />
  <meta name="keywords" content="HTML, CSS, JavaScript" />
  <meta name="author" content="John Doe" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>
```

## Que son etiquetas de auto cierre

Las etiquetas de auto cierre son etiquetas que no tienen contenido. Estas etiquetas no necesitan una etiqueta de cierre.

```html
<br />
<hr />
<img src="img.jpg" alt="Imagen" />
```

## Que son los formularios y que etiquetas se usan

Los formularios HTML son elementos que se utilizan para recopilar información de los usuarios. Un formulario HTML contiene elementos de formulario.

```html
<form>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname" /><br />
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname" /><br />
  <input type="submit" value="Submit" />
</form>
```

## Tips de HTML

- Usa minúsculas para los nombres de etiquetas y atributos.
- Usa comillas dobles para los valores de los atributos.
- No olvides cerrar las etiquetas.
- No olvides cerrar las etiquetas en el mismo orden en que las abriste.
- No olvides cerrar las etiquetas vacías.
- No olvides cerrar las etiquetas de comentarios.

```

```
