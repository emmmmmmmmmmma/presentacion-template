---
theme: default
title: 'Variables en CSS'
titleTemplate: 'Presentación - Variables en CSS'
background: https://source.unsplash.com/1920x1080/?code
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Variables en CSS
---

# Variables en CSS

---

# ¿Que resuelven las variables en CSS?


- 📝 **DRY** - Son útiles para evitar duplicación
- 🎨 **Tokens** - Sirven para crear tokens de diseño
- 🧑‍💻 **Amigable con Javascript** - Se pueden utilizar con Javascript para crear funcionalidad más avanzada

<br>

Referencia de MDN: [Variables en CSS](https://developer.mozilla.org/es/docs/Web/CSS/Using_CSS_custom_properties)

<style>
h1 {
  padding-bottom: 2rem;
}

.slidev-page-2 {
  background: hsla(235, 100%, 50%, .1);
}
</style>

---
layout: two-cols
---

# ¿Como podemos utilizarlas para evitar duplicación?

Creando tokens de diseño que reflejen nuestra tipografía, los colores de nuestro branding, <br>type-scale e imágenes relevantes que podemos actualizar en sólo sitio sin tener que buscar la línea de código relevante.


::right::

<div class="centrar">
  <img src="https://res.cloudinary.com/pmichventura/image/upload/v1634790394/presentaciones/tokens_ylexst.png">
</div>

<style>
h1 {
  font-size: 2rem !important;
  line-height: 3rem !important;
  padding-bottom: 40px;
}
p {
  padding-right: 20px;
  line-height: 25px !important;
}
.centrar {
  display: grid;
  place-content: center;
  height: 100%;
}
</style>

---
layout: iframe-right
url: https://codepen.io/venturamichel/embed/RwZGJrb
---

# Ejemplo

Vamos a añadir imágenes a nuestras variables de CSS para actualizar el background de distintas secciones.


<style>
h1 {
  font-size: 2rem !important;
  line-height: 3rem !important;
  padding-bottom: 40px;
}
p {
  line-height: 30px !important;
  padding-right: 20px;
}
</style>
