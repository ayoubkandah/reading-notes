
Pure Function :
-Same inputs always return same outputs
pureFun
const add = (x, y) => x + y;

add(2, 4)

notPureFun
let x = 2;

const add = (y) => {
  x += y;
};

add(4)

paramater A return val B
-No side-effect

immutable 
-The value it returns is dependent on the input passed. The returned value will not change as long as the inputs do not change.
-It does not change things outside of its scope.

 First-class functions
ex const test= function() {
   console.log("hi ayoub");
}
// Invoke it using the variable
test= ();

Filter : it return an array with values thats return true .
Map : it return an array with values can be updating or changing .
reduce :it return total ammount of array
