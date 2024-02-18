# Menús Desplegables en Formularios HTML

Los menús desplegables permiten a los usuarios elegir una opción de una lista desplegable utilizando la etiqueta `<select>` y múltiples etiquetas `<option>` para los ítems.

## Ejemplo
```html
<label for="cars">Elige un coche:</label>
<select id="cars" name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```
La etiqueta <select> define el menú desplegable en sí, mientras que cada etiqueta <option> representa una opción individual que los usuarios pueden seleccionar.

##  Características de <select>

El atributo name en el <select> se utiliza para identificar el elemento en los datos del formulario enviado.
Utilizando el atributo multiple en el <select>, puedes permitir que se seleccionen varias opciones.
El atributo size puede definir cuántas opciones son visibles sin desplegar el menú.