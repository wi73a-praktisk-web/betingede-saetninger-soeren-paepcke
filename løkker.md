# opstart-soeren-paepcke
## Løkker i javascript

```javascript
//Løkker, del 1, øvelse 1.1

var omgange = 10;
do{
    if(omgange == 1){
        console.log("Der er kun " + omgange + " omgang tilbage.");
        omgange--;
    }
    else if(omgange > 1){
        console.log("Der er stadig " + omgange + " omgange tilbage!");
        omgange--;
    }
    else if(omgange == 0){
        console.log("Løbet er færdig!");
        omgange--;
    }
}
while(omgange >= 0);

//øvelse 1.2

var condition = 1;
//while løkke
while(condition <= 25){
    console.log(condition);
    condition++;
}

//do.while løkke
do{
    console.log(condition)
    condition++;
}while(condition <= 25);

//for løkke
for(var condition = 1; condition <= 25; condition++){
    console.log(condition);
}

//øvelse 3
for(var from_year = 2017; from_year >= 1917; from_year--){
    console.log(from_year);
}
```

### Beskrivelse af en "for-løkke"

```javascript
//øvelse 4, beskrivelse af en "for løkke"
for(var taeller = 1; taeller < 10; taeller++){
    console.log(taeller);
}
```
I grove træk kan man sige, at der er 3 "ingredienser" i en "for-løkke" gryderet:

* Først en variabel med en værdi af 1
* Bagefter en betingelse, hvor "tæller" variablen skal være mindre end 10
* Hver gang dette bliver udført, skal den lægge +1 til tælle-variablen.

Så man kan oversætte koden til:
**så længe(var tal = 1; tal < 10; tal + 1){**

    *skriv i konsollen(tal);*
    
**}**
