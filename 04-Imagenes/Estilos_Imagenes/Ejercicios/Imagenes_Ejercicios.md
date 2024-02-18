# Ejercicios de Estilos CSS para Imágenes

## Ejercicio 1
Aplica un estilo CSS a una imagen para que se atenúe al pasar el cursor sobre ella (efecto de opacidad). `opacity`



## Ejercicio 2
Crea un marco decorativo para tus imágenes utilizando propiedades CSS como `border` y `box-shadow`.

## Ejercicio 3
Diseña una galería de imágenes donde cada imagen cambie de tamaño y muestre un título cuando el usuario pase el cursor sobre ella.

`EJEMPLO DE CSS`

```css
.gallery {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.image-card {
  position: relative;
  margin: 10px;
}

.image-card img {
  width: 100%; 
  transition: transform 0.5s ease;
  border-radius: 5px;
}

.image-card:hover img {
  transform: scale(1.1); 
}

.caption {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.7); 
  color: white;
  text-align: center;
  padding: 10px;
  opacity: 0;
  transition: opacity 0.5s ease;
  border-radius: 0 0 5px 5px;
}

.image-card:hover .caption {
  opacity: 1; 
}
```

## Recursos Adicionales
Puedes encontrar recursos adicionales y páginas interactivas para practicar en los siguientes enlaces:

- [w3schools - HTML Images](https://www.w3schools.com/html/html_images.asp)
- [MDN Web Docs - Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [Codecademy - HTML & CSS](https://www.codecademy.com/learn/learn-html)

Recuerda probar tu código en diferentes navegadores para asegurarte de su compatibilidad.

---

Estos ejercicios te ayudarán a aprender a aplicar diferentes estilos CSS a las imágenes para hacerlas más atractivas visualmente.

