6543# Sistema de Pedidos para Bob's Auto Parts 1278
Este proyecto es un sistema básico de pedidos para una tienda de autopartes, **Bob's Auto Parts**, desarrollado utilizando HTML y PHP.
Permite a los usuarios realizar pedidos de productos específicos, calcular el total y mostrar la información sobre cómo el cliente 
conoció la tienda.

## Estructura del Proyecto
El proyecto está compuesto por los siguientes archivos:
- **`freight.html`**: Página que muestra los detalles de envío de los productos pedidos.
- **`freight.php`**: Script PHP que procesa la información del envío y muestra el resultado.
- **`orderform.html`**: Formulario de pedidos que permite al usuario seleccionar las cantidades de productos que desea comprar.
- **`processorder.php`**: Archivo PHP que procesa el pedido realizado, calcula el subtotal, el total con impuestos, y muestra cómo el cliente encontró la tienda.
  
## Funcionalidades
- **Realizar Pedido**: Los clientes pueden seleccionar productos como llantas, botellas de aceite y bujías, y hacer un pedido.
- **Cálculo de Precios**: Se calcula el total de los productos seleccionados, incluyendo impuestos.
- **Información del Cliente**: Se muestra cómo el cliente supo sobre la tienda (cliente regular, referencia de televisión, directorio telefónico, recomendación de boca a boca).
- **Visualización del Pedido**: Muestra un resumen del pedido con las cantidades de cada producto y el total con impuestos.

## Ejemplo de Uso
- **Formulario de Pedido**: Llena las cantidades de productos en `orderform.html`.
- **Proceso del Pedido**: El archivo `processorder.php` se encargará de calcular el total y mostrar los detalles del pedido.
- **Envío**: Usa `freight.html` para ver la información relacionada con el envío.7

## Requisitos
- **PHP**: Debes tener instalado PHP en tu servidor web.
- **Servidor Web Local**: Requiere un entorno como Apache para ejecutar los archivos PHP.

## Autor
Debora Alejandra Garcia Cruz
