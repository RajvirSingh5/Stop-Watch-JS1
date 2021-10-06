<h1>Stop Watch Mini Project</h1>

This was created in reference to JS Mini Project 1 requirement.


I have used html, css and vanila javascript.

Html file : index.html

css :  stopwatch.css

Javascipt:  stopwatch.js



The code renders a stopwatch on modern browsers with three control buttons.


The three contorl buttons are start, stop reset.



<h2>Variables in JS file</h2>

hours = hr

Minutes = min

Seconds  = sec

stoptime : boolean flag to check if stopwatch is stopped or not



<h2>Functions used</h2>

**Function startTimer** :   fucntion to start timer when 'Start' button is clicked.

**Function stopTimer** :  fucntion to stop timer when 'stop' button is clicked

**Function timerCycle** : TimerCycle() is called after every 1000ms (1 sec) using setTimeout.
If seconds are more than 60, minutes become 1 and seconds 0.
Similarly if minutes are more thant 60, hours become 1 and minutes 0.

**Function resetTimer** : fucntion to reset timer when 'reset' button is clicked

