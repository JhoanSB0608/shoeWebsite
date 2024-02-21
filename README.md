# Video de referencia

<iframe width="560" height="315" src="https://www.youtube.com/embed/oWmOqxIanjk?si=5-d7lzG1Y7dDdOUq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

HTML:

Etiquetas de HTML:

!DOCTYPE html> - Declara el tipo de documento y la versión de HTML que se está utilizando.
html lang="es"> - Define el comienzo del documento HTML y especifica el idioma del contenido.
head> - Contiene metadatos y enlaces a recursos externos utilizados por la página web.
meta charset="UTF-8"> - Especifica la codificación de caracteres del documento.
meta name="viewport" content="width=device-width, initial-scale=1.0"> - Define cómo el contenido debe escalar en dispositivos móviles.
title> - Define el título de la página web que se mostrará en la pestaña del navegador.
link> - Enlaza una hoja de estilo externa al documento HTML.
script> - Enlaza un script JavaScript externo al documento HTML.
body> - Contiene todo el contenido visible de la página web.
header> - Define el encabezado de la página web.
nav> - Define una sección de navegación.
div class="container"> - Define un contenedor para el contenido de la barra de navegación.
img> - Inserta una imagen.
div class="menu"> - Define una sección de menú dentro de la barra de navegación.
ul> - Define una lista sin ordenar.
li> - Define un elemento de lista.
a> - Define un enlace.
form> - Define un formulario para entrada de usuario.
div class="search-icon"> - Define un icono de búsqueda.
input> - Define un campo de entrada.
button> - Define un botón.
div class="menu-btn"> - Define un botón de menú.
div class="body"> - Define una sección del cuerpo de la página web.
div> - Define un contenedor genérico.
h4> - Define un encabezado de nivel 4.
h1> - Define un encabezado de nivel 1.
div class="rating"> - Define una sección de calificación.
i> - Define un icono.
p> - Define un párrafo de texto.
a> - Define un enlace.
img> - Inserta una imagen.
footer class="footer"> - Define el pie de página de la página web.
div class="social"> - Define una sección de redes sociales.
a> - Define un enlace.
div class="watch"> - Define una sección de reloj.
div class="play-icon"> - Define un icono de reproducción.



CSS:

Funciones:

rgba() - Define un color utilizando valores de rojo, verde, azul y un valor alfa para la transparencia.
Ejemplo: background: rgba(255, 255, 255, 0.3); establece un color de fondo blanco con una opacidad del 30%.

Clases y Selectores:
.container - Selecciona elementos con la clase "container".
.menu - Selecciona elementos con la clase "menu".
.search-icon - Selecciona elementos con la clase "search-icon".
.logo - Selecciona elementos con la clase "logo".
.nav-btn - Selecciona elementos con la clase "nav-btn".
.footer - Selecciona elementos con la clase "footer".
.play-icon - Selecciona elementos con la clase "play-icon".
header::before - Selecciona el pseudo-elemento ::before del elemento header>.
header::after - Selecciona el pseudo-elemento ::after del elemento header>.
.body - Selecciona elementos con la clase "body".

Propiedades CSS:
margin - Establece los márgenes externos de un elemento.
padding - Establece el espacio entre el borde de un elemento y su contenido.
font-family - Define la familia de fuentes utilizada para el texto.
background - Define el color de fondo de un elemento.
color - Define el color del texto.
z-index - Define el orden de apilamiento de un elemento en relación con otros elementos.
position - Especifica el método de posicionamiento utilizado para un elemento.
display - Especifica el comportamiento de visualización de un elemento.
align-items - Alinea los elementos flexibles dentro de un contenedor flex en el eje transversal.
grid-template-columns - Especifica las columnas de un grid.
justify-content - Alinea los elementos flexibles dentro de un contenedor flex a lo largo del eje principal.
list-style-type - Especifica el tipo de viñeta o numeración de una lista.
text-decoration - Especifica la decoración del texto.
text-transform - Especifica cómo se debe transformar el texto.
border-radius - Define el radio de las esquinas de un borde.
transition - Especifica cómo se deben animar los cambios en las propiedades CSS.
width - Establece el ancho de un elemento.
height - Establece la altura de un elemento.
border - Define un borde alrededor de un elemento.
outline - Establece una línea alrededor de un elemento.
cursor - Especifica el tipo de cursor que se mostrará cuando se pase el ratón sobre un elemento.
font-size - Establece el tamaño de fuente del texto.
letter-spacing - Establece el espaciado entre caracteres.
line-height - Establece la altura de línea para el texto.
overflow - Especifica cómo manejar el contenido que desborda el elemento.
transform - Aplica una transformación a un elemento.
filter - Aplica efectos visuales a un elemento.
box-shadow - Agrega una sombra alrededor de un elemento.
nth-child() - Selecciona el enésimo hijo de su elemento padre.
max-width - Establece el ancho máximo de un elemento.
margin-right - Establece el margen derecho de un elemento.
text-align - Establece la alineación del texto dentro de un elemento.
box-sizing - Define cómo se deben calcular el ancho y alto de un elemento.


JavaScript:

Funciones:

document.querySelector() - Una función que selecciona el primer elemento que coincida con un selector CSS especificado en el documento.
Ejemplo: const menu = document.querySelector(".menu") selecciona el primer elemento con la clase "menu" y lo guarda en la variable menu.

addEventListener() - Un método que agrega un evento a un elemento HTML y especifica una función que se ejecutará cuando ocurra el evento.
Ejemplo:
menuBtn.addEventListener("click", () => {
   menu.classList.toggle('nav-toggle');
});
Agrega un evento de clic al elemento con la clase "menu-btn". Cuando se hace clic en ese elemento, la función de flecha se ejecutará. Esta función toggle (alternar) la clase 'nav-toggle' en el elemento con la clase "menu".

Clases:
.menu - Clase CSS utilizada para seleccionar elementos HTML que representan el menú.
.menu-btn - Clase CSS utilizada para seleccionar elementos HTML que representan el botón del menú.

Métodos:
classList.toggle() - Un método que alterna (agrega o quita) una clase en un elemento HTML.
Ejemplo: menu.classList.toggle('nav-toggle'); alterna la presencia de la clase 'nav-toggle' en el elemento guardado en la variable menu. Si la clase está presente, la quita; si no está presente, la agrega. Esto se activa cada vez que se hace clic en el botón del menú.