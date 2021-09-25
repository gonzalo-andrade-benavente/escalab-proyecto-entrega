# escalab-proyecto-entrega
Proyecto Final Escalab Master JS

# Descripción general del proyecto

Se debe realizar en modo SPA (Single Page Application) una tienda de comercio electrónico con las siguientes características:
Se debe utilizar HTML, CSS y Javascript o Typescript, no se permitirá el uso de frameworks (React, Angular u otro).
En caso de estar realizado en Typescript no debe incluir los archivos compilados a JS.
El proyecto solo debe contener 1 archivo html (index.html).
(done) El usuario debe ser capaz de ver una variedad de productos y añadirlos a un carro de compra.
(done) El usuario debe poder autenticarse, la validación debe ser estática y se debe aclarar cuál será el usuario y contraseña para uso del ejercicio.
(done) La posibilidad de iniciar sesión no debe estar disponible si el usuario ha iniciado sesión, y en ese caso debe mostrar el nombre del usuario.
(done) La cuenta de usuario no debe persistir cuando el usuario sale del sitio (cierra la pestaña o cierra el navegador).
(done) Cada producto debe tener 1 imagen, 1 título, 1 precio y stock disponible (entre 1 y 5 unidades).
(done) Cada producto debe indicar si ese producto se encuentra  en el carro de compras y en qué cantidad, permitiendo añadir más del mismo ítem.
(done) El usuario no debe ser capaz de solicitar una cantidad mayor a la disponible.
(done) El stock de productos debe persistir ante la recarga de la página y si el usuario sale del sitio.
(done) El carro de compra debe persistir sus datos aún cuando el usuario realice una recarga de la página o si el usuario sale del sitio.
(done) El carro de compra debe calcular el total de la compra en base al valor de los productos seleccionados, añadir un costo de $1500CLP por envío (US$ 2) y $350CLP (US$0,5) por cada producto.
(done) El carro de compra debe tener un botón de compra, que solo debe estar habilitado si el usuario ha iniciado sesión.
(done) Al realizar la compra, se debe simular una petición asíncrona que se demore 3 segundos en responder.
(done) Se debe notificar al usuario que la compra está siendo realizada, mientras esto sucede, el usuario no debe ser capaz de añadir nuevos productos ni realizar otra compra.
(done) Cuando se realiza la compra, el carro de compra debe ser vaciado y mostrar un mensaje de compra exitosa, pero permitiendo que el usuario sea capaz de volver a realizar una compra.
(done) El descuento de productos del stock general debe realizarse una vez realizada la compra
(done) Se debe añadir un botón al pie que permita restaurar los valores por defecto de la cantidad de productos.
