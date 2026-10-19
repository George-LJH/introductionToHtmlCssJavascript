


I started building these projects to learn web development and explore both frontend and backend. Each project was chosen for a specific reason:

* Calculator: This is my first project when learning any new programming language.
* Number Guessing Game: This was one of the very first things I ever coded when I started with Python.
* Stopwatch: As a fan of Rubik's cubing, I wanted to build a timer.
* API Call Integration: I wanted to connect Ntfy with my microcontrollers to send alerts to my device whenever the mailman arrives.
### How It works
#### Calculator
* Get the user input using getElementById
* Add them together
* Display it on screen
#### Number Guessing Game
* Have 4 variables; min, max, guess, and answer
* the answer contains the number the user should guess for, and it is made using a random integer generator provided by [Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random), min and max is the number range of the answer, at the start min and max is 0 and 100, respectively
* whenever the user guesses, update the variable guess, and if the user's guess below the answer, set guess to min, but if it is larger, set it to max. If the guess is equal to the answer, then tell the user they guessed the correct number
* This project is my first project that used [panic-overlay](https://github.com/xpl/panic-overlay)
#### Stopwatch
* This project is the first project where I used Grid.Js
* It uses a couple of functions, like one to load the time, one to show/hide the menu, and one to get the time/date.
* It is also on of my more styled projects.
