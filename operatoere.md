# betingede-saetninger-soeren-paepcke
## Operatoere

```javascript
//øvelse 1
var tal1 = 3;
var tal2 = 1337;

//addering
console.log(tal1 + tal2);

//subtraktion
console.log(tal2 - tal1);

//multiplikation
console.log(tal1 * tal2);

//division
console.log(tal2 / tal1);

//modulus
console.log(tal1 % tal2);
//dividerer, og tæller hvor mange gange resultatet går op i det første tal, i det her tilfælde 3

// ++ operator, lægger 1 til

tal1++;
console.log(tal1);

// -- operator, trækker 1 fra

tal1--;
console.log(tal1);

//øvelse 2.1, sætter tal1 til at blive det samme som tal2

tal1 = tal2;
console.log(tal1);

//øvelse 2.2, lægger tal1 sammen med tal2

tal1 += tal2;
console.log(tal1);

//øvelse 2.3, trækker tal1 fra tal2

tal2 -= tal1;
console.log(tal2);

//øvelse 2.4, ganger tal1 med tal2
 
tal1 *= tal2;
console.log(tal1);

//øvelse 2.5, dividerer tal2 med tal1

tal2 /= tal1;
console.log(tal2);

//øvelse 2.6, finder ud af hvor mange gange resultatet af divisionen går op i tal1

tal1 %= tal2;
console.log(tal1);

//øvelse 3, begge betingelser skal være opfyldt her pga. &&

var navn = "Søren Paepcke";
var alder = 27;

if(navn === "Søren Paepcke" && alder == 27){
    console.log("Goddag, gamle dreng");
}
else{
    console.log("Hej, hvad hedder du?");
}

//øvelse 4, blot en af betingelserne skal være opfyldt, pga. || double pipes
var navn = "Søren Paepcke";
var alder = 26;

if(navn === "Søren Paepcke" || alder == 27){
    console.log("Goddag, gamle dreng");
}
else{
    console.log("Hej, hvad hedder du?");
}

```
### Øvelse 5
#### Beskrivelse af forskellige operatoere

* \=   Sætter en værdi eller et udsagn til noget andet

**Eksempel:** x = y


* \==  Sammenligner to værdier eller udsagn med hinanden

**Eksempel:** x == y


* \=== Sammenligner både indhold og datatype for en værdi/et udsagn

**Eksempel:** x === y


* \!   Vender et udtryk om

**Eksempel:** x ! y


* \!=  Hvis noget *ikke* er lig med noget andet

**Eksempel:** x != y


* \!== Hvis det ikke er samme værdi *eller* datatype

**Eksempel:** x !== y


* \<   Mindre end noget

**Eksempel:** x < y


* \>   Større end noget

**Eksempel:** x > y


* \<=  Mindre end, eller lig med

**Eksempel:** x <= y


* \>=  Større end, eller lig med

**Eksempel:** x >= y


* \+   Addering, lægger to værdier eller udsagn sammen

**Eksempel:** x + y


* \-   Subtraktion, trækker to værdier fra hinanden

**Eksempel:** x - y


* \*   Multiplikation, ganger to værdier med hinanden

**Eksempel:** x * y


* \/   Division, dividerer to værdier med hinanden.

**Eksempel:** x / y


* \%   Modulus, dividerer to værdier, og ser hvor mange gange resultatet går op i det første tal

**Eksempel:** x % y


* \&&  Hvis 2 eller flere værdier skal være *true*, bruges disse operatoere.

**Eksempel:** x == z && y == w


* \||  Hvis blot en af 2 eller flere værdier skal være *true*, bruges disse "double pipes"


**Eksempel:** x == z || y == w



Kilde: [W3 Schools](https://www.w3schools.com/js/js_operators.asp)
