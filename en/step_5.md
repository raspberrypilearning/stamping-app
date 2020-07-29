## Buttons
Now its time to create buttons. What do your buttons need to do? Grow, shrink, flip horizontally, flip vertically, ghost?

--- task ---
Go to the [Stamping app](https://scratch.mit.edu/studios/27160618){:target="_blank"} Scratch studio.

Explore the buttons used in the projects. Click 'See inside' to investigate how the code for the buttons works.

--- /task ---

--- task ---
Choose or create in Paint Editor a sprite for each button you need. Don't forget to add a simple icon on each button sprite to visually communicate the buttons effect.

**Tip:** There are some useful button graphics in Scratch - to find these search for buttons in Choose a Sprite.

--- /task ---

--- task ---
Position the buttons where they need to go on the Stage.

--- /task ---

--- task ---

Click on the Code tab of each of the button sprites and add the following code. On each of the button sprites, don't forget to add a New message to the broadcast which is easy to understand i.e if the button flips the costume then call the message flip etc. Make sure you are in the correct button sprite's Code tab when doing this:

```blocks3
when this sprite clicked
broadcast [New message  v]
```
--- /task ---

--- task ---

You now need to go to your equivalent of the Ingredients sprite and add the relevant code so  it recieves the broadcast from each of your button sprites and responds with an effect:
Grow it:
```blocks3
when I receive [message v]
change size by (5)
```
Shrink it:
```blocks3
when I receive [message v]
change size by (-5)
```
Flip it:
```blocks3
when I receive [message v]
turn (180) degrees :: motion
```
Change its colour:
```blocks3
when I receive [message v]
change [color v] effect by (5) :: looks
```
From the dropdown, don't forget to match the correct broadcast message to the effect.

--- /task ---
--- save ---
