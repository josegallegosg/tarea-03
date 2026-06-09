# Tarea 03 — Pieza narrativa individual en HTML

## Descripción

Esta página web presenta mi pieza narrativa individual dentro de la webstory grupal sobre el deshielo glaciar en Chile. La historia se construye a partir de los datos del **Inventario Público de Glaciares 2022 (IPG 2022)** de la Dirección General de Aguas (DGA), combinando una crónica con voz propia y la visualización desarrollada en la entrega anterior.

**Sitio publicado:** [link de GitHub Pages acá]

---

## Contenido de la página

- Crónica narrativa sobre la pérdida de superficie glaciar en Chile
- Bloque de datos clave extraídos del IPG 2022
- Visualización de superficie glaciar por macrozona
- Lista de preguntas que guían la investigación grupal
- Fuentes y enlaces a las bases de datos originales

---

## Proceso

Lo primero que hice fue revisar los datos que ya tenía de la entrega anterior: la ficha técnica del IPG 2022 y la visualización en Altair. A partir de eso, definí qué historia quería contar con mi pieza individual: la paradoja de que Chile tiene el 80% de los glaciares de Sudamérica pero enfrenta una crisis hídrica creciente, especialmente en la zona central.

Para estructurar el HTML, empecé por decidir qué secciones tendría la página antes de escribir una sola línea de código: encabezado, navegación, crónica, bloque de datos, visualización y fuentes. Eso me ayudó a tener claro qué etiquetas necesitaba usar.

Traté de que la crónica tuviera un tono mixto: datos concretos del inventario (superficie, volumen, distribución por macrozona) combinados con una voz más personal que conectara esos números con el problema real. Me interesaba especialmente la idea de que el hielo está en el sur pero la crisis está en el centro, porque eso no siempre queda claro cuando se habla de glaciares en términos generales.

En cuanto al HTML, usé las etiquetas vistas en clases (`<header>`, `<footer>`, `<nav>`, `<main>`, `<div>`, `<figure>`, `<blockquote>`, listas ordenadas y no ordenadas) y agregué algunos elementos que busqué por mi cuenta, como el atributo `rel="noopener"` en los links externos y el uso de `<figcaption>` para describir la imagen.

El CSS lo mantuve simple y funcional, sin intentar hacer algo complejo que distrajera del contenido.

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
