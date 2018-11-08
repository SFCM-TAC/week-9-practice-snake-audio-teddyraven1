The code you find here is a game of Snake implemented in p5.js that I stole from their website (they have a lot more examples here: https://p5js.org/examples/). The gameplay code is in 'snake.js'. Your assignment is to add sound to the game using either Tone.js or p5.sound.js (both libraries are included for you already in the js folder so you don't need to download them).

This assignment is an exercise in reading and understanding code, and in using open source libraries. You'll need to look at their references to figure out what functions and objects to use to load and play sounds.

P5.js reference: https://p5js.org/reference/
P5.sound.js reference: https://p5js.org/reference/#/libraries/p5.sound˝
Tone.js reference: https://tonejs.github.io/docs/
Our Tone.js code from class a week ago: https://github.com/SFCM-TAC/week7-inclass-tonejs

Be as creative as you want, but for the purposes of grading this assignment you need to at least implement:
1. A looping background song or ambience
2. A sound when the snake successfully eats a fruit
3. A 'game over' sound
(Don't worry about making perfect sound assets, I'm not grading on that - you can create your own sounds, use found sounds, or use the synth capabilities in the libraries.)

Additionally, make at least one modification to the gameplay to make it your own. Ideas:
* Speed up the snake after eating a certain number of fruits
* Change the snake's color every time it eats a fruits
* Randomize the size of the fruit


Reminder, if you use sound files, you may need to run your code on a server in order to load them. Instructions:

1. Open the 'terminal' application on your mac
2. Type 'cd /Path/to/parent/folder' and hit enter to navigate to your app folder (you can also drag a folder into the command prompt to have it auto-fill the path)
3. Type 'python -m SimpleHTTPServer 8000' in the terminal to start the local server
4. Go to localhost:8000 in your browser to load your web app!
5. It should load changes to your files automatically, but if you need to restart the sever: press 'ctrl+C' in the terminal to stop the server. Run 'python -m SimpleHTTPServer 8000' again to restart it with your changes.
