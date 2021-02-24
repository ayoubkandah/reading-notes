A call stack is a mechanism to track multiple function.

when we invoke function the call stack will ignore all functions and run the function thats we invoked.

 if the call stack not exist we have to put function in order to run without any erors like this 
function firstFunction(){
--------------------------
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();


------------------------------
third function couldnt run first function because first function will pop before invoked third function 

but in call stack it will work.


Error msg its indecator for our default .
Reference errors : when we use var or func thats not declared or used it before declare

Syntax errors its about syntax like ( or , or } ...etc

Debugging : its a best practice to track a code and to know exactly where is the error or we can 
use debugging to know if our if statement or loop stat or func stat is correct or the code run inside it 
