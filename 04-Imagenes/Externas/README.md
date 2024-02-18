# Imágenes Externas en HTML

Este directorio contiene ejemplos de cómo referenciar imágenes alojadas en servidores externos dentro de tu HTML.

## Cómo Utilizar Imágenes Externas

Las imágenes externas son aquellas que no se alojan en tu servidor o repositorio local, sino que se cargan desde una ubicación externa mediante una URL. Para incluir una imagen externa en tu página web, utilizas la etiqueta `<img>` con un atributo `src` que contiene la URL de la imagen.

## Ejemplo de Referencia a Imagen Externa

```html
<img src="https://ejemplo.com/imagen.jpg" alt="Descripción de la imagen">
```
Asegúrate de que la URL sea accesible y que tengas permiso para usar la imagen en tu sitio web.

## Buenas Prácticas
- Uso de Alt: Siempre utiliza el atributo alt para describir el contenido de la imagen. Esto es importante para la accesibilidad y para los usuarios que puedan tener las imágenes desactivadas en su navegador.
- Ancho y Alto: Especifica las dimensiones de la imagen para ayudar al navegador a reservar espacio mientras la imagen se está cargando.
- Derechos de Autor: Verifica que tienes el derecho de utilizar la imagen en tu sitio web para evitar problemas de derechos de autor.

## Ejemplo Completo en HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Referencia a Imagen Externa</title>
</head>
<body>

<!-- Inserción de una imagen externa en la página web -->
<img src="https://ejemplo.com/imagen.jpg" alt="Descripción de la imagen" width="500" height="auto">

</body>
</html>
``` 
