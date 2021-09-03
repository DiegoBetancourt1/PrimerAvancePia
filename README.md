# PrimerAvancePia
Primer avance del PIA de Programación Orientada a Objetos

Diego Fernando Betancourt González - 1855707
Osmar Eliud Fortuna Hernandez - 2034216

Nuestro objetivo con el PIA que realizaremos, es mejorar y/o arreglar el sistema de inventario de una tienda Seven Eleven, que tiene el problema de que no puede registrar bien los productos que recibe, los que tiene, los que vende y despues los que necesita marcar como merma. Con esto en mente, lo que buscamos implementar es el mejoramiento en el rendimiento del sistema de la tienda.

Entidades: Las entidades que componen el diagrama son: Menu, Jefe, Empleado y Cliente

Atributos: Los atributos de cada una de ellas son: 
Menu: Jefe(), Empleado() Cliente(), Nuevo() y Salir()
Jefe: VerProducto(), Agregar(), Quitar(), ConFab() y Menu()
Empleado: VerProducto(), Venta() y Menu()
Cliente: VerProducto(), Comprar() y Menu()

Funcionalidades:
ID: Sirve para obtener los distintos usuarios (Tanto de jefe, empleado y cliente)
ConFab: Sirve para encontrar los fabricantes/proveedores de productos
FechaCad: Sirve para obtener la fecha de caducidad del producto
Merma: Sirve para dar de baja productos del inventario de la tienda

Diagrama UML:

![Avance del PIA](https://user-images.githubusercontent.com/89086761/131973153-1a04194d-be62-47d2-9c20-d74666b9b0ab.png)

![Avance del PIA (1)](https://user-images.githubusercontent.com/89086761/131973159-cae2f6a8-e095-4e4e-9e4b-14ea1b21e871.png)


