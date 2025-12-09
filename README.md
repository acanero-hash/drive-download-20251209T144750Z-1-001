# Guía Profesional de Etiquetas HTML
 
Este README tiene como objetivo proporcionar una referencia rápida y profesional sobre las etiquetas HTML más comunes y su uso adecuado. HTML (HyperText Markup Language) es el lenguaje estándar para crear páginas web y su estructura.

## Tabla de Contenidos

1.  [Estructura Básica de un Documento HTML](#estructura-básica-de-un-documento-html)
2.  [Etiquetas Semánticas](#etiquetas-semánticas)
3.  [Etiquetas de Texto](#etiquetas-de-texto)
4.  [Etiquetas de Enlaces e Imágenes](#etiquetas-de-enlaces-e-imágenes)
5.  [Etiquetas de Listas](#etiquetas-de-listas)
6.  [Etiquetas de Tablas](#etiquetas-de-tablas)
7.  [Etiquetas de Formularios](#etiquetas-de-formularios)
8.  [Colaboradores](#colaboradores)

## 1. Estructura Básica de un Documento HTML

Todo documento HTML comienza con una estructura fundamental:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la Página</title>
</head>
<body>
    <!-- Contenido de la página -->
</body>
</html>
```

-   `<!DOCTYPE html>`: Declaración del tipo de documento, define que el documento es HTML5.
-   `<html lang="es">`: Elemento raíz de la página, `lang="es"` especifica el idioma del contenido.
-   `<head>`: Contiene metadatos sobre la página (no visibles en el navegador).
    -   `<meta charset="UTF-8">`: Define la codificación de caracteres para el documento.
    -   `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configura la vista para dispositivos móviles.
    -   `<title>`: Define el título que aparece en la pestaña del navegador.
-   `<body>`: Contiene todo el contenido visible de la página web.

## 2. Etiquetas Semánticas

Las etiquetas semánticas dan significado a las diferentes partes de una página web, mejorando la accesibilidad y el SEO.

-   `<header>`: Representa contenido introductorio o un grupo de enlaces de navegación.
-   `<nav>`: Contiene enlaces de navegación.
-   `<main>`: Contenido principal y único del documento.
-   `<article>`: Contenido independiente y auto-contenido (por ejemplo, una entrada de blog).
-   `<section>`: Agrupa contenido relacionado temáticamente.
-   `<aside>`: Contenido relacionado con el contenido principal, pero que puede considerarse separado (por ejemplo, barras laterales).
-   `<footer>`: Contenido de pie de página para su sección o para todo el documento.

## 3. Etiquetas de Texto

-   `<h1>` a `<h6>`: Encabezados de diferentes niveles, `<h1>` es el más importante.
-   `<p>`: Párrafo de texto.
-   `<a>`: Enlace de hipertexto.
    -   `href`: Atributo que especifica la URL de destino.
-   `<strong>`: Texto con gran importancia (generalmente en negrita).
-   `<em>`: Texto enfatizado (generalmente en cursiva).
-   `<span>`: Contenedor en línea para aplicar estilos o manipular contenido con JavaScript.
-   `<div>`: Contenedor a nivel de bloque para agrupar elementos y aplicar estilos.
-   `<br>`: Salto de línea.
-   `<hr>`: Línea horizontal temática.

## 4. Etiquetas de Enlaces e Imágenes

-   `<a>`: Para crear enlaces.
    ```html
    <a href="https://www.ejemplo.com" target="_blank">Visitar Ejemplo</a>
    ```
    -   `target="_blank"`: Abre el enlace en una nueva pestaña.
-   `<img>`: Para insertar imágenes.
    ```html
    <img src="imagen.jpg" alt="Descripción de la imagen" width="500" height="300">
    ```
    -   `src`: Ruta de la imagen.
    -   `alt`: Texto alternativo para accesibilidad.
    -   `width`, `height`: Dimensiones de la imagen.

## 5. Etiquetas de Listas

-   `<ul>`: Lista desordenada (con viñetas).
-   `<ol>`: Lista ordenada (numerada).
-   `<li>`: Elemento de lista.

    ```html
    <ul>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
    </ul>

    <ol>
        <li>Primer elemento</li>
        <li>Segundo elemento</li>
    </ol>
    ```

## 6. Etiquetas de Tablas

-   `<table>`: Contenedor de la tabla.
-   `<thead>`: Encabezado de la tabla.
-   `<tbody>`: Cuerpo de la tabla.
-   `<tr>`: Fila de la tabla.
-   `<th>`: Celda de encabezado de la tabla.
-   `<td>`: Celda de datos de la tabla.

    ```html
    <table>
        <thead>
            <tr>
                <th>Encabezado 1</th>
                <th>Encabezado 2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Dato 1</td>
                <td>Dato 2</td>
            </tr>
        </tbody>
    </table>
    ```

## 7. Etiquetas de Formularios

-   `<form>`: Contenedor del formulario.
-   `<input>`: Campo de entrada (texto, número, email, etc.).
    -   `type`: Tipo de entrada (`text`, `email`, `password`, `submit`, etc.).
    -   `name`: Nombre del campo para el envío de datos.
    -   `placeholder`: Texto de ejemplo en el campo.
-   `<textarea>`: Área de texto multilinea.
-   `<button>`: Botón.
-   `<label>`: Etiqueta para un control de formulario.
-   `<select>`: Lista desplegable.
-   `<option>`: Opción dentro de una lista desplegable.

    ```html
    <form action="/submit" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" placeholder="Tu nombre">

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje" name="mensaje" rows="4"></textarea>

        <button type="submit">Enviar</button>
    </form>
    ```

## 8. Colaboradores

Queremos agradecer a las siguientes personas por sus valiosas contribuciones a este proyecto:

-   **Rafael Cordero (Pipkonx)** - Creación inicial del README y estructura de contenido. [GitHub](https://github.com/Pipkonx)
-   **Blazze (acanero-hash)** - Revisión y mejoras. [GitHub](https://github.com/acanero-hash)

¡Gracias por tu interés en aprender y contribuir al desarrollo web!