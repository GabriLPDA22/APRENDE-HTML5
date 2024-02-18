# Imágenes Locales en HTML

Las imágenes locales son aquellas almacenadas en el mismo servidor o dominio que tu sitio web. Estas se referencian a través de rutas relativas o absolutas del servidor.

## Cómo Referenciar una Imagen Local

Para utilizar una imagen local en tu sitio web, usa la etiqueta `<img>` con el atributo `src` que apunta al archivo de la imagen dentro de tu estructura de proyecto.

```html
<img src="/ruta/del/proyecto/imagen.jpg" alt="Descripción alternativa de la imagen">
```
## Ejemplo con Ruta Relativa
- Si la imagen está en la misma carpeta que el archivo HTML, puedes hacer referencia a ella de esta manera:

```html
<img src="imagen.jpg" alt="Descripción alternativa de la imagen">
```
## Consideraciones
- Asegúrate de que la ruta de la imagen esté correcta para evitar imágenes rotas.
- Utiliza rutas relativas para hacer tu sitio más portable.
- El atributo alt es importante para la accesibilidad y para los usuarios que puedan tener imágenes desactivadas en sus navegadores.
