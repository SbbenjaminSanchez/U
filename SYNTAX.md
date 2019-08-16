# U
Syntax

EN:


ES:
La sintaxis de U esta influenciada por Java, Python y JavaScript

Un ejemplo inicial de declaracion de funciones, para entendar la mezcla que debe ser aplicada.


VARIABLES
En U debemos registrar variables sin la necesidad de indicar el tipo de valor que contendra, antes del nombre de 
la variable debemos inficar que se trara de una variable global o privada.

let g variableName   //Variable publica
let p variableName2  //Variable privada

let gs variableName3   //Variable publica estatica
let ps variableName4  //Variable privada estadica

Sacrificamos el indicador del tipo de variable para indicar su tipo
-let-           Indica que se registra una variable a continuacion
-g-             Variable global
-p-             Variable privada
-gs-            Variable groblan estatica
-ps-            Variable privada estadica
-variableName-  Los nombres de las variables deben iniciar con letra minuscula

Debido a que U, seguira una filosofia de bloque organizados (codigo fuente), podremos inficar tipos de variables
por bloques y acceder a variables publicas entre bloques (Este tema se detallara mas adelante).



Funciones:
En U deberemos indicar si una funcion es -public- o -private- luego de usar la palabra recervada 'function',
seguido debemos colocar el nombre de la funcion, colocar apertura y cierre de parantesis () y abrir y cerrar llaves {}.

function public name(){
    //
}

Estas funciones pueden o no recibir paramentros, pero sin la necesidad de indicar el tipo de dato que contiene.

function private name(parameter){
    //
}

Es permitido retornar un valor desde una funcion sin la necesidad de indicar un retorno al momento de crear la funcion.

function private name(){    
    return 1 + 2
}