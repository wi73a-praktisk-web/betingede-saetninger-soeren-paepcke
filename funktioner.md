# opstart-soeren-paepcke
## funktioner

```javascript
//opvarmningsøvelse, simpel funktion

function hello(){
    console.log("Hello!");
}
hello();

//hoisting øvelse, javascript kan kalde funktioner både før og efter de bliver erklæret
sayHello('javascript hoisting');

function sayHello(who){ //argumentet "who" overfører en værdi
    console.log("Hello", who);
}

sayHello("Søren Paepcke!");

//hvis funktionen ligger i en variabel, virker hoisting ikke, så skal kaldet ligge under funktionen

sayYo('test for hoisting?'); //sayYo variablen bliver kaldt før den er erklæret, så det virker ikke

var sayYo = function sayHey(value){
    console.log(value);
}


//øvelse 1.A

profileData('Søren', 'Paepcke', 290390);
//funktionskald('værdi', 'værdi', tal-værdi)

function profileData(name, lastName, birthDay){ //funktion funktionsNavn(argument, argument, argument)
    console.log(name, lastName, birthDay); //console.log(argument, argument, argument)
}


//øvelse 1.B, regne funktioner, regner ud individuelt

function plus(num1, num2){
    console.log(num1 + num2);
}
plus(10, 2)

function minus(num1, num2){
    console.log(num1 - num2);
}
minus(10, 2);

function gange(num1, num2){
    console.log(num1 * num2);
}
gange(10, 2);

function division(num1, num2){
    console.log(num1 / num2);
}
division(10, 2);


//regnefunktioner, med result variabel, regner videre på resultatet

var result = 0;

function add(num){
    result += num;
}
add(10);

function sub(num){
    result -= num;
}
sub(5);

function mul(num){
    result *= num;
}
mul(4);

function div(num){
    result /= num;
}
div(5);

result = console.log(result);


//pi
var sum = 100;

function piBeregner(){
    console.log(Math.PI * sum);
}
piBeregner();

//kvadratrod

var nogleTal = 9;
var resultat = Math.sqrt(nogleTal);

function kvadratrodBeregner(){
    console.log(resultat);
}
kvadratrodBeregner();

//anonym funktion, kalder på variablen istedet

var helloAnon = function(value){
    console.log(value);
}
helloAnon('Den anonyme funktion, 2 spooky 5 me!');


//arrow function expression, function uden at skrive "function", => erstatter ordet

var sayWhat = value => console.log(value);

sayWhat('Hvad er dette for noget sort magi?');

//argumenter og default values

function add(x = 0, y = 0){
    console.log(`X er lig med ${x} og y = ${y}. Sum: `, x + y);
}
add();       //udskriver "X er lig med 0 og y = 0. Sum: 0"
add(10, 90); //udskriver "X er lig med 10 og y = 90. Sum: 100"


//øvelse 2, afkortning af string

var forkortDetHer = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce quis lectus quis sem lacinia nonummy. Proin mollis lorem non dolor. In hac habitasse platea dictumst. Nulla ultrices odio. Donec augue. Phasellus dui. Maecenas facilisis nisl vitae nibh. Proin vel seo est vitae eros pretium dignissim. Aliquam aliquam sodales orci. Suspendisse potenti. Nunc adipiscing euismod arcu. Quisque facilisis mattis lacus. Fusce bibendum, velit in venenatis viverra, tellus ligula dignissim felis, quis euismod mauris tellus ut urna. Proin scelerisque. Nulla in mi. Integer ac leo. Nunc urna ligula, gravida a, pretium vitae, bibendum nec, ante. Aliquam ullamcorper iaculis lectus. Sed vel dui. Etiam lacinia risus vitae lacus. Aliquam elementum imperdiet turpis. In id metus. Mauris eu nisl. Nam pharetra nisi nec enim. Nulla aliquam, tellus sed laoreet blandit, eros urna vehicula lectus, et vulputate mauris arcu ut arcu. Praesent eros metus, accumsan a, malesuada et, commodo vel, nulla. Aliquam sagittis auctor sapien. Morbi a nibh.";
var stringForkorter = forkortDetHer.substring(0, 20); //substring (startposition, slutposition)

console.log(stringForkorter);

//øvelse 3

//henter den nuværende dato
var currentDate = new Date();
//henter kun det nuværende år
var currentYear = currentDate.getFullYear();

var profil = function(profilData){
    return  "Fornavn: " + profilData[0] +
            ".\nEfternavn: " + profilData[1] +
            ".\nFødt i året " + profilData[2] +
            ".\nEr " + currentAge + " år gammel" +
            ".\nEr født i " + profilData[3] +
            ".\nHan elsker desuden at " + profilData[4];
}

var minProfil = ["Søren", "Paepcke" , 1990, "Norge", "nørde."];
//trækker det nuværende år fra året jeg er født
var currentAge = currentYear-minProfil[2];

console.log(profil(minProfil));


//øvelse 4

function calculator(){

    var result = 0;

    return {
        //addering
        add: function(x){
            result += x;
        },
        //subtraktion
        sub: function(x){
            result -= x;
        },
        //multiplikation
        mul: function(x){
            result *= x;
        },
        //division
        div: function(x){
            result /= x;
        },
        //pi
        pi: function(x){
            result *= Math.PI;
        },
        //kvadratrod
        squ: function(x){
            result = Math.sqrt(result); 
        },
        result: function(){
            return result;
        }
    }
}

var calc = calculator();

calc.add(2);
calc.add(5);
calc.add(3);
calc.sub(4);
calc.mul(5);
calc.div(3);
calc.pi();
calc.squ();

console.log(calc.result());
```
