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
