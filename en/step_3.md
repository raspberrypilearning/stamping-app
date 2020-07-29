## App interface
First it's time to design your graphical user interface (GUI) for the Stamping app. The GUI will includes the menu - ingredients and buttons - as well as the design area of the window where the user will create their design.

--- task ---
Design your interface.

Think about what you want the graphical user interface to look like.
How much space will you need for the menu?
What buttons do you need? You will make them in the next step  but you need enough space for them when you are planning.
Do you want to add a graphic and/or colour to the design area?

![Image of labelled interface](images/labelled_interface.png){:width="400px"}

--- /task ---

--- task ---
Go to the Backdrops tab and create a design area for your interface using graphics and/or colour.

--- /task ---

--- task ---
Select the Code tab for the Backdrop.

--- /task ---

--- task ---
Add this simple code for the Backdrop:

```blocks3
when stage clicked
broadcast [add v]
```
Look at the code and understand how it works.

**Add me in: generic-broadcast **

--- /task ---

--- task ---
Now create a sprite called Menu. Go to Choose a Sprite and select Paint to access the Paint Editor.

**Add me in: generic-ChooseaSprite/Paint **

--- /task ---

--- task ---
In the Paint Editor create a menu. In the examples given, a plain white rectangle has been used. The menu should not include any buttons.

--- /task ---

--- task ---
Set the menu to Backward so that the menu will always sit behind the buttons you create.

**Add me in: generic-painteditor/arrangeforwardORbackward**

--- /task ---

Sprites automatically sit on top of Backdrop so the menu will sit on top of the Backdrop that you have created. 

The menu sprite needs no code.

--- task ---

At the stage you may need to reposition the menu to one side of the Backdrop's design area or make the interface's design area larger or smaller.

--- /task ---

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
