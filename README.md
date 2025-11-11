# Leyendas del Asfalto

Este es un proyecto de landing page desarrollado como parte de una actividad práctica sobre la metodología **BEM (Block, Element, Modifier)**. La página está dedicada a los autos más icónicos del automovilismo: el BMW M3 GTR, el Ferrari 250 GTO y el Porsche 959.

El objetivo fue crear una página visualmente atractiva, aplicando todos los conceptos aprendidos de BEM para organizar bien el código HTML y CSS, haciendo que sea limpio, reutilizable y fácil de mantener.

**Enlace de la pagina:** (https://landing-page-basic-c15g.vercel.app/)

---

## ¿Qué es BEM y cómo lo usé?

BEM es una forma de nombrar las clases en HTML y CSS para que el código sea más claro y organizado. Se basa en tres ideas:

- **Bloque**: Un componente independiente (como una tarjeta o un menú).
- **Elemento**: Una parte interna de ese bloque (como el título o la imagen dentro de la tarjeta).
- **Modificador**: Una variación del bloque (por ejemplo, una tarjeta "destacada").

En este proyecto, lo apliqué así:

- `.feature-card` → **Bloque**: Cada tarjeta de auto.
- `.feature-card__title` → **Elemento**: El título dentro de la tarjeta.
- `.feature-card--highlighted` → **Modificador**: Para destacar el Ferrari 250 GTO.

Esto me ayudó a mantener el código ordenado y evitar errores al agregar estilos.

---

## ¿Qué incluye la página?

La landing page cumple con todos los requisitos solicitados:

1. **Header**: Con logo, menú de navegación y botón de llamado a la acción ("COMPRAR AHORA").
2. **Hero Section**: Con título impactante, subtítulo explicativo y fondo oscuro elegante.
3. **Features Section**: Tres tarjetas con imágenes, títulos y descripciones detalladas de cada auto. Una de ellas está destacada.
4. **Testimonios**: Comentarios ficticios de clientes satisfechos, estilo e-commerce.
5. **Precios**: Sección con valores aproximados de mercado y botones de compra.
6. **Formulario de contacto**: Con campos de nombre, email y mensaje, y validación básica.
7. **Footer**: Con enlaces, información de contacto y redes sociales.

Todo está en un solo archivo `index.html`, y los estilos están divididos por componentes en la carpeta `css/components/`, siguiendo buenas prácticas.
