Array.map() : method creates a new array with the results of calling a function for every array element.


Array.reduce() :reduce() method reduces the array to a single value,return the value of the function stored in acc.

superagent using then

superagent().get(API).then(Result =>{ log(Result)  }) //-- it will return JSON from API

superagent using async and await

async function data(){
    let promise = superagent.get(url);

 let Result= await promise

log(Result) //-- it wil wait untill the promise end and return the JSON from API
}

explain the promise 
promise in js it like promise in real life for ex :
when you order something in amazon , the order is the [Promise]
and when you get the order is a [future value]

Asynchronous in js

no , Asynchronous in js (promises and async/await) like when you req data from api it will take the time so the asynchronous it come to fix that.

but, the js is a single-threaded programming language which means only one thing can happen at a time. so other functions not Asynchronous.
