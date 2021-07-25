# egg-catcher-game
How To Create An Egg Catcher Game using Python?
An egg catcher game tests your concentration and the speed of your reflexes as you have to catch eggs falling all around the screen with one basket. To create an egg catcher game you have to design an animation of falling eggs at random positions and a basket will be catching all the falling eggs.

To create an eggs catcher game using Python, your first step will be to design a floor, basket, and eggs. Once your game starts, the eggs will gradually move across the floor, which will create an animation indicating that the eggs are falling. Then with the help of loops, we can constantly check that the eggs have been caught in the basket or have touched the ground. When the egg is caught or dropped, it will be an end of an event, so here the egg will be removed and the game has to adjust the score by increasing the score if the egg was caught in the basket or by decreasing your one life if the egg has touched the ground.

Egg Catcher Game using Python
To create an egg catcher game using Python, we need to use three different loops:

One to create new eggs.
Another to check if the catcher has caught an egg.
And the third loop to move eggs and to check if the eggs touched the ground.
I hope you now have understood the complete process of creating an eggs catcher game using Python. Now let’s see how to create an egg catcher game using Python. To create this game, I will be using three Python modules:
1.itertools: to change the colours of the falling eggs.
2.random: to make the eggs appear at random positions.
3.Tkinter: to animate the game on the screen.
The three looping functions are executed using a timer to ensure that they aren’t executed before the main loop. Then the mainloop() function is executed to run the egg catcher game.
