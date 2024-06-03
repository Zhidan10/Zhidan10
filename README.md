// ES5
var firstName = 'Sandy'
// ES6
let firstName = 'Sandy'
// Example of the difference
function example() {
  var a = 'a';
  let b = 'b';
  console.log(a,b); // a b
  {
    var c = 'c';
    let d = 'd';
  }
  console.log(c); // c
  console.log(d); // ReferenceError: d is not defined
}
