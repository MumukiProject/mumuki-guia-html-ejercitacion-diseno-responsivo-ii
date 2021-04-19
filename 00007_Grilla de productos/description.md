Necesitamos organizar los productos de una tienda :convenience_store: mediante un código HTML que debe contener:

- un título `h1` que diga `Mi tienda`;
- un título `h2` que diga `Productos más comprados`;
- un párrafo `p` con `lorem ipsum`;
- una grilla con 6 cards productos, donde cada card de producto contiene:
  - una imagen del producto;
  - un título `h3` con el nombre del producto;
  - un párrafo `p` con el precio del producto;
  - un párrafo `p` con una oración `lorem ipsum`;

:warning: Consideraciones:

- la tipografía debe ser `Monserrat`;  
- los títulos y textos deberán tener un tamaño `1em`;
- para el tamaño de letra, utilizá unidades relativas y no absolutas (`em`);
- el título principal y el secundario, el párrafo, y la grilla deben estar centrados horizontalmente;
- la grilla debe tener un ancho máximo (no ocupar todo el ancho de la pantalla inicialmente);
- las cards de productos de la grilla deben estar espaciados entre sí con márgenes;
- las cards de productos de la grilla inicialmente deben tener una disposición de 3 productos por fila;
- utilizá breakpoints para que, a medida que la resolución se vaya achicando, la grilla cambie a 2 productos por fila y finalmente 1 producto por fila;
- cuando se muestran 3 y 2 productos por fila, la imagen debe estar arriba de la información del producto;
- cuando se muestra 1 producto por fila, la imagen debe estar a la izquierda de la información del producto;
- cuando se muestra 1 producto por fila, el título principal, el secundario y el párrafo, deben alinearse horizontalmente a la izquierda;
- utilizá un breakpoint que modifique el `font-size` del body, de modo tal que, al ser el tamaño del texto relativo a esta medida, cambien todos los demás tamaños en simultáneo.