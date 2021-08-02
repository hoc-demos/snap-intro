# Snap! Intro


![](https://github.com/hoc-labs/images/blob/main/alonzo.png?raw=true)
This is Alonzo, the mascot of our programming language, Snap!. You should see him on the stage, the white area in the top right corner of the Snap! window.

![](https://github.com/hoc-labs/images/blob/main/snap-intro-1.png?raw=true)

You're going to program a game in which the goal is to click on Alonzo as he's moving around.

As a first step, make Alonzo jump someplace else on the stage when he's clicked. Drag these two blocks into the scripting area (the center area of the window):

![](https://github.com/hoc-labs/images/blob/main/when-clicked-jump.png?raw=true)

You can find blocks in palettes with their matching color. Drag one block underneath another to snap them together.

![](https://github.com/hoc-labs/images/blob/main/motion-palette-categories.jpg?raw=true)

Test your program: Click on the Alonzo sprite on the stage several times. If your program works, Alonzo should move to a random position on the stage each time you click him.


### Making the Game Challenging
The game isn't much fun if Alonzo just sits there waiting to be clicked. Once you've clicked him, he should keep jumping around on his own. To make Alonzo keep moving around, you need a block that says "do this forever." And there is a block that does it:

![](https://github.com/hoc-labs/images/blob/main/forever.png?raw=true)

Attach this to the bottom of your Alonzo script:

![](https://github.com/hoc-labs/images/blob/main/forever-jump.png?raw=true)


The sequence of blocks inside the **forever** block will repeat until you click the red stop sign, ![](https://github.com/hoc-labs/images/blob/main/stop_button.png?raw=true) stop button, or stop the script in some other way.

Alonzo moves too fast. Use the ![](https://github.com/hoc-labs/images/blob/main/wait-1-secs.png?raw=true) block to slow him down. Try your program, and increase or reduce the wait time if you like.

Where the **wait** block goes in your script matters. Do you want the script to wait one time or each time Alonzo moves?

### Confirming Whether Alonzo Was Clicked
First, the person playing your game wants to know right away whether they succeeded at clicking Alonzo before he moved out of the way.

#### Vocabulary : Sprites and Costumes
The Alonzo character is named after Alonzo Church, a major contributor to early computer science. In this project, there are three objects related to Alonzo:

* One is a sprite, which is like an actor on the stage who knows how to do many different things, such as walk around the stage and speak the lines of the play.
* The other two are costumes, picture that can be "worn" by a sprite.

Program Alonzo to face the other way when clicked.![](https://github.com/hoc-labs/images/blob/main/alonzo.png?raw=true)![](https://github.com/hoc-labs/images/blob/main/alonzo-flipped-other-way.png?raw=true) 
* The project you loaded has two Alonzo costumes—one facing right and the other facing left—so you can use the ![](https://github.com/hoc-labs/images/blob/main/next-costume.png?raw=true) block to make the sprite face the other way. Add the next costume block to the place in your program where the user has just clicked on Alonzo.
* Test your program. Make sure Alonzo faces the other way when he is clicked but not when he jumps without being clicked.

### Keeping Score
The player will also want to know how much progress they have made in the game. The command ![](https://github.com/hoc-labs/images/blob/main/ghosteffect.png?raw=true) can control Alonzo's transparency.

#### Transparency
The transparency of an image is how much you can see what's behind it. For example, here is the Alonzo sprite shown with three different transparencies (which have been set using the **ghost effect** block).

![](https://github.com/hoc-labs/images/blob/main/transparency2.png?raw=true)

Use transparency to tell the user how close they are to winning: every time they click, Alonzo gets more invisible, and when he disappears completely, they win the game.
* Drag the **change (ghost) effect** block into the center scripting area, and experiment with different input numbers (clicking it repeatedly after each change) to see exactly what it does. At what ghost effect value does Alonzo become completely invisible? You can use the command ![](https://github.com/hoc-labs/images/blob/main/clear-graphic-effects.png?raw=true) to make Alonzo fully opaque again.
* Then, modify your script so that every time Alonzo is clicked, he gets a little more ghostly. Think about how the input you use affects the length of the game. Try out your game.
  
### Making the Game More Challenging
So far, even a bad player will eventually make Alonzo disappear. The game will be much more interesting if the player is penalized for missing a click.
* Figure out where to add a **change (ghost) effect by (-5)** block to your script to make Alonzo get less transparent any time he moves without being clicked.
* Play your game a few times, and adjust your code to get a level of difficulty that you like.  (You can change the change effect input number (for either instance of the block) and/or the wait time to make the game easier or harder).

### Ending the Game

When Alonzo is completely transparent, the game should stop.

Add this code to the right place in your script to end the game.

![](https://github.com/hoc-labs/images/blob/main/if-done-stop.png?raw=true)

### Saving your Work

Save your work within your local repository to a file named **snap-intro**.




[Programming Your App](https://www.youtube.com/watch?v=FSroPySQv1o&list=PL2y3GgO490w4AtmsMwi7ESRPXi2-ZDXLI&index=2)

[Moving Randomly](https://www.youtube.com/watch?v=PFuUMeGypeY&list=PL2y3GgO490w4AtmsMwi7ESRPXi2-ZDXLI&index=4)

[Greeting the Player](https://www.youtube.com/watch?v=jhUBYjmWuOk&list=PL2y3GgO490w4AtmsMwi7ESRPXi2-ZDXLI&index=5)

[Make it a Game](https://www.youtube.com/watch?v=zobmLX5ZkKY&list=PL2y3GgO490w4AtmsMwi7ESRPXi2-ZDXLI&index=6)



