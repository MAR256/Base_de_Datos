## Práctica 4.
### Introducción a SQL
Objetivo: Demostrar la correcta identificación de los conceptos del lenguaje SQL
Ejercicio:

1. Menciona los comandos DMl: (valor .85)
    SELECT, INSERT, UPDATE, DELETE

2. Menciona 3 tipos de datos que existen: (valor .85)
    CHAR, INT, FLOAT

3. ¿Qué diferencia existe entre TRUNCATE y DELETE?(valor .85)
   Truncate es una operación DDL, no permite el borrado selectivo; elimina todo el contenido; no se puede ejecutar si la tabla tiene asociadas aún si no existiesen 
   registros en la tabla que  contiene la FK; es la forma más raída de eliminar el contenido de la tabla.
   
   Delete es una operación DML; permite el borrado selectivo mediante la clausula where; se puede ejecutar si hay FK asociada a la tabla pero siempre y cuando
    no haya registros asociados o la FK este deshabilitada, es más lenta.

4. ¿Para qué se utiliza el atributo UNIQUE?(valor .85)
    Nos permite establecer este atributo a los campos que requerimos tengan datos que no se puedan repetir.

5. ¿Qué diferencia hay entre los tipos de datos VARCHAR y CHAR? (valor .85)
    La longitud, char es una cadena de caracteres de longitud fija y varchar una cadena de caracteres de longitud variable con una longitud máxima n especificada por       el usuario, se ajusta al numero de caracteres.

6. Defina brevemente el significado de las siglas SQL(valor .85)
    Lenguaje de consulta estructurado. Lenguaje estándar e interactivo de acceso a bases de datos relacionales, permite especificar diversos tipos de operaciones,      gracias a la utilización del álgebra y de cálculos relacionales.

7. Defina brevemente qué es MySQL WorkBench (valor .85)
    Un editor visual de base de datos MySQL que cuenta con el respaldo oficial de MySQL.

## Práctica 5.
### Gestores de base de datos

Objetivo: Categorizar los distintos gestores de base de datos que existen y señalar las
ventajas y desventajas

Evaluación: Conoce los tipos de gestores de base de datos 3 puntos.

Domina sus diferencias de los gestores de base de datos mencionados 3 puntos

Ejercicio:

En un mapa conceptual presenta 3 gestores de bases de datos, sus características
principales, las ventajas y desventajas. (valor 6)

![image](https://user-images.githubusercontent.com/104279939/172019971-83faad0e-b0d1-47e4-a33d-be1471ecbe7a.png)

## Práctica 6.
### Herramienta en línea y ejercicio necesarios para realizar las prácticas

Creación de base de datos.

Objetivo: Demostrar mediante la creación de una base de datos el uso y la aplicación de
las funciones

Ejercicio: Creación de la base de datos (valor 18 puntos)

Tienda de informática

![image](https://user-images.githubusercontent.com/91554777/170415101-717bca19-3644-46a9-8a57-8d5940c5d283.png)




Modelo entidad/relación




Base de datos para MySQL
