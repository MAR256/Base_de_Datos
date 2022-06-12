# Proyecto Final de base de datos.
### Indicaciones de lo que se debe realizar

● Diseña el modelo entidad-relación del siguiente problema.
![image](https://user-images.githubusercontent.com/104279806/173203176-4c7dd335-6efd-41ec-a599-aeae91bea8a5.png)

● Crea el script para la base de datos.
Proveedores
https://www.db-fiddle.com/f/vchm3fFMd6WxuFHjJETNbx/1

Tenemos que diseñar una base de datos sobre proveedores y disponemos de
la siguiente información:

● De cada proveedor conocemos su nombre, dirección, ciudad, provincia y
un código de proveedor que será único para cada uno de ellos.

● Nos interesa llevar un control de las piezas que nos suministra cada
proveedor. Es importante conocer la cantidad de las diferentes piezas
que nos suministra y en qué fecha lo hace. Tenga en cuenta que un
mismo proveedor nos puede suministrar una pieza con el mismo código
en diferentes fechas. El diseño de la base de datos debe permitir
almacenar un histórico con todas las fechas y las cantidades que nos ha
proporcionado un proveedor.

● Una misma pieza puede ser suministrada por diferentes proveedores.

● De cada pieza conocemos un código que será único, nombre, color,
precio y categoría.

● Pueden existir varias categorías y para cada categoría hay un nombre y
un código de categoría único.

● Una pieza sólo puede pertenecer a una categoría.
