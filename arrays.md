# opstart-soeren-paepcke
## arrays

//array øvelser 1.1

var cars = ['Saab', 'Volvo', 'BMW'];

console.log(cars);


//array øvelser 1.2

var cars = ['Saab', 'Volvo', 'BMW'];

console.log(cars[1]);


//array øvelser 1.3

var cars = ['Saab', 'Volvo', 'BMW'];
//ændrer det første item i mit array, da de er 0 indekseret, til "Opel"
cars[0] = "Opel";

console.log(cars);


//array øvelser 1.4

var cars = ['Saab', 'Volvo', 'BMW'];

console.log(cars.length);


//array øvelser 1.5

var cars = ['Saab', 'Volvo', 'BMW'];
//tilføjer mercedes til "cars" array'et
cars[cars.length] = "Mercedes";

console.log(cars);


//array øvelser 2
//opretter variabel med 3 arrays inde i, ændrer indholdet i arrays'ne
var personer = [
    hold_1 = ['Benny Bennysen', 'Knud Knudsen'],
    hold_2 = ['Anders Andersen', 'Per Persen'],
    hold_3 = ['Kaj Kajsen', 'Hans Hansen']
];
hold_1[0] = 'Nickolas Nickolasen';
hold_1[1] = 'Sheila Sheilasen';

hold_2[0] = 'Troels Træls';
hold_2[1] = 'Gandalf Gandalfsen';

hold_3[0] = 'Yolo Swaggins';
hold_3[1] = 'Gollum Gollumsen';

console.log(personer);
