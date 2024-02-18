# Listas Ordenadas en HTML

Las listas ordenadas se utilizan cuando el orden de los items es importante. Se representan con la etiqueta `<ol>` y los items dentro de la lista se numeran automáticamente.

## Ejemplo de Uso
```html
<ol>
  <li>Primer paso</li>
  <li>Segundo paso</li>
  <li>Tercer paso</li>
</ol>
```
## Puntos Importantes
- Se pueden usar diferentes tipos de numeración utilizando el atributo type en la etiqueta <ol>.
  
1: para números.
A: para letras mayúsculas.
a: para letras minúsculas.
I: para números romanos mayúsculos.
i: para números romanos minúsculos.


  ```html
    <!-- Lista Ordenada con Números  -->
  <ol type="1">
    <li>Primer item</li>
    <li>Segundo item</li>
    <li>Tercer item</li>
  </ol>
  
  <!-- Lista Ordenada con Letras Mayúsculas -->
  <ol type="A">
    <li>Primer item</li>
    <li>Segundo item</li>
    <li>Tercer item</li>
  </ol>
  
  <!-- Lista Ordenada con Letras Minúsculas -->
  <ol type="a">
    <li>Primer item</li>
    <li>Segundo item</li>
    <li>Tercer item</li>
  </ol>
  
  <!-- Lista Ordenada con Números Romanos Mayúsculos -->
  <ol type="I">
    <li>Primer item</li>
    <li>Segundo item</li>
    <li>Tercer item</li>
  </ol>
  
  <!-- Lista Ordenada con Números Romanos Minúsculos -->
  <ol type="i">
    <li>Primer item</li>
    <li>Segundo item</li>
    <li>Tercer item</li>
  </ol>
  ```

- El orden se genera automáticamente y se ajusta si se añaden o eliminan items.

