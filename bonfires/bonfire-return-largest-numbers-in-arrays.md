#Bonfire: Return Largest Numbers in Arrays
<a href="http://freecodecamp.com/challenges/Bonfire:%20Return%20Largest%20Numbers%20in%20Arrays?solution=function%20largestOfFour(arr)%20%7B%0A%20%20for(var%20i%20%3D%200%3B%20i%20%3C%20arr.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20arr%5Bi%5D.sort(function(a%2Cb)%7Breturn%20b-a%7D)%3B%0A%20%20%7D%0A%0A%2F%2F%20hard-coded%20for%20exactly%20four%20arrays%20as%20asked%20in%20instructions%0A%20%20arr%20%3D%20%5Barr%5B0%5D%5B0%5D%2C%20arr%5B1%5D%5B0%5D%2C%20arr%5B2%5D%5B0%5D%2C%20arr%5B3%5D%5B0%5D%5D%3B%0A%20%20return%20arr%3B%0A%7D%0A%0AlargestOfFour(%5B%5B4%2C%205%2C%201%2C%203%5D%2C%20%5B13%2C%2027%2C%2018%2C%2026%5D%2C%20%5B32%2C%2035%2C%2037%2C%2039%5D%2C%20%5B1000%2C%201001%2C%20857%2C%201%5D%5D%2C%20%22%22)%3B" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10">Return an array consisting of the largest number from each provided sub-array. For simplicity, the provided array will contain exactly 4 sub-arrays.</p><p class="wrappable negative-10">Remember, you can iterate through an array with a simple for loop, and access each member with array syntax arr[i] .</p><p class="wrappable negative-10">If you are writing your own Chai.js tests, be sure to use a deep equal statement instead of an equal statement when comparing arrays.</p><p class="wrappable negative-10">Remember to use <a href="//github.com/FreeCodeCamp/freecodecamp/wiki/How-to-get-help-when-you-get-stuck" target="_blank">Read-Search-Ask</a> if you get stuck. Write your own code.</p><div class="negative-30-bottom"><div id="MDN-links"><p class="negative-10">Here are some helpful links:</p><div class="negative-10"><ul><li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators" target="_blank">Comparison Operators</a></li></ul></div></div></div>


####Answer:
```javascript
function largestOfFour(arr) {
  for(var i = 0; i < arr.length; i++) {
    arr[i].sort(function(a,b){return b-a});
  }

// hard-coded for exactly four arrays as asked in instructions
  arr = [arr[0][0], arr[1][0], arr[2][0], arr[3][0]];
  return arr;
}

largestOfFour([[4, 5, 1, 3], [13, 27, 18, 26], [32, 35, 37, 39], [1000, 1001, 857, 1]], "");
```