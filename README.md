# Neon Cursor Trail Effect

![Vista previa](assets/preview.svg)

Estela luminosa de cursor dibujada en un único canvas, con intensidad configurable y límite de partículas.

## Características

- Canvas de alta densidad limitado a `devicePixelRatio` 2.
- Intensidad suave, media o intensa.
- Conjunto acotado de partículas, sin nodos DOM permanentes.
- Desactivación automática en touch y movimiento reducido.

## Demo en vivo

[neon-cursor-trail-effect.netlify.app](https://neon-cursor-trail-effect.netlify.app)

## Instalación

Clona el repositorio, entra en `neon-cursor-trail-effect` y abre `index.html`.

## Estructura del proyecto

Canvas y controles en `index.html`, presentación en `style.css`, render en `script.js` y recursos en `assets/`.

## Cómo personalizarlo

Modifica `limits`, el color RGBA, el decaimiento `life` y el tamaño de las partículas.

## Accesibilidad

El canvas es decorativo, los controles son nativos y el estado explica cuándo el efecto no está disponible.

## Rendimiento

Un solo canvas, máximo configurable de partículas, render detenido cuando la estela queda vacía y resize limitado a DPR 2.

## Licencia y créditos

[MIT](LICENSE). Creado por [Nacho Torres](https://github.com/NachoTorresRD) para [NTDESWEB](https://www.ntdesweb.com) con [NT-SKILL SUPREME](https://github.com/NachoTorresRD/nt-skill-supreme).

[Ver en GitHub](https://github.com/NachoTorresRD/neon-cursor-trail-effect) · [Trabajar con NTDESWEB](https://www.ntdesweb.com)
