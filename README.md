## wonder-the-word-game

I took every english word (over 200k words) and built a little NodeJS.
app to play with words that contain specific characters.

##How to Use

###The underscore

This character is great for games like What's the Phrase (a knock off
of Wheel of Fortune)

Type a word into the text box with the following pattern:

    st___

and you'll get a word from words matching with our pattern.
Few words matching our pattern:
    stack
    stade
    staff
    stage
    stagy
    start

but you will get only one word and you have to guess it first before hitting enter:
For instance, you may get:

    start

If you guessed it at the first place. Buddy you won. You can play with it with your friends to increase vocablary.

##Instructions for running

Go to http://nodejs.org and install NodeJS

Clone the repo: git clone git@github.com:GargPrince/wonder-the-word-game.git

And `cd` into the directory (all instructions below assume you are in
the `wonder-the-word-game` directory:

    cd wonder-the-word-game

##Run Locally

Install all the dependencies:

    npm install (you may need to prefix this with sudo if you're on Mac)

Run the app:

    node server.js

Consider using the package `nodemon` if you'd like. It'll auto start your server
every time you save.

    npm install nodemon -g
    nodemon server.js

Then navigate to `http://localhost:3000`
