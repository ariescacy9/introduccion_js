# Desafío: INTRODUCCION JS

## Instrucciones

### llamado `introduccion_js` donde deberás escribir a un costado los valores que tomaran los siguentes ejercicios:

6 / "3"  // daria como resultado 2 porque js trata como numeros al ser inteligente
"2" * "3" // igual se multiplican y saldria 6 en entero
4 + 5 + "px" // se suman ambos numeros y se concatena con la cadena 9px
"$" + 4 + 5 // igual se cncatenan y se suman los numeros $9
"4" - 2 // daria como resultad 2 pues se tratan como numeros ambos
"4px" - 2 //  creo que daria como resultado indefinido
7 / 0 // igual indefinido supongo
{}[0] // nan 
parseInt("09") // convierte a numero entero supongo
5 && 2 // true a falta de condiciones
2 && 5 // true a falta de condiciones
5 || 0 // true a falta de condiciones
0 || 5 // true a falta de condiciones
[3]+[3]-[10] // -[4] creo
3>2>1 // true
[] == ![] // false 


//Analiza cual sera el resultado de los console.log:

var profesor = "Jhoswe";
let teacher = "Jose";
if (true) {
    var profesor = "The Flash";  // se le trata de asignar otra cadena a la variable profesor
    let teacher = "Reverse Flash"; // se le asigna la cadena "Reverse Flash"
    console.log(profesor); // como es falso no ejecutaria el consol log por que es una variable global y no cambia
    console.log(teacher); // imprime la nueva cadena asiganda "Reverse Flash"
}
console.log(profesor); // imprime la cadena "Jhoswe" por que es una variable global y no cambia
console.log(teacher); // imprime la cadena "Jose"