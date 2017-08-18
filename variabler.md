# opstart-soeren-paepcke
## variabler

```javascript
//øvelse 1

var navn = "Søren Paepcke";
var alder = 27;

//besværlig metode med plusser og plinger
var tekst = 'Mit navn er ' + navn + ' og jeg er '+ alder + ' år gammel.';
console.log(tekst);

//smart metode med "back tics" som gør det samme som overstående, bare uden plusser og plinger
console.log(`Mit navn er ${navn} og jeg er ${alder} år gammel`);


//øvelse 2

var moms = 1.25;
var pris_uden_moms = 400;
//lægger moms oven i prisen
var pris_med_moms = moms * pris_uden_moms;
//console.log(pris_med_moms);

//trækker momsen fra igen
var pris_uden_moms2 = pris_med_moms / moms;
console.log(pris_uden_moms2);


//øvelse 3

var forste = 10;
var anden = 20;

//laver en midlertidlig kasse til variablen "forste" som opbevarer tallet 10
var temp = forste;
//bytter værdierne rundt i variablerne
forste = anden;
anden = temp;

console.log(forste, anden);


//øvelse 4.1

var carName = "Volvo";
console.log(carName);


//øvelse 4.2

var number = 50;
console.log(number);


//øvelse 4.3

var carName = "Volvo";
//med fejl i koden
console.log(carname);
//uden fejl i koden
console.log(carName);
//javascript er case sensitive

//øvelse 4.4

var x = 5;
var y = 10;

console.log(x+y);


//øvelse 4.5

var x = 5;
var y = 10;
var z = x+y;

console.log(z);


//øvelse 4.6

var firstName ='John', lastName = 'Doe', age = 35;

console.log(firstName, lastName, "is", age);


```
