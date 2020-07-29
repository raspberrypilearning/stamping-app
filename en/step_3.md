## Get a sprite moving
First it's time to design your graphical user interface (GUI) for the Stamping app. The GUI will includes the menu - ingredients and buttons - as well as the design area of the window where the user will create their design.

--- task ---
Think about how you want the graphical user interface to look.
How much space do you need for the menu?
What buttons do you want.
Do you want to add graphics or colour to the design area?

--- no-print ---
![Animated gif showing path of sprite](images/moving-up-down.gif){:width="400px"}
--- /no-print ---

--- print-only ---
![Image annotated with path of sprite](images/moving-up-down.png){:width="400px"}
--- /print-only ---

Here's the code it uses:

```blocks3
when flag clicked
set rotation style [don't rotate v]
point in direction (0)
set size to (100) %
forever
move (5) steps
if on edge, bounce
end
```

Look at the code and understand how it makes the sprite move.

Choosing `0` in the `point in direction`{:class="block3motion"} block makes the sprite point upwards so the `move`{:class="block3motion"} block will make the sprite move up to the top of the stage. If the sprite touches the top of the Stage it will flip direction and start moving down towards the bottom of the stage. 

--- /task ---

--- task ---
Think about how you want your sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly." or "I want my sprite to be really small and move quickly in a diagonal line."
--- /task ---

--- task ---
Select your first sprite and click on the Code tab. 

--- /task ---

--- task ---
Add code to make your sprite move around the stage in a forever loop, bouncing off the edges of the stage. 

**Add me in: generic-scratch-if-on-edge-bounce **

--- /task ---

--- task ---
Change the speed and direction of your sprite to get the effect you want. 

--- /task ---

--- task ---
You may need to change the way your sprite's costume rotates when it moves to stop it going upside down.

**Add me in: scratch-rotate-costume **

--- /task ---

--- task ---
Is your sprite the size you want it to be? If not, adjust its size.

**Add me in: generic-scratch-change-size **

--- /task ---

**Tip:** It's easier to identify issues if you make one change at a time and then run your program. 

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

*[graphical user interface (GUI)]: a visual way of interacting with windows, icons and menus so a user can input information and receive output from an application.

--- save ---
