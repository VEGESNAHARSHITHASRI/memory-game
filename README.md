#Memory Game Lab

You're going to create a Javascript memory game on a subject of your choice(web frameworks, dog breeds, etc.) See the example gifs at the bottom of the page for inspiration.

### Instructions

The starter project has some HTML and CSS styling to display a static version of the Memory Game project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.

To get started, open `js/app.js` and start building out the app's functionality

For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

### Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).


####Bonus Features

    Add a card-flipping animation when the user clicks a card


###How It Works

   If you're unfamiliar with the game, the rules are very simple; flip over two hidden cards at a time to locate the ones that match!

    The game board consists of sixteen cards arranged randomly in a grid. The deck is made up of eight different pairs of cards, each with different symbols on one side. Each turn:

    A player flips one card over to reveal its underlying symbol
    The player then turns over a second card, trying to find the corresponding card with the same symbol
    If the cards match, both cards stay flipped over
    If the cards do not match, both cards are returned to their initial hidden state

      The game ends once all cards have been correctly matched.
###What Will I Learn?

The memory game presents the first opportunity to fully combine HTML, CSS, and JavaScript into a large project. Aside from solidifying your skills with these three technologies, you'll learn how best to combine them in a complex application. What's the ideal workflow? How many files do you need? Do you write the HTML first? The JavaScript?


###Hints

    We recommend starting off working on a very simple grid of cards. Don't worry about styling, just get something clickable on the page
    Figure out how each card is structured. Remember, you have to represent two sides of the card. Are you going to have two separate elements stacked on top of each other?
    Once you have a grid, add in the click logic to reveal the hidden side of each card
    Next, work on the matching logic. How does your game "know" if a player guesses correctly or incorrectly?
    We recommend saving styling until the very end. Allow your game logic and functionality to dictate the styling.

###Credits

    memory-game
