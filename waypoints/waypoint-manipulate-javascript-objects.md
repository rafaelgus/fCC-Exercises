#Waypoint: Manipulate JavaScript Objects
<a href="http://freecodecamp.com/challenges/Waypoint:%20Manipulate%20JavaScript%20Objects?solution=%2F%2F%20var%20ourDog%20%3D%20%7B%0A%2F%2F%20%20%20%22name%22%3A%20%22Camper%22%2C%0A%2F%2F%20%20%20%22legs%22%3A%204%2C%0A%2F%2F%20%20%20%22tails%22%3A%201%2C%0A%2F%2F%20%20%20%22friends%22%3A%20%5B%22everything!%22%5D%0A%2F%2F%20%7D%3B%0A%0A%2F%2F%20ourDog.bark%20%3D%20%22arf!%22%3B%0A%2F%2F%20delete%20ourDog.tails%3B%0A%0Avar%20myDog%20%3D%20%7B%0A%20%20%20%22name%22%3A%20%22Camper%22%2C%0A%20%20%20%22legs%22%3A%204%2C%0A%20%20%20%22tails%22%3A%201%2C%0A%20%20%20%22friends%22%3A%20%5B%5D%0A%7D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%2F%2F%20Let%27s%20add%20the%20property%20bark%20to%20myDog%0AmyDog.bark%20%3D%20%22true%22%3B%0Adelete%20myDog.tails%3B%0A%0A%2F%2F%20Now%20delete%20the%20property%20tails%0A%0A%0A%2F%2F%20Only%20change%20code%20above%20this%20line.%0A%2F%2F%20We%20use%20this%20function%20to%20show%20you%20the%20value%20of%20your%20variable%20in%20your%20output%20box.%0A(function(z)%7Breturn%20z%3B%7D)(myDog)%3B%0A" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10">There are many ways to add and remove properties from objects.</p><p class="wrappable negative-10">For example, we can add properties to objects like this:</p><p class="wrappable negative-10"><code>myObject.myProperty = &quot;myValue&quot;;</code></p><p class="wrappable negative-10">We can also delete them like this:</p><p class="wrappable negative-10"><code>delete myObject.myProperty;</code></p><p class="wrappable negative-10">Let&apos;s add the property <code>&quot;bark&quot;</code>, and delete the property <code>&quot;tails&quot;</code>.</p><div class="negative-bottom-margin-30"><div id="MDN-links"><p class="negative-10">Here are some helpful links:</p></div></div>


####Answer:
```javascript
// var ourDog = {
//   "name": "Camper",
//   "legs": 4,
//   "tails": 1,
//   "friends": ["everything!"]
// };

// ourDog.bark = "arf!";
// delete ourDog.tails;

var myDog = {
   "name": "Camper",
   "legs": 4,
   "tails": 1,
   "friends": []
};

// Only change code below this line.

// Let's add the property bark to myDog
myDog.bark = "true";
delete myDog.tails;

// Now delete the property tails


// Only change code above this line.
// We use this function to show you the value of your variable in your output box.
(function(z){return z;})(myDog);

```