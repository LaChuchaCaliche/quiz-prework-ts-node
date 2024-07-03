# quiz-prework-ts-node
JavaScript Básico:

Describe qué es una función en JavaScript y cómo se declara.
Una funcion en javascript es un fragmento de codigo que ocupa su propio "entorno de ejecucion" y que al ser declarada como
var x = function () {};
Manipulación del DOM:

Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
primero con una sintaxis especifica para elementos HTML $ creamos una variable y en esa variable almacenamos el objeto del DOM con un getElementsbyid,classname, etc, y asi nos aseguramos de seleccionar esa parte del DOM, luego podemos interactuar agregandole childs con appedn childs, o agregando directamente eventlisteners 
Programación Orientada a Objetos (OOP):

¿Qué es una clase en JavaScript y cómo se define una?
Eventos en JavaScript:
Las clases en javascript son los prototipos que se definen con atributos y metodos 

¿Cómo se agrega un evento de clic a un botón en JavaScript?
Variables y Tipos de Datos:
con el comando .addeventlistener ("dbclick" , ()=>{function})
Explica las diferencias entre var, let, y const en JavaScript.
Control de Flujo:

¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
IF, ELSE , SWITCH , FOR, WHILE

Funciones de Flecha:

Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
una funcion flecha es una funcion no declarada que sirve para resolver una variable que necesita una transformación. 
let sum = () => { return (2+a)}
JSON:
¿Qué es JSON y cómo se utiliza en JavaScript?
JSON es un archivo que funciona como archivo modificable, por lo general java script lo usa para almacenar datos , como listas con objetos 
Promesas:

Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
una promesa en java script es un entorno de ejecucion ordenado en el cual utilizamos la expresion .then para definir las funciones en su orden y la cadena no se ejecutara hasta que el primer .then sea resuelto, por ultimo en cada .then se debe definir el return para que asi la función siguiente reciba y ejecute 
Depuración:
depurar es eliminar de lo que recuerdo qcreo que con remove o .pop
¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
Preguntas de Selección Múltiple (20)
¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable;
B) variable myVariable;
C) let myVariable;
D) A y C son correctas. X
¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
A) push()X
B) pop()
C) shift()
D) unshift()
¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
B) === X
C) !=
D) !==
¿Cuál es la salida del siguiente código?
console.log(typeof null);
A) null
B) undefined 
C) object X
D) number
¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
D) Todas las anteriores X
¿Qué se entiende por “hoisting” en JavaScript?
A) Declaraciones de variables y funciones se mueven al principio de su ámbito. X
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.
¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor. X
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.
¿Cuál es el propósito del método Array.prototype.map()?
A) Modificar el array original.
B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original. X
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.
¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
B) Un proceso que permite a JavaScript realizar operaciones asincrónicas. X
C) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.
¿Cuál es la salida del siguiente código?

console.log(0.1 + 0.2 === 0.3);
A) true X
B) false
C) undefined
D) NaN
¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
D) Ninguna de las anteriores.
¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
D) A y C son correctas. X
¿Qué es un callback en JavaScript?

A) Una función que se pasa como argumento a otra función. X
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.
¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
B) Manejar operaciones asincrónicas de manera más simple y legible. X
C) Declarar variables globales.
D) Ninguna de las anteriores.
¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
C) Objetos
D) Ninguna de las anteriores. X
¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify() X
C) toString()
D) parseInt()
¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica. X
C) Un método para declarar variables.
D) Ninguna de las anteriores.
¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
C) shift()
D) unshift()
¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente. X
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.
¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation()
B) event.preventDefault() X
C) event.stop()
D) event.cancel()
