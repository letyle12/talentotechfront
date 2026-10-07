# Nexo — Tecnología para tu día

## Propósito

Nexo es una página de muestra para una tienda de tecnología. Presenta una selección de productos, reseñas de clientes y un formulario de contacto. El proyecto fue creado como práctica de HTML semántico, CSS, Flexbox, Grid y diseño responsivo.

## Archivos

- `index.html`: contenido y estructura semántica de la página.
- `styles.css`: estilos externos, tarjetas de productos, cuadrícula de reseñas y ajustes responsivos.

## Cómo visualizar

Abre `index.html` en un navegador. Las fotografías y las fuentes tipográficas se cargan desde servicios externos, por lo que se necesita conexión a internet.

## Configurar el formulario de Formspree

El formulario ya incluye los campos de nombre, correo y mensaje, y usa el método `POST` de Formspree. Para que los mensajes lleguen a una cuenta:

1. Crea un formulario en [Formspree](https://formspree.io/) y confirma tu dirección de correo.
2. Copia el identificador que te proporciona Formspree.
3. En `index.html`, reemplaza `REEMPLAZA_CON_TU_ID` en el atributo `action` por ese identificador. Por ejemplo, el formato de la dirección es `https://formspree.io/f/ID_DEL_FORMULARIO`.
4. Envía un mensaje de prueba desde la página.

El endpoint depende de la cuenta del propietario, así que el valor de ejemplo debe configurarse antes de recibir envíos reales.
