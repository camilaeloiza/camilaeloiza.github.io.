# Bitácora de inteligencia artificial

## Consulta 1
- **Fecha:** 24/11/2026
- **Herramienta utilizada:** Gemini
- **Objetivo:** Generar la estructura semántica HTML5 base e incorporar mi información personal sobre informática y robótica.
- **Prompt completo:** "a ese codigo agregale la sigiente informacion nombre camila eloiza jazmin soy estudiante de informatica con conocimiento en robotica y agregale mas cosa"
- **Parte utilizada:** Estructura de etiquetas `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`, además de la redacción inicial de los proyectos de robótica.
- **Cambios realizados por mí:** Personalicé mi correo electrónico, agregué el campo de Evidencia en cada proyecto y verifiqué que los `id` coincidieran con el menú de navegación.
- **¿Qué comprendí?:** Entendí cómo funciona la navegación interna mediante anclas (`href="#proyectos"` conectado con `id="proyectos"`) y el uso de `<article>` para cada proyecto independiente.
- **¿Qué descarté y por qué?:** Descarté textos genéricos que no reflejaban mis prácticas reales con Arduino y Tinkercad.

## Consulta 2
- **Fecha:** 24/11/2026
- **Herramienta utilizada:** Gemini
- **Objetivo:** Rediseñar el aspecto visual aplicando una paleta en gamas de morados y vincular mi fotografía de perfil.
- **Prompt completo:** "a este codigo cambiale el color a gamas de morados y el diceño" / "esa foto ponrla en el codigo donde vaya la imagen"
- **Parte utilizada:** Las variables de color en `:root`, el diseño de tarjetas con sombras y la etiqueta `<img>` con forma circular (`border-radius: 50%`).
- **Cambios realizados por mí:** Separé el código CSS de la etiqueta `<style>` hacia el archivo externo `css/estilos.css` y renombré mi imagen a `perfil.jpg` dentro de `assets/img/`.
- **¿Qué comprendí?:** Comprendí cómo usar variables CSS para mantener una paleta coherente y cómo funcionan las rutas relativas (`assets/img/perfil.jpg`).
- **¿Qué descarté y por qué?:** Descarté dejar los estilos incrustados en el HTML para respetar la organización de carpetas de la guía.
