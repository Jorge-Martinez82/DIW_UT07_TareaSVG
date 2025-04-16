# Adóptame – Pagina Web

## Descripcion general

Esta pagina web One Page forma parte del proyecto Adóptame. Se ha diseñado pensando primero en dispositivos móviles (Mobile First), asegurando una experiencia clara y fluida en pantallas pequeñas, y adaptándose progresivamente a resoluciones más grandes.

## Decisiones de diseño

- **Colores suaves y amigables**: Se han utilizado tonos cálidos y fondos con huellas para transmitir cercanía y ternura.
- **Tipografía legible**: Se combinan las fuentes *Montserrat* y *Roboto* para lograr títulos llamativos y textos fáciles de leer.
- **Distribución sencilla**: El contenido está organizado en bloques verticales con buena separación, facilitando la lectura y navegación desde móviles.

## Animaciones implementadas

Se han utilizado animaciones en CSS para mejorar la experiencia del usuario, sin saturar la página:

1. **Efecto de dibujo en SVG**: la imagen del gato muestra un efecto de “dibujo” progresivo, utilizando las propiedades `stroke-dasharray` y `stroke-dashoffset`.

2. **Animación con movimiento**: Al pasar el cursor sobre el perro, su cola se mueve como si saludara, gracias a una animación con `@keyframes`.

3. **Efecto de entrada en galería**: La imagen del conejo aparece con una animación de entrada que modifica su tamaño y cambia su opacidad, haciendo que se integren de forma más dinámica al cargar.

4. **Transiciones suaves**: Elementos interactivos como el botón de “Más información” o la tortuga responden al cursor con efectos de escala, brillo o color, mediante transiciones suaves.

## Llamado a la acción

Se ha incluido un botón animado que dirige a una página con más información sobre la iniciativa. Este botón cambia de color y tamaño al pasar el cursor para llamar la atención del usuario.
