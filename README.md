# Wordle

This is a clone of the popular game Wordle. Made with React library

# Run it locally

1. Install [Node.js](https://nodejs.org/en/)
2. In the directory of the project run `npm install`
3. Run command `json-server ./data/db.json --port 3001` . It allows to fetch data from the local JSON server
4. In another terminal run `npm run start`. It will open the app automatically


# How to play the game

1. Type a 5-letter word and press enter
2. If you guessed the correct letter with a correct order it will appear green
3. If the letter is in the solution but in another place it will appear yellow
3. If there is not a letter in the solution it will be gray.

You have 6 guesses. Good luck!
