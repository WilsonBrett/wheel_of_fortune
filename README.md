# Before and After Game
## General Assembly Final Class Project

This single page application was my final project in General Assembly's web development immersive course. It is modeled after the TV game show Wheel of Fortune. This project utilized Bootstrap, AngularJS, jQuery, and CSS primarily. It has a NodeJS backend but the application hasn't been fully built out yet to make use of cookies, sessions, and other routes. The letter board is generated using two ng-repeats which are styled with CSS.  When the page loads initially a phrase is mapped to the board using AngularJS and a user can submit letters one at a time to be matched against the phrase. The user gets 500 points for each letter matched and a -500 when a letter isn't found. The matching code and scoring are done with jQuery and CSS

When the new game button is clicked the AngularJS data layer grabs a new phrase from an array of phrases and maps that to the board without a full page refresh. The game phrase can also be revealed by clicking the reveal button and an exit button, when clicked, is meant to log a user out. I have a MongoDB set up with  phrases in it and would like to connect to it from AngularJS on page load but this is a feature yet to be implemented. Please enjoy the game as it stands so far and happy guessing!
