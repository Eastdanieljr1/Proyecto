# Proyecto diseño de software



# Introducción
El presente proyecto tiene como finalidad desarrollar un software para la gestión de ventas en la tienda "Abarrotes Tizimín". Dada la creciente necesidad de automatizar y mejorar la eficiencia en la administración de ventas, el gerente de la tienda busca implementar un sistema que permita registrar clientes, artículos y gestionar las compras de manera rápida y precisa.



# Objetivo
El objetivo principal del proyecto es diseñar e implementar un sistema de software que permita:
Registrar Clientes: Facilitar el almacenamiento de información detallada de los clientes, incluyendo identificador, nombre, apellido, dirección y teléfono.

Registrar Artículos: Gestionar el inventario de artículos, registrando su identificador, nombre, precio al público, precio del proveedor y cantidad en existencia.

realizar Compras: Permitir a los clientes realizar compras verificando la existencia de los artículos, generando un ticket con el detalle de la compra, que incluya el nombre del artículo, cantidad, precio, importe total, fecha y nombre del cliente.

Interfaz Gráfica de Usuario (GUI): Proporcionar una interfaz amigable y fácil de usar mediante un menú principal con opciones claras para registrar clientes, artículos, realizar compras y salir del sistema.


# Requerimientos Funcionales 

RF-001. Alta de vendedor El sistema deberá permitir el registro de los vendedores mediante un nombre de usuario y contraseña. Esta acción solo estará disponible con la cuenta de administrador, la cual se proporcionará al momento de entregar el sistema.

![1](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/85efcdae-0e43-4c65-8545-b732b6a7839c)

RF-002. Baja de vendedor  El sistema deberá brindar la posibilidad de dar de baja a un vendedor del sistema. Esta acción solo estará disponible con la cuenta de administrador.
![clientes](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/15053070-242f-4bc5-b61f-92af867d921b)

RF-003. Alta de productos  El sistema deberá permitir registrar productos, por parte del administrador. Este registro se compone del nombre del producto, un identificador para el producto, número de existencias, tamaño (en diferentes medidas disponibles), precio de proveedor y su precio de venta; al igual que su disponibilidad, es decir, se puede marcar como disponible para venta, si quiere que el producto esté a la venta, o no disponible para su venta, en caso contrario.

![2](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/16e7a2ae-0700-415a-ac46-f71b5f3a0ee4)

RF-004. Modificación de los datos de los productos  El sistema deberá permitir que los datos actuales, no críticos, de los productos registrados se puedan modificar, por parte del administrador. En otras palabras, permite al administrador modificar el nombre del producto, el número de existencias, la disponibilidad y el precio de venta para cada producto registrado; el identificador de cada producto será inmodificable.

![pasted image 0](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/a9486ff0-3769-458d-bf0c-140d5a1d70f8)

RF-005. Baja de productos  El sistema deberá permitir al administrador poder eliminar del sistema un producto registrado. Esta acción debe incluir una confirmación por parte del administrador para que se realice con éxito.

![pasted image 0](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/a9486ff0-3769-458d-bf0c-140d5a1d70f8)

RF-006. Visualización de productos disponibles <br> El sistema deberá mostrar a los vendedores y administrador los productos que están a la venta.

![1321](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/9a1d1c7f-a5d4-4256-98c6-19603f3e9bbb)

RF-007. Generar lista de compra El sistema deberá tener un apartado para que los vendedores que tengan una cuenta registrada puedan registrar la compra de productos elegidos por los clientes, en forma de una lista. Se debe tener en cuenta las opciones de pago: 

![3](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/87620cbd-f5e7-457a-9c8c-b343aeb7c48b)

RF-008. Cancelación de compra  El sistema debe permitir la cancelación de listas generadas previamente, esta cancelación solo podrá ser llevada a cabo mientras no se haya efectuado el pago.

![4](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/c28429c8-cb39-47b6-bb4d-d42a41795625)


RF-009. Calcular precios, totales y cambios  El sistema debe realizar las operaciones necesarias para generar el total de la compra, recibir un pago y en base al pago calcular el cambio del cliente.

![9](https://github.com/Eastdanieljr1/Proyecto/assets/143151182/e11874eb-1f44-48d0-adaa-063a17366623)


RF-010. Impresión de ticket  Brinda la posibilidad de generar un ticket con los datos de la compra como nombre de productos, precios, cantidad, total, pagado y devuelto (cambio). Aquí se van a detallar el vendedor que lo atendió y la hora de compra.

#Conclusion


El desarrollo e implementación del software de gestión para la tienda  representa un paso significativo hacia la modernización y optimización de las operaciones comerciales. A través de este sistema, se logrará una mejor organización y control de los datos de clientes y artículos, así como un manejo más eficiente de las ventas.

La utilización de Java y JavaFX proporciona una base robusta y flexible para el desarrollo del software, garantizando una interfaz de usuario intuitiva y fácil de usar. La capacidad de registrar clientes y artículos de manera sistemática, junto con la funcionalidad de generar tickets detallados de compra, no solo mejora la precisión de las transacciones, sino que también aumenta la satisfacción del cliente.

En resumen, la implementación de este sistema contribuirá a:

Automatización de Procesos: Reduciendo el tiempo y esfuerzo necesario para gestionar clientes y artículos.
Mejora en la Gestión del Inventario: Permitiendo un control más preciso de la cantidad de artículos en existencia.
Optimización del Servicio al Cliente: Asegurando que las compras se realicen de manera eficiente y se proporcione un ticket detallado.
Reducción de Errores Humanos: Minimizando los errores en el registro de datos y las transacciones

