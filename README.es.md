<div align="center">

# Awesome Tailwind Animations

![web](./lib/imgs/web.jpg)

![Tailwind
CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.1-blue?style=for-the-badge&logo=tailwind-css)
![Astro](https://img.shields.io/badge/Astro-4.3.3-orange?style=for-the-badge&logo=astro)

Obten animaciones de CSS con una sola clase de Tailwind!

Visita la [web](https://tailwindcss-animations.vercel.app/) para obtener más
información.

</div>

## Instalación

Instala el paquete con tu gestor de paquetes favorito:

```sh
$ npm install @bissuett729/tailwind-animations
$ pnpm add @bissuett729/tailwind-animations
$ yarn add @bissuett729/tailwind-animations
```

Usa el plugin en tu configuración de Tailwind:

```js

// tailwind.config.mjs
import animations from '@bissuett729/tailwind-animations'

export default {
  // resto de opciones
  plugins: [
    animations
  ],
}

```

## Uso

Este plugin trae varias clases de utilidad así como varias animaciones CSS listas para usar. Aquí tienes algunos ejemplos simples:

```html
<div class="animate-fade-in">
  Fade in box
</div>

<div class="animate-slide-in-bottom animate-delay-300 animate-duration-slow">
  Slow animation after 300ms to slide in from bottom
</div>
```