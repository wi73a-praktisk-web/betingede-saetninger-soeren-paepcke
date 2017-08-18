# betingede-saetninger-soeren-paepcke
## Betingelser

```javascript
//øvelse 1

var betingelse = false;

if (betingelse == true){
    console.log('Hej verden');
}
else {
    console.log('Farvel verden!');
}

//øvelse 2
//genererer et random tal mellem 0-10, begge inkluderet

var random_tal = Math.floor(Math.random() * 11);

if (random_tal > 5){
    console.log('Tallet er større end 5! Tallet er ' + random_tal);
}
else if(random_tal == 5){
    console.log('Tallet er 5!');
}
else{
    console.log('Tallet er mindre end 5. Tallet er ' + random_tal);
}

//øvelse 3

var random_tal = Math.floor(Math.random() * 11);

var result = random_tal > 5 ? 
    //hvis udsagnet er sandt, udføres dette
    "Haha. Tallet er størrere end 5! Tallet er " + random_tal :
    //hvis udsagnet IKKE er sandt, udføres dette
    "Haha. Tallet er mindre end 5! Tallet er " +  random_tal;
console.log(result);

//øvelse 4

var drink = "Pepsi Twist";

if(drink == "Pepsi Twist"){
    console.log('Ahhh, det var godt.');
}
else if(drink == "Harboe Cola"){
    console.log("Hmm, billigt men det er OK.");
}
else if (drink == "Saftevand"){
    console.log("Bedre end ingenting. :)");
}
else{
    console.log('Jeg er stadig tørstig ! :(');
}

//øvelse 5

var drink = "Carlsberg";

switch (drink){
    case "Pepsi Twist":
        console.log("Ahh, det var rart.");
        break;
    case "Carlsberg":
        console.log("Uha, den er også god!");
        break;
    case "Saftevand":
        console.log("Bedre end ingenting! :)");
        break;
    case "Juice":
        console.log('Sundt og lækkert !');
        break;
    //hvis intet af det overstående er sandt, udføres dette
    default:
        console.log("Jeg er stadig tørstig!");
        break;
}
```
### øvelse 6, beskrivelse af if/else sætninger

En if/else sætning, er en betinget sætning, som kan direkte oversættes til "hvis/ellers" på dansk, eksempel:
```javascript
//husk alle tegnene, især de runde paranteser og de krøllede
if("Søren" == "sej til javascript"){
    console.log('Fortsæt den gode stil!');
}
else{
    console.log('Læs op på emnet derhjemme!');
}
```
Denne lille if/else sætning har én betingelse, hvor den ser på om jeg er sej til javascript.

Hvis jeg er det, udskrives der "Fortsæt den gode stil" i konsollen, og hvis jeg ikke er det, skal jeg læse op på det derhjemme.

Betingelsen kan komme fra alt muligt, men i det her tilfælde blot to "strings"/"tekst".

Det er **meget vigtigt** at man husker alle tegnene i en if/else sætning, ligesom det er med javascript generelt.

I en if/else *skal* der være mindst én betingelse, som kan være enten sand eller falsk, hvorefter koden enten udføres eller gør noget andet.

Desuden *skal* if/else skrives med småt, da det er reserverede ord i javascript, så hvis man skriver **If** eller **IF** vil man få en fejl.

Man kan også have "else if" sætninger, imellem "if" og "else" sætningerne, hvis man har flere ting man vil tjekke for, eller for at give flere tilbagemeldinger til brugeren af ens website, f.eks. 
