# Ejercicios con Imágenes Locales

## Ejercicio 1
Añade una imagen local a tu documento HTML y utilízala como fondo de una sección de la página.

## Ejercicio 2
Organiza un conjunto de imágenes locales en una estructura de grilla utilizando CSS.


```html 
    <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Galería de Imágenes en Grilla</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="image-grid">
  <img src="imagen1.jpg" alt="Descripción de la imagen 1">
  <img src="imagen2.jpg" alt="Descripción de la imagen 2">
  <!-- Añadir más imágenes según sea necesario -->
</div>

</body>
</html>

```
``` css
.image-grid {
  display: 
  grid-template-columns: 
  gap: 
}

.image-grid img {
  width: 
  height: 
  transition: 
}

.image-grid img:hover {
  transform: 
}

```

## Ejercicio 3
Crea una presentación de diapositivas de imágenes locales que los usuarios puedan controlar con botones de siguiente y anterior.

```html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Presentación de Diapositivas Básica</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="slideshow">
  <div class="slide">
    <img src="imagen1.jpg" alt="Imagen 1">
  </div>
  <div class="slide">
    <img src="imagen2.jpg" alt="Imagen 2">
  </div>
  <div class="slide">
    <img src="imagen3.jpg" alt="Imagen 3">
  </div>
</div>

</body>
</html>


```
```css

.slideshow {
  position: 
  max-width: 
  margin: 
}

.slide {
  display: 
}

.slide:first-child {
  display: 
}

.slideshow:hover .slide {
  display: 
}

.slideshow:hover .slide:nth-child(2) {
  display: 
}

.slideshow:hover .slide:nth-child(3):hover {
  display: 
}

.slide img {
  width: 
  height: 
}

```

---

## Recursos Adicionales
Puedes encontrar recursos adicionales y páginas interactivas para practicar en los siguientes enlaces:

- [w3schools - HTML Images](https://www.w3schools.com/html/html_images.asp)
- [MDN Web Docs - Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [Codecademy - HTML & CSS](https://www.codecademy.com/learn/learn-html)

Recuerda probar tu código en diferentes navegadores para asegurarte de su compatibilidad.


Estos ejercicios están diseñados para que aprendas a manejar imágenes almacenadas en tu servidor o máquina local y a integrarlas de manera eficiente en tu diseño web.
