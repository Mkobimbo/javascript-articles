EVENTS AND EVENT LISTENERS EXPLAINED TO A DUCK quack quack!!
#
javascript
#
beginners
#
webdev
#
tutorial
Prerequisites
Knowledge of HTML
Javascript functions

Introduction
Hello there! my duck friends, imagine floating in the middle of a pond or lake, taking in the cool breeze and enjoying the sunshine. Think of event listeners as your ability to notice things happening to you.

let's say you are floating close to the shores and someone throws in some tasty pieces of bread. When those pieces of bread hit the water you react by swimming towards them quickly. those pieces of bread hitting the water are events and your reaction toward them is similar to how event listeners work.

So we can say events are things that happen in your programming system e.g. a user selects, clicks, or hovers the cursor over an element. Either pausing, playing, or ending a video. An event listener is a block of code in JavaScript that waits for an event to occur and then responds to it.

Quack-tastic event listeners for ducky ducks.
Paying Attention
Just like you pay attention to the pieces of bread hitting the water, event listeners focus on specific things happening on a webpage, like a click or a key being pressed.

Reacting to Events
When someone throws pieces of bread, you immediately swim towards them, right? Similarly, when an event happens on a web page (like a click on a button), the event listener reacts by doing something—like making the page do a fun animation or changing the color of an element.

Different Types of Events
Just as there can be different things happening around the pond (like kids playing, birds chirping, etc.), event listeners can listen for various events: clicks, mouse movements, keyboard presses, and more.

Listening Skills
You're not only attentive to just one type of bread; you react to any kind of bread someone tosses your way. Event listeners are flexible—they can listen for different types of events on various elements of a webpage.

Ready, Set, React!
Imagine someone threw bread near your pond but not directly at you. You'd notice it and swim over, right? That's like event bubbling in JavaScript—events start from a specific element and can affect its parent elements, too.

Event listener example

in our code below,
The HTML file contains a button element with the ID "myButton".

In the JavaScript file, we select the button using document.getElementById.

We define a function changeText() that changes the text content of the button to 'Good ducky!'.

We attach an event listener to the button using addEventListener. This listener listens for a 'click' event on the button and triggers the changeText() function when the button is clicked.

When you open this in a web browser, clicking the button will change its text from "Say Quack!" to "Good ducky!".
<body>

  <button id="myButton">Say Quack!</button>

  <script src="script.js"></script>
</body>
const button = document.getElementById('myButton');

function changeText() {
  button.textContent = 'Good ducky!';
}

button.addEventListener('click', changeText);

and there you have it, have a quack-tastic day my duckie friend.