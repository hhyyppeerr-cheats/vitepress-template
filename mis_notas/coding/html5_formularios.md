# Formularios

Los formularios son una parte importante de la web. Son la forma en que los usuarios interactúan con los sitios web y las aplicaciones. Los formularios son la forma en que los usuarios pueden enviar datos al servidor para su procesamiento posterior. Los formularios son la forma en que los usuarios pueden crear cuentas, escribir comentarios, realizar compras y realizar muchas otras acciones en línea.

## Elementos de un formulario

Los formularios se componen de uno o más elementos de formulario. Un elemento de formulario es un componente de un formulario que permite a los usuarios introducir datos. Los elementos de formulario incluyen:

- `<input>`
- `<textarea>`
- `<select>`
- `<button>`
- `<label>`
- `<fieldset>`
- `<legend>`

Un ejemplo de formulario:

```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

## Atributos de un formulario

Los formularios tienen varios atributos que controlan su comportamiento. Los atributos más importantes son: