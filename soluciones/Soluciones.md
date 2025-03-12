# 🌍 Ejercicios de Accesibilidad Web  

Este repositorio contiene ejercicios prácticos para mejorar la accesibilidad web utilizando HTML y CSS.  

---

## 📌 Nivel Básico  

### 1. Añadir texto alternativo a imágenes  
```html
<img src="imagen1.jpg" alt="Paisaje montañoso con un río">
<img src="imagen2.jpg" alt="Un perro corriendo en el parque">
<img src="imagen3.jpg" alt="Plato de pasta con salsa de tomate y queso parmesano">
```

### 2. Mejora el contraste de texto y fondo  
```html
<p style="color: #333; background-color: #fff;">
  Este texto tiene un mejor contraste con el fondo.
</p>
```

### 3. Usar subtítulos en videos  
```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  <track src="subtitulos.vtt" kind="subtitles" srclang="es" label="Español">
  Tu navegador no soporta videos.
</video>
```

### 4. Formularios accesibles  
```html
<label for="nombre">Nombre:</label>
<input type="text" id="nombre" name="nombre">
```

### 5. Navegación por teclado  
```html
<button>Botón 1</button>
<button>Botón 2</button>
<button>Botón 3</button>
```

### 6. Evitar movimiento brusco 
```html
<style>
@media (prefers-reduced-motion: reduce) {
  .parpadeo {
    animation: none;
  }
}
@keyframes parpadeo {
  0% { opacity: 1; }
  100% { opacity: 0.5; }
}
.boton {
  animation: parpadeo 1.5s infinite;
}
</style>
<button class="boton">Parpadear</button>
```

### 7. Contraste para enlaces
```html
<a href="#" style="color: #FFD700; background-color: #00008B;">Enlace
```

### 8. Encabezados jerárquicos
```html
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
<h3>Sección dentro del subtítulo</h3>
```

### 9. Uso del atributo lang
```html
<!DOCTYPE html>
<html lang="es">
<head><title>Ejemplo</title></head>
<body>
  <p>Este es un documento en español.</p>
</body>
</html>
```

### 10. Botón accesible
```html
<button aria-label="Enviar formulario">Enviar</button>
```

## 📌 Nivel Intermedio 

### 11. Añadir roles ARIA
```html
<nav role="navigation">
  <ul>
    <li><a href="#">Inicio</a></li>
    <li><a href="#">Servicios</a></li>
  </ul>
</nav>
```

### 12. Validar formularios accesibles
```html
<form>
  <label for="email">Correo electrónico:</label>
  <input type="email" id="email" name="email" required>
  <span id="error-email" aria-live="polite"></span>

  <label for="password">Contraseña:</label>
  <input type="password" id="password" name="password" required>
  <span id="error-password" aria-live="polite"></span>

  <button type="submit">Enviar</button>
</form>
```

### 13. Usar aria-live
```html
<p id="mensaje" aria-live="assertive"></p>
<script>
  document.getElementById("mensaje").textContent = "Formulario enviado con éxito";
</script>
```

### 14. Constraste en botones
```html
<button style="color: white; background-color: black;">Accesible</button>
```

### 15. Crear enlaces accesibles
```html
<a href="articulo.html" aria-label="Leer más sobre accesibilidad web">Leer más</a>
```

### 16. Resaltar elementos al enfocarlos
```css
a:focus {
  outline: 3px solid yellow;
  background-color: black;
  color: white;
}
```

### 17. Añadir subtítulos a contenido dinámico
```html
<button id="mostrarMensaje">Mostrar mensaje</button>
<p id="mensaje" aria-describedby="info"></p>
<span id="info" hidden>Este es un mensaje importante</span>
<script>
  document.getElementById("mostrarMensaje").onclick = function() {
    document.getElementById("mensaje").textContent = "Mensaje mostrado";
  };
</script>
```

### 18. Crear enlaces accesibles
```html
<header>Encabezado</header>
<main>Contenido principal</main>
<footer>Pie de página</footer>
```

### 19. Crear enlaces accesibles
```html
<div role="region" aria-label="Galería de imágenes">
  <img src="imagen1.jpg" alt="Descripción de la imagen 1">
</div>
```

### 20. Contenido multimedia accesible
```html
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
```

## 📌 Nivel Avanzado

### 21. Navegación accesible por teclado
```html
<nav>
  <ul>
    <li><a href="#" tabindex="0">Inicio</a></li>
    <li><a href="#" tabindex="0">Servicios</a></li>
  </ul>
</nav>
```

### 22. Mejorar una tabla
```html
<table>
  <tr>
    <th scope="col">Nombre</th>
    <th scope="col">Edad</th>
  </tr>
  <tr>
    <td>Juan</td>
    <td>30</td>
  </tr>
</table>
```

### 23. Crear un modal accesible
```html
<div role="dialog" aria-hidden="true">
  <p>Este es un modal accesible.</p>
</div>
```

### 24. Crear un sistema de alertas accesibles
```html
<div role="alert">¡Error en el formulario!</div>
```

### 25. Contraste dinámico con CSS
```css
@media (prefers-contrast: high) {
  body {
    background-color: black;
    color: white;
  }
}
```

### 26. Iconos accesibles
```html
<i class="icono" aria-hidden="true"></i>
<a href="#">Enlace</a>
```

### 27. Crear un mapa interactivo accesible
```html
<map name="mapa">
  <area shape="rect" coords="34,44,270,350" alt="Descripción del área">
</map>
```

### 28. Navegación por regiones
```html
<div role="region" aria-labelledby="seccion1">
  <h2 id="seccion1">Sección 1</h2>
</div>
```

### 29. Comprobación de accesibilidad con Lighthouse
Este paso implica auditar el sitio con Lighthouse en Chrome DevTools.

### 30. Transformar una página para accesibilidad
Coger una web que no sea accesible y aplicar estos conceptos.
