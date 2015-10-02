# Resumen

Reporte programación
 
Variables estáticas: Las variables pueden ser creadas dentro de una función o fuera de esta, cuando son inicializadas dentro de una función, al termino de esta el valor de dicha función se pierde, y cada ves que se llama nuevamente a la función se le asigna el valor, al declarar esta variable como estática, el valor que tiene la variable al termino de la función seguirá siendo el que el método le asigne, y al llamar nuevamente a la función el valor con el que inicializará será el que tenia al finalizar la función.

Ciclo de vida de las variables: El tiempo de vida de una variable se define como el intervalo durante los cuales la variable existe, esta existe durante la ejecución de un programa, mientras se pueda acceder a su valor, donde se puede garantizar que dicho valor está almacenado en la localidad asignada para dicha variable.

Memoria dinámica: Está memoria, es la cual se reserva en tiempo de ejecución, es decir, esta puede variar durante la ejecución del programa. El uso de esta memoria es útil cuando no sabemos la cantidad de datos que vamos a utilizar durante la ejecución , una desventaja frente a la estática es que es mas lenta debido a que la anterior, ya esta definida previa a la ejecución del programa.

Clase: una clase la podemos definir como un campo general que contiene ciertas condiciones dadas, de un tipo distintivo y con funciones generales de este tipo.

Objeto: Un objeto perteneciente a una clase, es la instancia de esta clase, donde se parametrizan las funciones o condiciones de dicha clase, creando características distintivas a los demás objetos de la misma clase.

Instanciación: A esto se le conoce como el proceso de construir un objeto, cuando se crea un objeto, es necesario darle condiciones iniciales a este, para esto existe un método llamado constructor, que es llamado cada ves que una variable es instanciada.

Herencia: Esta es una manera de crear una clase tomando como base de esta una clase ya existente, pasando a la nueva clase las características deseadas para esta.

Sobrecarga de funciones: Esto se llama al proceso donde asignamos el mismo identificador a diferentes funciones, las funciones son distintas, pero el uso de este recurso es para una identificación, son usadas cuando se tienen objetos del mismo tipo a los cuales se aplicaran funciones similares.

Ciclo de vida de variables:

“Variables de instancia:

•	–  Se crean cuando se crea el objeto que las contiene. 
•	–  Se inicializan por defecto si no se hace de modo explicito: • 0 para números, "false" para booleano, "null" para objetos. 
•	–  Se destruyen cuando el recolector de basura de Java no encuentra referencias activas para el objeto. 

Variables estáticas: 

•	– Se crean cuando la clase se usa por primera vez. 
•	– Se inicializan por defecto si no se hace de modo explicito: • 0 para números, "false" para booleano, "null" para objetos 
•	– Suelen existir para el resto del programa (salvo que no esté cargado).

Variables locales (en un método o bloque) 

•	– Existen desde el punto de definición hasta el final del bloque • Los bloques se definen mediante llaves { }
• Los bloques se suelen utilizar para definir: 
•	– El cuerpo del método
– Sentencias múltiples en operaciones de tipo if-else o en forma de bucles 
•	– Las variables locales solo existen dentro del propio método • No se da acceso a ningún otro método.” (MIT, 2002)

Bibliografía
MIT. (2002). 1.00 Introducción a la informática y a la resolución de problemas de ingeniería. Recuperado el Septiembre de 2015, de MIT OpenCoursWare: http://ocw.mit.edu/index.htm

