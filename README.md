# ASIX1_M4_UF1_A3_JordiSorribes
# GITHUB
**Git**

**Repositorio**
Un repositorio es un depósito centralizado que almacena el código fuente de un proyecto junto con su historial de versiones o commits.

**Branch**
Una rama (branch) es una línea de desarrollo independiente que permite a los desarrolladores trabajar en nuevas funcionalidades o arreglos sin interferir con la versión principal del código.

**Commit**
Un commit es un registro de cambios realizados en el código fuente de un proyecto. Cada commit se acompaña de un mensaje descriptivo que resume los cambios introducidos.

**Como clonar un Repositorio**
```
git clone <URL del repositorio>
```

**Como subir los cambios**
```
git push origin main
```

**Como añadir y confirmar cambios**
```
git add <nombre de archivo>
git commit -m "Mensaje descriptivo del commit"
```
# MARKDOWN
**Tipos de Encabezados HTML**
En HTML, existen seis niveles de encabezados, identificados por las etiquetas <h1> hasta <h6>. La etiqueta <h1> representa el nivel de encabezado más importante y el <h6> el menos importante. La importancia disminuye a medida que aumenta el número del encabezado.
<h1>Encabezado de Nivel 1</h1>
<h2>Encabezado de Nivel 2</h2>
<h3>Encabezado de Nivel 3</h3>
<h4>Encabezado de Nivel 4</h4>
<h5>Encabezado de Nivel 5</h5>
<h6>Encabezado de Nivel 6</h6>

**Tipos de Estilos de Letras**
Negrita (<strong> o <b>): Hace que el texto aparezca en negrita.
<strong>Texto en Negrita</strong>
<b>Texto en Negrita</b>

**Cursiva** (<em> o <i>): Aplica un estilo de cursiva al texto.
<em>Texto en Cursiva</em>
<i>Texto en Cursiva</i>

**Subrayado** (<u>): Subraya el texto.
<u>Texto Subrayado</u>

**Tachado** (<del>): Agrega una línea que atraviesa el texto.
<del>Texto Tachado</del>

**Codigo**
El codigo se expresa con 3 comas y se interpreta asi:
```
<html>
  <div
  </div>
</html>
```
<html>
  <div>
  </div>
</html>

[Esto es un enlace](https://www.w3schools.com/html/default.asp "Enlace a la pagina de w3schools")
[Esto es una imagen de ](https://github.com/100006162/ASIX1_M4UF1A3_JordiSorribes/blob/main/w3school.jpg "imagen de w3school")

# HTML
**Sintaxis HTML**
- **<!DOCTYPE html>**: Define el tipo de documento como HTML5.
- **<html>**: Define el comienzo y el final del documento HTML.
- **<body>**: Contiene todo el contenido visible de la página.
- **<head>**: Contiene metadatos, enlaces a archivos CSS, scripts, entre otros.
- **<title>**: Define el título de la página que se muestra en la pestaña del navegador.
- **<h1>, <h2>, <h3>, <h4>, <h5>, <h6>**: Encabezados que indican la importancia y jerarquía del texto.
- **<div>**: Define una división o sección genérica en un documento HTML.
- **<p>**: Define un párrafo de texto.
- **<a>**: Define un hipervínculo que enlaza a otra página web o recurso.
- **<br>**: Inserta un salto de línea o espacio en blanco.
- **<ul>**: Define una lista no ordenada.
- **<li>**: Define un elemento de la lista no ordenada.
- **<ol>**: Define una lista ordenada.
- **<li>**: Define un elemento de la lista ordenada.
- **<link>**: Enlaza un documento con un recurso externo, como una hoja de estilo CSS.
- **<img>**: Inserta una imagen en la página web.
- **<video>**: Inserta un video en la página web.
- **<tbody>**: Define el cuerpo de una tabla.
- **<thead>**: Define la cabecera de una tabla.
- **<table>**: Define una tabla.
- **<tr>**: Define una fila en una tabla.
- **<th>**: Define una celda de encabezado en una tabla.
- **<tfoot>**: Define el pie de una tabla.
- **<form>**: Define un formulario para recopilar información del usuario.
- **<input>**: Define un campo de entrada en un formulario.
- **<label>**: Etiqueta para un elemento de formulario.
- **<article>**: Define un contenido independiente que podría estar embebido en otro contexto.
- **<section>**: Define una sección de un documento.
- **<aside>**: Define contenido relacionado que no está directamente relacionado con el contenido principal.
- **<figure>**: Agrupa contenido relacionado y su leyenda.
- **<audio>**: Inserta audio en la página web.

# CSS
## SELECTOR
Los selectores en CSS se utilizan para aplicar estilos a elementos HTML específicos. Pueden apuntar a elementos individuales, grupos de elementos o clases.
- **.**: Selector de clase.
- **body**: Selector para el cuerpo del documento HTML.
- **h1, h2, h3, h4, h5, h6**: Selectores para los diferentes niveles de encabezados.
- **p**: Selector para los párrafos.

## PROPIEDADES
Las propiedades en CSS determinan cómo se mostrarán los elementos seleccionados. Aquí hay algunas propiedades comunes y su descripción:
- **font-family**: Define el tipo de fuente.
- **font-size**: Establece el tamaño de la fuente.
- **font-weight**: Controla el grosor de la fuente.
- **text-align**: Alinea el texto dentro de un elemento.
- **color**: Define el color del texto.
- **opacity**: Establece la opacidad de un elemento.
- **background**: Define el fondo de un elemento.
- **background-color**: Establece el color de fondo de un elemento.
- **background-image**: Especifica una imagen de fondo.
- **border-radius**: Define la curvatura de los bordes.
- **position**: Controla la posición de un elemento.
- **width**: Define el ancho de un elemento.
- **height**: Establece la altura de un elemento.
- **padding**: Define el relleno alrededor del contenido de un elemento.
- **margin**: Establece el margen alrededor de un elemento.
- **text-decoration**: Define la decoración del texto.
- **min-width**: Establece el ancho mínimo de un elemento.
- **max-width**: Establece el ancho máximo de un elemento.
- **overflow**: Controla el comportamiento de desbordamiento de un elemento.
- **display**: Define cómo se muestra un elemento.
- **float**: Establece la alineación horizontal de un elemento.

## VALORES
Los valores en CSS son los datos que se asignan a las propiedades. Aquí hay algunos valores comunes:
- **url**: URL para enlazar recursos externos.
- **0px**: Unidad de medida de píxeles.
- **auto**: Valor automático.
- **center**: Centra el contenido.
- **scroll**: Habilita la barra de desplazamiento.
- **hidden**: Oculta el contenido que excede los límites.
- **border-box**: Define el modelo de caja de borde.
- **static, relative, absolute, fixed, sticky**: Controla el posicionamiento de un elemento.
- **block, inline-block**: Define el tipo de visualización de un elemento.
- **blue**: Representa un color en CSS.

# DISEÑO RESPONSIVE
## Sintaxis
Las Media Queries se definen utilizando la regla `@media` seguida de una o varias condiciones que especifican las características del dispositivo o del medio. La sintaxis general es la siguiente:

```css
@media only screen and (max-width: 600px) {
  /* Estilos específicos para dispositivos con un ancho máximo de 600px */
}

Se suelen utilizar para pedidas de mobiles (768px) y otras medidas como: 600px, 768px, 992px o 1200px...
