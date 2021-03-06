# Brogrammer Hangman
A console-based hangman Node.js app that incorporates objects, user-input, and constructors. Keeping on the theme of a command line application, all the words to be guessed are programming languauges (or frameworks). Start building up your Brogrammer lexicon now!

The app uses the `inquirer` node module to collect user inputs.

No cheating! All of the words that can be guessed are in the `game.js` file.


# Instructions
Unfortunately, since this is a command line application, it must be cloned down to your machine to be demoed. After cloning down the repo to your computer, `cd` into the `Week11-Hangman` folder and run `npm install` to download all the node dependencies.

Once the node dependencies are installed, you can run the app by calling `node main.js` in your console.

The game will last for the duration of 1 word. After you either win or lose, the program exits. Run `node main.js` each time you wish to guess a new word.


# Screenshots

### Winning Scenerio (word is guessed)
![Winner](/screenshots/winner.png)

### Losing Scenerio (word not guessed after 10 letters entered)
![Loser](/screenshots/loser.png)

### Snarky Comment 1 (You cannot guess the same letter twice)
![Double Guess Prompt](/screenshots/double guess.png)

### Snarky Comment 2 (You must guess a letter, no numbers or special characters)
![Not a letter Prompt](/screenshots/not a letter.png)