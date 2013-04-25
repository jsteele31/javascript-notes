javascript-notes
================

javascript notes
///////////////////

console.log();
Math.random();
String(varible);
Math.floor();
varible.length
varible.SubString(start, end) // 0 _ 1 _ 2 _ <-- index is on the left!
Math.PI;

typeof

ClassName.prototype.method = function () { };

Penguin.prototype = new Animal();

prompt();
confirm();


Object
-> hasOwnProperty( "name" ); // => true / false
///////////////////////////////////

<
>
<=
>=
!==
===

&&
||
! // not

///////////////////////////////////
var array = ["", 2, "22", true];
var twoDimensional = [[1, 1], [1, 1]];

var family = new Array();

///////////////////////////////////

var phonebookEntry = {};

phonebookEntry.name = 'Oxnard Montalvo';

|| 

var myObject = {
    key: value,
    key: value,
    key: value
};

||

var myObj = new Object();

myObj["name"] = "Charlie";
myObj.name = "Charlie";

///////////////////////////////////
for (var i = 0; i < 5; i++)
{

}

///////////////////////////////////
do {


} while (condition);
///////////////////////////////////

var func = function (parameter) {
};

///////////////////////////////////
if ()
else if ()
else


///////////////////////////////////
isNaN('berry') // => true
isNaN(NaN) // => true
isNaN(undefined) // => true
isNaN(42);  // => false
isNaN("42"); // => false

isNaN checks if its a number;
true = not a number
false = a number
///////////////////////////////////

switch (varible)
{
case 'condition':
  break;
default:
  break
}

////////////////////////////////

susan.setAge1 = setAge;
susan.setAge1(35);

var setAge = function (newAge) {
  this.age = newAge;
};

///////////////////////////////////

function Person(name,age) {
  this.name = name; // Public
  this.age = age;
  var bankBalance = 7500; // Private
}

var bob = new Person("Bob Smith", 30);

///////////////////////////////////

function Rectangle(length, width) {
  this.length = length;
  this.width = width;
  this.calcArea = function() {
      return this.length * this.width;
  };
  // put our perimeter function here!
  
}

OR

var obj = {
  age: 22,
  speak: function(blah) {
}
};

////////////////////////////////////
for(var property in dog) {
console.log(property);
}

////////////////////////////////////
Dog.prototype.bark = function() {
  console.log("Woof");
};


