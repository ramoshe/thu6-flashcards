#The Challenge

When our users are studying flashcards, they will likely want to try to guess the answer before they see the hint, and then show the hint if they get stuck. The challenge is to write some JavaScript to hide the hint by default and present a button the user can click to reveal the hint.

##Setup
You can serve JavaScript files from the public folder, the same way you're doing with CSS.
 1. Create a new folder in public, next to stylesheets, and name it js.
 2. Inside, create a new file called app.js. This is where you'll write the client-side JavaScript.

##Writing the Feature
You'll need to:
 - Hide the hint.
 - Create and append a button element to the DOM.
 - Add an event listener to the button to unhide the hint when the button is clicked.
 - Also, make sure the code only runs on the question side of the flashcard.

Below is a snippet of HTML for use as a guide to what structure the DOM should have after it's manipulated. Try to match this if you want the page to be styled correctly.
```
<div id="content">
  <h2>What is one way a website can store data in a user's browser?</h2>
  <button>Show hint</button>
  <p class="hint" style="display: none;"><i>They are delicious with milk</i></p>
</div>
```


#Additional challenges
 - Create additional flashcard sets 
     - diff themes like Astronomy
 - connect to a database
     - to get flashcard info
 - add users/authentication