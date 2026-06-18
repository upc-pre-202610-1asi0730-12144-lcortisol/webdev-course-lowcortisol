# Lección 7: Proyecto Final - Página de Perfil Personal

**Responsable:** Miguel

**Duración:** 10 minutos

## Objetivo

Integrar los conocimientos de HTML y CSS para crear una página web de perfil personal completa.

---

## Introducción

Bienvenidos a nuestra última lección del curso.

En esta sesión aplicaremos todo lo aprendido anteriormente sobre HTML y CSS para construir una página web de perfil personal.

Utilizaremos HTML para crear el contenido de la página y CSS para darle estilo y mejorar su apariencia visual.

Para desarrollar este proyecto utilizaremos CodePen, un editor de código gratuito que funciona completamente en línea.

---

## Desarrollo del HTML

En el panel izquierdo de CodePen observamos la sección HTML.

Primero utilizaremos la etiqueta:

```html
<body>
```

La etiqueta body representa el contenido visible de nuestra página web.

Dentro de ella agregaremos un contenedor utilizando la etiqueta:

```html
<div class="card">
```

Este contenedor agrupará todos los elementos de nuestro perfil.

### Imagen de perfil

Agregamos una imagen utilizando:

```html
<img src="URL-DE-LA-IMAGEN" alt="Imagen de perfil">
```

La propiedad `src` contiene la dirección de la imagen.

La propiedad `alt` proporciona una descripción alternativa cuando la imagen no puede mostrarse y mejora la accesibilidad.

### Título principal

Agregamos un encabezado principal:

```html
<h1>Mi perfil web</h1>
```

### Descripción personal

Luego agregamos un párrafo:

```html
<p>
  Hola, estoy aprendiendo a crear páginas web usando HTML y CSS.
</p>
```

### Lista de hobbies

Agregamos un subtítulo:

```html
<h2>Mis hobbies</h2>
```

Y una lista no ordenada:

```html
<ul>
  <li>Escuchar música</li>
  <li>Ver películas</li>
  <li>Aprender tecnología</li>
</ul>
```

### Enlace favorito

Finalmente agregamos un enlace:

```html
<a href="https://www.facebook.com">
  Visitar mi página favorita
</a>
```

Después cerramos correctamente todas las etiquetas.

---

## Desarrollo del CSS

Ahora trabajaremos en la sección CSS para mejorar el diseño.

### Estilos generales

Aplicamos estilos al body:

```css
body {
  background-color: #eef2f3;
  font-family: Arial, sans-serif;
}
```

### Tarjeta de perfil

Aplicamos estilos al contenedor:

```css
.card {
  width: 320px;
  margin: 40px auto;
  padding: 24px;
  text-align: center;
  background-color: white;
  border: 2px solid #dcdcdc;
  border-radius: 16px;
}
```

Explicación:

- width define el ancho.
- margin crea espacios externos.
- padding crea espacios internos.
- text-align centra el contenido.
- border agrega un borde.
- border-radius redondea las esquinas.

### Imagen de perfil

Aplicamos:

```css
img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
}
```

Explicación:

- width y height controlan el tamaño.
- border-radius: 50% genera una forma circular.
- object-fit: cover evita que la imagen se distorsione.

### Estilos adicionales

También podemos personalizar:

- Títulos.
- Párrafos.
- Listas.
- Enlaces.

Utilizando diferentes colores y tamaños.

---

## Resultado Final

Al ejecutar el proyecto observaremos:

- Imagen de perfil.
- Título principal.
- Descripción personal.
- Lista de hobbies.
- Enlace favorito.

Además podremos comprobar que el enlace funciona correctamente al hacer clic.

---

## Actividad

Modifica tu página de perfil:

- Cambia la imagen.
- Agrega tu nombre.
- Personaliza la descripción.
- Cambia los hobbies.
- Agrega más enlaces favoritos.
- Prueba diferentes colores y estilos.

---

## Cierre

¡Felicitaciones!

Has creado tu primera página web completa utilizando HTML y CSS.

Ahora cuentas con una base sólida para seguir aprendiendo desarrollo web.