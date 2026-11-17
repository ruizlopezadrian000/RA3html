# Guía de uso de HTML

## Presentación

Bienvenidos a esta guía de uso de **HTML**. En ella aprenderemos los conceptos básicos para crear páginas web desde cero, conoceremos las etiquetas más utilizadas y veremos cómo organizar el contenido de una página.

Esta documentación está pensada para personas que están empezando a trabajar con desarrollo web.

## ¿Qué es HTML?

HTML (*HyperText Markup Language*) es un lenguaje de marcado que se utiliza para estructurar el contenido de las páginas web.

Con HTML podemos incluir:

- Títulos y párrafos.
- Imágenes y enlaces.
- Listas y tablas.
- Formularios.
- Secciones para organizar una página.

HTML no es un lenguaje de programación: sirve para definir la estructura y el significado del contenido.

## Objetivos de la guía

Al terminar esta guía podrás:

1. Comprender la estructura básica de un documento HTML.
2. Utilizar etiquetas habituales para crear contenido.
3. Añadir enlaces e imágenes.
4. Crear listas, tablas y formularios sencillos.
5. Organizar los archivos de una página web.
6. Comprobar el resultado desde un navegador.

## ¿Qué necesitas?

Para seguir los ejemplos solo necesitas:

- Un ordenador.
- Un editor de código, como Visual Studio Code.
- Un navegador web, como Chrome o Firefox.
- Crear archivos con extensión `.html`.

## Estructura básica de HTML

Todo documento HTML debe tener una estructura básica. Este es un ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primera página</title>
</head>
<body>
    <h1>Hola, mundo</h1>
    <p>Esta es mi primera página web.</p>
</body>
</html>
```

### ¿Qué significa cada parte?

- `<!DOCTYPE html>` indica que el documento utiliza HTML5.
- `<html>` contiene todo el documento.
- `<head>` incluye información sobre la página.
- `<meta charset="UTF-8">` permite utilizar caracteres como tildes y ñ.
- `<title>` establece el título que aparece en la pestaña del navegador.
- `<body>` contiene el contenido visible de la página.

## Etiquetas HTML más utilizadas

| Etiqueta | Función |
|---|---|
| `<h1>` a `<h6>` | Crear títulos y subtítulos. |
| `<p>` | Escribir párrafos. |
| `<a>` | Insertar enlaces. |
| `<img>` | Mostrar imágenes. |
| `<ul>` | Crear listas sin ordenar. |
| `<ol>` | Crear listas numeradas. |
| `<li>` | Añadir elementos a una lista. |
| `<table>` | Crear tablas. |
| `<form>` | Crear formularios. |
| `<br>` | Insertar un salto de línea. |

## Ejemplo: títulos y párrafos

```html
<h1>Mi página web</h1>
<h2>Sobre mí</h2>
<p>Estoy aprendiendo a crear páginas web con HTML.</p>
```

## Ejemplo: enlaces e imágenes

```html
<a href="https://www.google.com">Visitar Google</a>

<img src="imagen.jpg" alt="Descripción de la imagen">
```

El atributo `href` indica la dirección del enlace. En una imagen, `src` señala el archivo y `alt` ofrece una descripción alternativa.

## Ejemplo: listas

```html
<h2>Mis asignaturas</h2>
<ul>
    <li>Lenguajes de marcas</li>
    <li>Redes</li>
    <li>Programación</li>
</ul>
```

Se utiliza `<ul>` para una lista con viñetas y `<ol>` para una lista numerada.

## Ejemplo: tabla

```html
<table>
    <tr>
        <th>Nombre</th>
        <th>Edad</th>
    </tr>
    <tr>
        <td>Laura</td>
        <td>20</td>
    </tr>
</table>
```

## Ejemplo: formulario

```html
<form>
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre">

    <button type="submit">Enviar</button>
</form>
```

Los formularios permiten recoger información introducida por los usuarios.

## Cómo probar una página HTML

1. Abre Visual Studio Code o tu editor de código.
2. Crea un archivo llamado `index.html`.
3. Escribe o copia una estructura HTML básica.
4. Guarda el archivo.
5. Abre `index.html` con un navegador.
6. Modifica el código y actualiza el navegador para ver los cambios.

## Buenas prácticas

- Utiliza nombres de archivo sencillos y sin espacios.
- Escribe las etiquetas correctamente y ciérralas cuando corresponda.
- Mantén una indentación ordenada.
- Añade el atributo `alt` a las imágenes.
- Utiliza etiquetas semánticas, como `<header>`, `<main>`, `<section>` y `<footer>`.
- Comprueba la página en el navegador mientras trabajas.

## Conclusión

HTML es la base de la estructura de cualquier página web. Conociendo sus etiquetas principales podemos crear documentos organizados y añadir diferentes tipos de contenido. Esta guía sirve como punto de partida para continuar aprendiendo desarrollo web y, más adelante, combinar HTML con CSS y JavaScript.

---

**Fin de la guía.**
