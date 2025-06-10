# Muro Filosófico Digital 🧠

Una aplicación web sencilla donde los usuarios pueden:

- Ver y rotar frases filosóficas célebres.
- Enviar preguntas filosóficas y compartir reflexiones.
- Visualizar las preguntas y reflexiones recientes en un "muro" digital.

## Funcionalidades

- **Frase aleatoria:** Un botón muestra una frase célebre al azar de una pequeña colección.
- **Preguntas filosóficas:** Los usuarios pueden enviar preguntas, que se almacenan y muestran en la misma página.
- **Reflexiones:** Los usuarios pueden dejar reflexiones, también almacenadas y mostradas.
- **Persistencia local:** Tanto preguntas como reflexiones se guardan usando `localStorage` del navegador, permitiendo que se mantengan aunque se recargue la página.
- **Estilo moderno:** Interfaz limpia, amable y responsiva.

## Uso

1. Simplemente abre el archivo HTML (`index.html`) en tu navegador.
2. Haz clic en "Mostrar otra frase" para inspirarte.
3. Envía una pregunta filosófica o comparte una reflexión usando los formularios.
4. Las preguntas y reflexiones aparecerán en sus respectivos muros.

## Detalles técnicos

- **Frontend:** HTML5, CSS3 y JavaScript puro.
- **Almacenamiento:** `localStorage` (no requiere backend).
- **Límites:** Se guardan y muestran solo las últimas 20 preguntas y 20 reflexiones.

## Personalización

- Puedes agregar o modificar frases célebres editando el array `phrases` en el `<script>` del HTML.
- Para reiniciar el muro, limpia el almacenamiento local desde las herramientas de tu navegador.

## Propósito

Este proyecto busca fomentar el pensamiento crítico y la participación reflexiva, especialmente en contextos educativos o comunitarios.

---

Proyecto creado para el Muro Filosófico Digital.