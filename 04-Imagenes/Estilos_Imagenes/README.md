# Estilos de Imágenes en HTML

Aplicar estilos a las imágenes es crucial para asegurar que se integren bien con el diseño general de la página web.

## Cómo Aplicar Estilos a Imágenes

Los estilos se pueden aplicar directamente con atributos en las etiquetas de imagen, o externamente usando CSS. Aquí hay un ejemplo usando atributos HTML:

```html
<img src="url-de-la-imagen.jpg" alt="Descripción de la imagen" width="500" height="300">
```
Para un control más detallado y mantenible, es recomendable usar CSS:

```css
.imagen-estilizada {
  width: 500px;
  height: auto;
  border: 1px solid #000;
  border-radius: 4px;
}

```

Y aplicarlo en tu HTML:

```html
<img src="url-de-la-imagen.jpg" alt="Descripción de la imagen" class="imagen-estilizada">
```

## Ejemplo


Ahora, para implementar el HTML con el estilo CSS que mencione, el código sería el siguiente:

```html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Imagen Estilizada</title>
<style>
  .imagen-estilizada {
    width: 500px;
    height: auto;
    border: 1px solid #000;
    border-radius: 4px;
  }
</style>
</head>
<body>

<!-- Imagen con enlace y estilo -->
<a href="https://www.ejemplo.com" target="_blank">
  <img src="https://images.pexels.com/photos/838413/pexels-photo-838413.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Imagen Prueba" class="imagen-estilizada">
</a>

</body>
</html>

```
## NOTA
A la hora de aplicarle el estilo a tu imagen tienes que enlazarlo correctamente


