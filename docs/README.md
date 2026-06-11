# Tarea 03 — Narrativa individual en HTML

## Descripción

Esta página web presenta mi propuesta narrativa individual dentro de la webstory grupal sobre el deshielo glaciar en Chile. La historia se construye a partir de los datos del **Inventario Público de Glaciares 2022 (IPG 2022)** de la Dirección General de Aguas (DGA), combinando una crónica con voz propia y la visualización desarrollada en la entrega anterior.

**Sitio publicado:** [Click aquí](https://josegallegosg.github.io/tarea-03/)

---

## Contenido de la página

- Crónica narrativa sobre la pérdida de superficie glaciar en Chile
- Bloque de datos clave extraídos del IPG 2022
- Visualización de superficie glaciar por macrozona
- Lista de preguntas que guían la investigación grupal
- Fuentes y enlaces a las bases de datos originales

---

## Proceso

Lo primero que hice fue revisar los datos que ya tenía de la entrega anterior: la ficha técnica del IPG 2022 y la visualización en Altair. A partir de eso, definí qué historia quería contar: la paradoja de que Chile tiene el 80% de los glaciares de Sudamérica pero enfrenta una crisis hídrica creciente, especialmente en la zona central.

Para estructurar el HTML, empecé por dibujar en un cuaderno qué secciones tendría la página antes de escribir el código: encabezado, navegación, crónica, bloque de datos, visualización y fuentes. Eso me ayudó a tener claro qué etiquetas necesitaba usar.

Traté de que la crónica tuviera un tono mixto: datos concretos del inventario (superficie, volumen, distribución por macrozona) combinados con una voz más personal de Shoan (el huemul) que conectara esos números con el problema real. 

En cuanto al HTML, usé las etiquetas vistas en clases (`<header>`, `<footer>`, `<nav>`, `<main>`, `<div>`, `<figure>`, `<blockquote>`, listas ordenadas y no ordenadas) y agregué algunos elementos que busqué por mi cuenta, como el atributo `rel="noopener"` en los links externos y el uso de `<figcaption>` para describir la imagen.

El CSS hice lo más interactivo y atractivo posible para poder mantener a la audiencia interesada en un tema tan complejo como este.

---

## Estructura de archivos

```
docs/
├── index.html       # Página principal
└── vis_01.jpg       # Imagen de la visualización (IPG 2022)
```

---

## Fuentes de datos

- [Inventario Público de Glaciares 2022 — DGA](https://dga.mop.gob.cl/inventario-publico-de-glaciares-actualizacion-2022/)
- [Fundación Glaciares Chilenos — Análisis IPG 2022](https://www.glaciareschilenos.org/reportajes/glaciares-chilenos-en-evolucion-analisis-del-inventario-publico-de-glaciares-2022/)
