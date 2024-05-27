# Esquema HTML5 CSS3 Javascript continuación
Esquema de pagina realizada con los estandares html5 y css3 con codigo javascript para gua de desarrollo de otras paginas

## HTML5

El nuevo estandar HTML5 provee los elementos estrucutrales, css se centra en comohacer esa estrucutra usable y atractiva visualmente y javascript provee el dinamismo a las aplicaciones web.

Existen elementos adicionales de HTML que podemos incorporar a nuestra página web que nos permiten presentar de manera adecuada la información según nuestras necesidades.

Las etiquetas principales que componen un documento HTML son las siguientes:

html
head
title
body
section
article
footer

Las etiquetas básicas para el uso en HTML son

h1 indica un encabezado, existen 6 diferentes niveles de encabezados

hr es una línea de división usada para separar secciones

br es una etiqueta que agrega un salto de línea en el documento

Para agregar un enlace a otra página o un sitio externo se usa la siguiente etiqueta

<a href="https://www.google.com">Ir a Google</a>

Para abrir el enlace en una nueva pestaña, se agrega el atributo target de la siguiente manera

<a target="_blank" href="https://www.google.com">Ir a Google</a>

## CSS3

CSS3 no fomra parte de la definición de HTML5, complementa esta para mejorar la presentacion de la pagina.

CSS3 sobreescribe los estilos por defecto del navegador.

CSS3 se enlaza con el documento HTML5 desde un archivo esterno a través de una etiqueta link dentro d la etiqueta head.

´´´ link rel = "stylesheet" href = "/css/estilos.css" ´´´

## Javascript

La finalidad principal de javascript es permitir la creacion de paginas dinamicas, con codigo que se ejecuta del lado del criente, disminuyendo la tarea del servidor y disminuyendo el numero de peticiones que se le hacen a este.

La inclusion de un codigo javascript en un documento HTML se indica mediante la inclucion de la siguiente linea en el encabezado

<script type="text/javascript"> y </script>
Sin embargo la mejor opcion es hacer un enlace a un archivo externo que contenga el codigo javascript, de la siguiente manera

<script type="text/javascript" scr="./js/script.js"></script>
Para que el documento quede validado, la etiqueta script debe tener el atributo

type="text/javascript"

En el valor scr se indica la ruta y el nombre del archivo que contiene el codigo javascript que se desea ejecutar desde la pagina HTML.

Referencias
Como incluir javascript en HTML
http://mialtoweb.es/como-incluir-javascript-en-html/
