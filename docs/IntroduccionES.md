# INTRODUCCIÓN

## ¿QUÉ ES HTML?

HTML (HyperText Markup Language) es el lenguaje estándar para estructurar el contenido de las páginas web. Es un lenguaje de marcado: su función es indicar al navegador qué es cada elemento, un título, un párrafo, una imagen, un enlace y cómo debe organizarse en pantalla. Vamos a definir que significa cada palabra de HTML.

HyperText (Hipertexto): es el corazón de la web o red. Se refiere a los enlaces que conectan una página web con otra. Al hacer clic en un enlace se navega a través de hipertexto. Es lo que transforma un documento aislado en una vasta red interconectada de información, permitiendo saltar de un sitio a otro con un simple clic.

Markup (Marcado): aquí reside la función principal de HTML. No es un lenguaje de programación como Python o Java, que se utilizan para crear programas con lógica compleja y funcionalidades dinámicas. Por el contrario, HTML es un lenguaje de marcado, lo que significa que su trabajo es marcar un documento con etiquetas (tags). Estas etiquetas actúan como instrucciones para el navegador web, indicándole cómo debe estructurar y mostrar los diferentes tipos de contenido.

Language (Lenguaje): como cualquier lenguaje, HTML posee su propia sintaxis, vocabulario y reglas que deben seguirse para que los navegadores puedan interpretarlo correctamente.
Para comprender qué significa HTML se puede recurrir a la analogía de la construcción de una casa para la que se necesitan planos detallados que definan la estructura básica: los cimientos, la ubicación de las paredes, las puertas y las ventanas. Este plano estructural es el equivalente al HTML en el mundo web. No se ocupa de cómo de bonita es la casa (el color de las paredes, el estilo de los muebles, etc.), sino de dónde va cada elemento fundamental. [1][2]

<img src="/Users/adrianlopezruiz/Desktop/ASIR/2ºASIR/Servicios de red e internet/1 TRIMESTRE/RA3html/img/Introducción_qué_es.png">

## ¿Para qué sirve HTML?

Sirve para:

- Estructurar el contenido: Define la jerarquía de la información, utilizando encabezados, párrafos, listas y otros elementos.

- Presentar información multimedia: Permite insertar imágenes, vídeos y audio en la página web.

- Crear enlaces: Facilita la navegación entre diferentes páginas y sitios web.

- Facilitar la interacción con formularios: HTML permite crear formularios interactivos mediante etiquetas como `<form>`, `<input>`, `<textarea>` y `<button>`. Estos formularios son la puerta de entrada para que los usuarios se comuniquen con los sitios web, ya sea para contactar, iniciar sesión, realizar búsquedas, completar encuestas o efectuar compras en línea.

- Asegurar la accesibilidad: Ayuda a que las páginas web sean accesibles para personas con discapacidades.

HTML es la estructura de una página web. Es el código que le dice al navegador (como Chrome, Firefox o Safari) qué elementos debe mostrar y en qué orden deben aparecer. Sin esta estructura, la página sería un caos de texto y medios sin organización. [3] [1]


## Historia
La historia del HTML empieza en 1989 cuando el investigador Tim Berners-Lee lo inventa con el fin de compartir artículos científicos. La primera versión sólo contaba con 18 etiquetas para texto. Lo que lo hacía especial es que podía ligar varios documentos con el hipertexto. Todo esto se podía visualizar en un navegador llamado World Wide Web.

En 1996 llegó la versión HTML 3.2 la cual ha sido una de las más completas y que ha marcado la historia del HTML hasta nuestros días.

Es importante mencionar que en este tiempo se utilizaba un navegador de nombre NSCA Mosaic. Posteriormente se lanzó la primera versión de Netscape, quien en unos cuantos meses era usado por la mayoría de los usuarios en internet.

En la evolución de internet jugaron un papel fundamental otros lenguajes de programación. La introducción de Java o JavaScript dio más forma a la segunda versión de HTML. Gracias a este lenguaje se podían implementar tablas, imágenes, tipografías e incluso colores. Posteriormente surgió el CSS (hojas de estilo en cascada) con el que se da estilo y forma a los textos.

En la tercera versión de HTML se incluyen las etiquetas específicas para los navegadores web como Internet Explorer. Sin embargo, esta decisión sólo causó caos y problemas. Por esta razón se decidió hacer un cambio hacia un estándar único.

En esta nueva versión se incluyeron etiquetas como `<a>`, `<estilo>`, `<java>` y `<DIV>`. Es así que en la versión HTML 4.0 se agregan los botones y el iFrame para poder tener sitios dentro de otros sitios. En 2014 se desarrolló la quinta versión de HTML. Esta actualización llegó con un sin fin de audios, vídeos e inputs.

<table><thead><tr><th style="text-align:left">Versión</th><th style="text-align:right">Año</th><th style="text-align:left">Aporte principal</th></tr></thead><tbody><tr><td style="text-align:left">HTML 1.0</td><td style="text-align:right">1991</td><td style="text-align:left">Primera versión: encabezados, párrafos, listas, enlaces</td></tr><tr><td style="text-align:left">HTML 2.0</td><td style="text-align:right">1995</td><td style="text-align:left">Estandariza características ya usadas, formularios básicos</td></tr><tr><td style="text-align:left">HTML 3.2</td><td style="text-align:right">1997</td><td style="text-align:left">Soporte para tablas, scripts y más estilos de presentación</td></tr><tr><td style="text-align:left">HTML 4.0</td><td style="text-align:right">1997</td><td style="text-align:left">Separa contenido (HTML) y presentación (CSS)</td></tr><tr><td style="text-align:left">HTML 4.01</td><td style="text-align:right">1999</td><td style="text-align:left">Actualización y correcciones de HTML 4.0</td></tr><tr><td style="text-align:left">HTML5</td><td style="text-align:right">2014</td><td style="text-align:left">Etiquetas semánticas, multimedia, canvas, SVG, apps web</td></tr></tbody></table> [4] [5]



## Conceptos clave (etiqueta, elemento, atributo)

Las etiquetas son los bloques con los que se construye cualquier página web: cada una tiene una función específica y define un tipo de elemento. Se escriben entre corchetes `< >` y casi siempre vienen en pares: etiqueta de apertura y de cierre.

Las más utilizadas son:

- Encabezados de `<h1>` a `<h6>`: organizan el contenido de forma jerárquica. h1 es el título principal de la página; los siguientes actúan como subtítulos de menor jerarquía.

- Párrafo `<p>`: define bloques de texto.

- Enlace `<a href="...">`: crea hipervínculos hacia otras páginas o recursos.

- Imagen `<img src="..." alt="...">`: inserta imágenes. El atributo alt es clave para la accesibilidad web y el posicionamiento en buscadores.

- Listas (`<ul>`, `<ol>`, `<li>`): crean listas no ordenadas y ordenadas.

- División `<div>` y texto en línea `<span>`: agrupan elementos para aplicarles estilos o comportamientos con CSS y JavaScript.

- Formulario `<form>`: estructura los campos donde los usuarios introducen datos. [1]


## Webgrafía:

https://www.unir.net/revista/ingenieria/que-es-html/ [1]

https://universidadeuropea.com/blog/que-es-html/ [2]

https://www.eaemadrid.com/es/blog/que-es-html [3]

https://div.zone/es/docs/html/historia-de-html [4]

https://sernagrp.com/blog/html/ [5]