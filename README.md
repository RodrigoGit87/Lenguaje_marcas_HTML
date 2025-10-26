
# Práctica: Crear una web completa (Tema 2)

## Directrices de la práctica

El objetivo de la práctica es realizar una página web donde se incluyan todas las etiquetas vistas en clase. Cada uno debe crear su propia página web personal con la temática que desee, adaptándose a los siguientes requisitos:

* La parte superior (**cabecera**) de la página debe tener un mensaje de bienvenida dentro de un `<h1>` y una imagen, ambos centrados (propiedad `align`).
* La imagen usada debe ser bastante grande y, por tanto, redimensionarse modificando su anchura.
* La parte inferior de la página (**pie de página**) debe tener un título `<h6>` indicando el autor y una dirección de correo electrónico del autor (no tiene por qué ser real).
* Después de la cabecera debe aparecer una serie de enlaces que serán **anclas internas** de la página que nos llevarán a cada una de las secciones de la misma. Debe tener contenido suficiente para que exista barra de desplazamiento.
* El número de secciones lo elegirá cada uno, con un **mínimo de 3**. Deberán empezar por un título en `<h2>` y estar separadas entre ellas con una línea hecha con la etiqueta `<hr>`.

---

### Requisitos adicionales

Además, la página debe incluir los siguientes requisitos:

* La página principal debe llamarse **`index.html`**.
* Al menos una **lista ordenada** y otra **no ordenada** con anidamiento.
* Al menos un párrafo con **negritas** y *cursivas*.
* La imagen de la cabecera debe tener un atributo `alt`.
* Al menos otra imagen que haga de **enlace a una página externa**.
* Un **enlace a una página interna**. El contenido de dicha página interna debe ser:
    * Un `<h1>`.
    * Una foto (imagen que no sea un dibujo, buscar una foto que represente algo real).
    * Un párrafo debajo de la misma que haga una descripción de la foto.
    * Esta página tiene que tener un enlace de vuelta a la página principal.
* La página interna debe estar en una **carpeta aparte** (dentro de la carpeta que contenga al `index.html`) y se deben enlazar mediante **direcciones relativas**.
* Las imágenes deben estar en una **carpeta aparte** (dentro de la carpeta que contenga al `index.html`) y se deben enlazar mediante **direcciones relativas**.
* Una **tabla** con todas sus etiquetas (`<thead>` con `<th>`, `<tbody>`, `<tfoot>`) con al menos 3 filas y 3 columnas (en `<tbody>`) usando de alguna forma `colspan` o `rowspan`.
* Un **formulario** con, al menos, las etiquetas `<fieldset>` y `<legend>`.
* Dentro del formulario debe haber, al menos:
    * `input` de tipo **texto** con tamaño mínimo y máximo, y `required`.
    * `input` de tipo **password** con tamaño mínimo, y `required`.
    * Botón de **submit**.
    * `input` de tipo **file**, `required` y que acepte solo vídeos. (Ver [enlace de ayuda MDN](https://developer.mozilla.org/es/docs/Web/HTML/Attributes/accept)).
    * Un `<select>` con al menos 4 opciones, una de ellas por defecto, y que sea obligatorio no elegir la opción por defecto. Cada `<option>` con su atributo `value`.
    * Un `checkbox` de obligada selección. Con atributo `value`.
    * Un `radio` con al menos 3 opciones. Con atributo `value`.
    * Un `<textarea>` con el tamaño de filas y columnas establecidas, siendo más ancho que alto.
