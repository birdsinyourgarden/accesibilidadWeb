# Ejercicios de Accesibilidad Web

### NOTA: podéis crear tantos index.html y styles.css como consideréis necesario

## Nivel Básico

### 1. Añadir texto alternativo a imágenes
**Enunciado:**  
Crea una página con 3 imágenes y añade texto alternativo a cada una para describir su contenido.

---

### 2. Mejora el contraste de texto y fondo
**Enunciado:**  
En un párrafo con texto gris claro (#cccccc) sobre un fondo blanco, ajusta los colores para mejorar el contraste según las normas de WCAG.

---

### 3. Usar subtítulos en videos
**Enunciado:**  
Añade subtítulos en español a un video con el archivo `subtitulos.vtt` y asegúrate de que los subtítulos sean visibles.

---

### 4. Formularios accesibles
**Enunciado:**  
Crea un formulario con un campo de texto para el nombre y asegúrate de que tenga una etiqueta asociada.

---

### 5. Navegación por teclado
**Enunciado:**  
Crea 3 botones en tu página y asegúrate de que sean accesibles mediante el teclado (usando la tecla Tab).

---

### 6. Evitar movimiento brusco
**Enunciado:**  
Crea un botón que parpadea rápidamente (0.3s) y ajusta su animación para que sea más accesible, siguiendo las normas de WCAG.

---

### 7. Contraste para enlaces
**Enunciado:**  
Crea un enlace sobre un fondo azul oscuro y ajusta su color para que sea legible, siguiendo las pautas de contraste.

---

### 8. Encabezados jerárquicos
**Enunciado:**  
Crea una página con un encabezado principal `<h1>` y subencabezados `<h2>` y `<h3>` para garantizar una estructura lógica.

---

### 9. Uso del atributo `lang`
**Enunciado:**  
Define el idioma del contenido en una página HTML en español usando el atributo `lang`.

---

### 10. Botón accesible
**Enunciado:**  
Crea un botón con el texto "Enviar" y asegúrate de que tenga un atributo `aria-label` que indique su propósito.

---

## Nivel Intermedio

### 11. Añadir roles ARIA
**Enunciado:**  
Crea una barra de navegación y usa atributos ARIA para especificar su rol como `navigation`.

---

### 12. Validar formularios accesibles
**Enunciado:**  
Crea un formulario con campos para "Correo electrónico" y "Contraseña", y añade mensajes de error accesibles si los campos están vacíos.

---

### 13. Usar `aria-live`
**Enunciado:**  
Crea un mensaje dinámico que informe "Formulario enviado con éxito" y hazlo accesible mediante el atributo `aria-live`.

---

### 14. Contraste en botones
**Enunciado:**  
Crea un botón con un texto claro sobre un fondo oscuro y ajusta los colores para cumplir con las pautas de contraste.

---

### 15. Crear enlaces accesibles
**Enunciado:**  
Crea un enlace con el texto "Leer más" y mejora su accesibilidad añadiendo un atributo `aria-label` para especificar a dónde lleva.

---

### 16. Resaltar elementos al enfocarlos
**Enunciado:**  
Usa la pseudo-clase `:focus` para resaltar un enlace cuando sea seleccionado con el teclado.

---

### 17. Añadir subtítulos a contenido dinámico
**Enunciado:**  
Crea un botón que, al hacer clic, muestre un mensaje dinámico y haz que sea accesible con `aria-describedby`.

---

### 18. Estructura con etiquetas semánticas
**Enunciado:**  
Crea una página con las siguientes secciones: cabecera, contenido principal y pie de página, usando `<header>`, `<main>` y `<footer>`.

---

### 19. Crear un slider accesible
**Enunciado:**  
Crea un slider con tres imágenes y usa atributos ARIA para que los lectores de pantalla puedan describir su contenido.

---

### 20. Contenido multimedia accesible
**Enunciado:**  
Añade controles accesibles a un video que permitan pausar, reproducir y ajustar el volumen.

---

## Nivel Avanzado

### 21. Navegación accesible por teclado
**Enunciado:**  
Crea un menú de navegación que se pueda controlar completamente con el teclado (usando las teclas Tab y Enter).

---

### 22. Mejorar una tabla
**Enunciado:**  
Crea una tabla con encabezados y usa el atributo `scope` para mejorar su accesibilidad.

---

### 23. Crear un modal accesible
**Enunciado:**  
Crea un modal que se abra con un botón y que sea accesible mediante teclado, con un atributo `aria-hidden` para ocultarlo cuando esté cerrado.

---

### 24. Crear un sistema de alertas accesibles
**Enunciado:**  
Crea un sistema de alertas dinámicas (por ejemplo, "Error en el formulario") y hazlo accesible con `role="alert"`.

---

### 25. Contraste dinámico con CSS
**Enunciado:**  
Usa una consulta de medios (`prefers-contrast`) para ajustar el contraste de una página según las preferencias del usuario.

---

### 26. Iconos accesibles
**Enunciado:**  
Añade un icono decorativo junto a un enlace y asegúrate de que sea ignorado por los lectores de pantalla usando `aria-hidden="true"`.

---

### 27. Crear un mapa interactivo accesible
**Enunciado:**  
Crea un mapa en tu página con puntos interactivos y usa descripciones accesibles para cada uno.

---

### 28. Navegación por regiones
**Enunciado:**  
Crea una página con varias secciones y usa atributos ARIA para definir regiones navegables.

---

### 29. Comprobación de accesibilidad con Lighthouse
**Enunciado:**  
Realiza una auditoría de accesibilidad de un sitio web usando Lighthouse y señala tres posibles mejoras.

---

### 30. Coge una página web completa creada por ti (de proyectos anteriores) y transformala para que sea accesible
**Enunciado:**  
Diseña una página web que combine todas las técnicas aprendidas: texto alternativo, ARIA, navegación por teclado, formularios accesibles y diseño semántico.
