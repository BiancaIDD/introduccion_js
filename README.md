# Introduccion_al_JS

Crear un nuevo archivo dentro de la carpeta `Clases` llamado `introduccion_js` donde deberás escribir a un costado los valores que tomaran los siguentes ejercicios:

6 / "3"= esta es una variable numerica, por ende el resultado es 2
"2" * "3"= el resultado es 6 aun que la variable no es numerica
4 + 5 + "px"= el resultado es 9px ya que realiza una suma de variables numericas y la variable px
"$" + 4 + 5= $45 como la primera variable no es numerica lleva  aencadenar todos los elementos
"4" - 2= 2 la primera variable no esta expresada como numerica pero aun asi lo sigue siendo y por eso realiza la resta
"4px" - 2
7 / 0= cualquier numero dividido a 0 da como resultado infinito 
{}[0]
parseInt("09")= si parseInt encuentra un caracter no numeral esfesifico, lo ignora a el y a todos los correctos siguientes, dando el valor entero obtenido hasta este punto el resultado seria 9
5 && 2= 2 ya que regresa el ultimo operador que lo valida como true
2 && 5= 5 este regresa el ultimo operador que valida como true
5 || 0= 5 regresa el primer operador que lo valida como true
0 || 5= 5 no toma el 0 que es false y regresa el primer operador que valida como true
[3]+[3]-[10]= 23 los dos primero se encadenan dado un 3 + 3 y se restan 10 como numero secundario
3>2>1= false ya que true seria 1
[] == ![]el operador ! fuerza a que el resultado sea false ya que es un boleano


Analiza cual sera el resultado de los console.log:

var profesor = "Jhoswe";
let teacher = "Jose";
if (true) {
    var profesor = "The Flash";
    let teacher = "Reverse Flash";
    console.log(profesor); se cambia la variable "the flash"
    console.log(teacher); se cambia la variable "reverse flash"
}
console.log(profesor); the flash
console.log(teacher); jose que se declara dentro del if