# codes-and-data

//Create OBJECT                                          

let person = {

  name: "Alice",

  age: 25,

  city: "Bengaluru"

};
 
//access

console.log("Name:", person.name);
 
//Adding or updating 

person.age = 26;            

console.log("Updated age:", person);
 
// Deleting 

delete person.city;

console.log("After Deleting city:", person);
 
 
 
///Create ARRAY

let numbers = [10, 20, 30, 40, 50];
 
//Acess

console.log("First number:", numbers[0]);  
 
//Adding elements

numbers.push(60);       // Add to end

numbers.unshift(0);     // Add to start

console.log("After adding:", numbers);
 
// Removing elements

numbers.pop();          // Removes last

numbers.shift();        // Removes first

console.log("After removing:", numbers);
 
 
LARGE DATA

//for loop

let largeArray = Array.from({ length: 10000 }, (_, i) => ({ id: i, value: i * 2 }));

for (let i = 0; i < largeArray.length; i++) {

    largeArray[i].value += 1; 

}
 
 
//for of 

for (const item of largeArray) {

    item.value += 1;

}
 
//for each

largeArray.forEach(item => item.value += 1);
 
 
//access and edit

for (const key in largeObject) {

    if (Object.hasOwnProperty.call(largeObject, key)) {

        largeObject[key] += 10;

    }

}

 
///Using map

//GET(Large data)

let map = {};

data.forEach(item => {

map[item.id] = item;

});

console.log(map[2].name);//get data
 
//SET using map

data.forEach(item => {

if (item.name = "xyx Updated";

}

});
 
//add new data

data.push({1;2, n:t});

data[2] = {1:2, n:t};
 
//delete

data = data.filter(item => item.id !== 2);

delete data[2];
 
 
 
///Using LOOP

//create

let data = [];

for (let i = 1; i <= 10000; i++) {

data.push({

id: i, name:'t' +  i});

}
 
 
I want data 1st 5000(using .slice, .filter)

//.slice

let first5000 = data.slice(0, 5000);

console.log(first5000);
 
//GET (particular id = 5000)

let result = null;

for (let i = 0; i < data.length; i++) {

if (data[i].id === 5000) {

result = data[i];

break;

}}

console.log(result);
 
//SET/UPDATE

for (let i =0; i < data.length; i++) {

if (data[i].id === 5000) {

data[i].name = "Updated user5000";

break;

}

}
 
//ADD

data.push({

id:10001,

name:"Teju"
 
//DELETE

for (let i = 0; i < length; i++) {

if (data[i].id === 5000) {

data.splice(i, 1);}}
 
 
///Nested LOOP

//Str

let data = [];

for (let i = 1; i < = 10000; i++) {

data.push( {

id: i,

name:"Teju" + i

});

}
 
//GET

let result = null;

for (let i = 0; i < data.length; i++) {

for (let j = 0; j< 1; j++) {

if (data[i].id === 5000) {

result = data[i];

break;

}}

if (result) break;

}

console.log(result);
 
//SET

for (let i = 0; i <data.lenghth; i++) {

for (let j = 0; j < 1; j++) {

if (data[i].name = "Updated TejuP";

break;}}

if (data[i].id === 5000) break;}
 
//DELETE(EX id = 102 inside id = 1)

for (let i = 0; i < data.length; i++) {

if (data[i].id === 1) {

for (let j = 0; j < data[i].users.length; j++) {

if (data[i].users[j].id === 102) {

data[i].users.splice(j, 1);

break;

}}

break;}}
 
//ADD

for (let i = 0; i <data.length; i++) {

if (data[i].id === 1) {

data[i].users.push({

id: 103,

name: "TejuP"

})'

break;

}}
 
 
 

numbers. Unshiftnumbers. Pushnumbers. Popnumbers. Shiftitem. Valueitem. Value 
