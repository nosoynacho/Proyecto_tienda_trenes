# Tienda Virtual de Trenes

Este proyecto consiste en una página web de una tienda ficticia dedicada a la venta de distintos tipos de trenes.

La página fue realizada usando únicamente HTML y CSS. El proyecto está dividido en varias páginas para poder navegar entre las diferentes secciones desde el menú principal.

## Estructura del proyecto

```text
Tienda_virtual_de_trenes_paginas/
├── index.html
├── README.md
├── css/
│   └── styles.css
└── pages/
    ├── productos.html
    ├── multimedia.html
    ├── resenas.html
    └── contacto.html
```

El archivo `index.html` es la página principal. Las demás secciones se encuentran dentro de la carpeta `pages`.

## Secciones

El sitio cuenta con las siguientes secciones:

- Inicio
- Productos
- Multimedia
- Reseñas
- Contacto

Cada opción del menú lleva a una página HTML diferente.

## Productos

En la sección de productos se muestran seis tipos de trenes diferentes. Cada uno tiene una imagen, una descripción, algunas características y un precio.

Para ordenar las tarjetas de los productos se utilizó Flexbox.

## Reseñas

La página de reseñas contiene opiniones de clientes sobre los productos de la tienda.

En esta parte se utilizó CSS Grid para organizar el contenido.

## Multimedia

La sección multimedia incluye imágenes relacionadas con trenes y un video de YouTube agregado mediante un `iframe`.

## Contacto

La página de contacto tiene un formulario donde se puede ingresar:

- Nombre
- Correo electrónico
- Tipo de tren
- Mensaje

El formulario está conectado con Formspree para poder enviar los datos.

El endpoint utilizado es:

```html
action="https://formspree.io/f/xppqqbda"
```

## Diseño responsive

Se utilizaron Media Queries para que la página se adapte mejor a distintos tamaños de pantalla, como computadora, tablet y celular.

También se usaron propiedades de CSS para trabajar con fondos, imágenes, fuentes y la distribución de los elementos.

## Tecnologías utilizadas

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- Google Fonts
- Formspree

No se utilizó JavaScript.

## Cómo abrir el proyecto

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Abrir el archivo `index.html`.
3. Ejecutarlo con Live Server o abrirlo directamente desde el navegador.
4. Usar el menú de navegación para entrar a las distintas secciones.

## Imágenes

Las imágenes utilizadas en el proyecto fueron obtenidas de Wikimedia Commons.
