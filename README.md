Whack-A-Mole
===================
Two factors determine what a React Component renders:

 1. Props - properties passed into the component from it's parent.
 2. State - the internal state of a component

If you haven't already, read the [React docs](https://facebook.github.io/react/docs/hello-world.html) to get a better sense of these two concepts.

In this challenge, we'll be building a [Whack-A-Mole](https://en.wikipedia.org/wiki/Whac-A-Mole) game - this exercise will serve as a gentle introduction to state and props.  

The game "engine" has already been created.  The state of the top-level component, App.js, contains two items:

 1. **dens** - an array of objects that are a representation of the "holes" in the whack-a-mole game.
 2. **points** - an integer that contains the number of times a mole was whacked/clicked.

Inspect App.js and attempt to understand the game engine logic - this may help you in achieving the objectives.

Objectives
-------------

 1. Modify the props that are passed into Mole.js and the Mole.js component itself so that the Mole image only appears when the **isMoleVisible** property of the appropriate **den** object is set to true.
 2. Modify Mole.js so that points are incremented whenever a visible mole is clicked.
 3. Add comments to the _startGame(), _getDensState(), and _onMoleWhacked() methods that explain what the code is doing.


> Squirrel by Pirog tetyana from the Noun Project

