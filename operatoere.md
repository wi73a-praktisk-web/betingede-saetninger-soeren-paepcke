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
