# DeStructuring

Obj Destrc.1

console.log(numPlanets);  8
console.log(yearNeptuneDiscovered);  1846
------------------------------------------


Obj Destrc.2

console.log(discoveryYears);
{yearNeptuneDiscovered: 1846, yearMarsDiscovered: 1659}
--------------------------------------------------------


Obj Destrc.3

getUserData({firstName: "Alejandro", favoriteColor: "purple"})
 Your name is Alejandro and you like purple

getUserData({firstName: "Melissa"})
 Your name is Melissa and you like green

getUserData({})
 Your name is undefined and you like green
 ----------------------------------------------------------------------------------------------
 
 
 Array Destrc.1
 
console.log(first);  Maya
console.log(second);  Marisa
console.log(third);  Chi
----------------------------------------------------------------------------------------------

Array Destrc.2

console.log(raindrops);  "Raindrops on roses"
console.log(whiskers);  "whiskers on kittens"
console.log(aFewOfMyFavoriteThings);
 ["Bright copper kettles", "warm woolen mittens", "Brown paper packages tied up with strings"]
 ----------------------------------------------------------------------------------------------
 
 
 Array Destrc.3
 
 console.log(numbers)  [10,30,20]
 ------------------------------------------------------------------------------------------
 
 
 Object Destructuring ES2015-
 
 const obj = {
  numbers: {
    a: 1,
    b: 2
  }
};

const {a,b} = obj.numbers
------------------------------------------------------------------------------------------


One-line Array Swap/ Destructuring-

[arr[0], arr[1]] = [arr[1], arr[0]]
-------------------------------------------------------------------------------------------


Race Results-

const raceResults = ([first, second, third, ...rest]) => ({first, second, third, rest})
------------------------------------------------------------------------------------------
