## App interface

First, it's time to design the Graphical User Interface (GUI) for your stamping app. For your app, the GUI will include a menu with ingredients (pictures or patterns) and buttons as well as the design area of the window where the user will create their picture or pattern.

`ALTERNATIVE BELOW`

First, it's time to design the Graphical User Interface (GUI) for your stamping app. The GUI will include the design area where the user will create their image, and a menu with the picture or pattern sprite to be used as a stamp and buttons to control how the stamps look.

--- task ---

Design your interface.

Think about what you want the graphical user interface to look like.
+ How will you arrange the design area, the menu area and the buttons?
+ How much space will you need for the menu? Where will it be on the screen?
+ How many buttons will you have? What will they do? Don't worry about the code yet but plan enough space for the buttons and where they will go.
+ Do you want to add a colour, image or pattern to the design area?

![Image of labelled interface](images/labelled_interface.png){:width="400px"}

--- /task ---

--- task ---

First, you'll create the look of the design area. 

**Tip:** Keep in mind where and how large your menu will be as this will cover that part fo the screen.

You will need to select the **Stage** and then you have different options for your design area:
+ Choose a backdrop from Scratch's built-in library
+ Hover over the Choose a backdrop button and select the Paint option to make your own
![Choose a backdrop Paint option](images/chooseBackdropPaint.png)
+ Choose a backdrop from Scratch's built-in library and then select the backdrops tab to customise it
![Backdrop tab](images/backdropTabSelected.png)


Go to the Backdrops tab and create a design area for your interface using graphics and/or colour.

--- /task ---

--- task ---

Select the Code tab for the Backdrop.

--- /task ---

--- task ---

Add this code to the Stage:

```blocks3
when stage clicked
broadcast [add v]
```
Look at the code and try to understand how it works.

Whenever the `stage is clicked`{:class="block3events"}, it will `broadcast`{:class="block3events"} the message, `add`{:class="block3events"}, which can then be `received`{:class="block3events"} by the project sprites.

**Add me in: generic-broadcast **

--- /task ---

--- task ---

Now create a sprite called **Menu**. Go to Choose a Sprite and select Paint to access the Paint Editor.

**Add me in: generic-ChooseaSprite/Paint **

--- /task ---

--- task ---

In the Paint editor, create a menu. In the examples given, a plain white rectangle has been used. The menu sprite should not include any buttons as the buttons will be completely separate sprites you will make later.

--- /task ---

--- task ---

Set the menu to the `back layer`{:class="block3looks"} so that the menu will always sit behind the buttons you create.

**Add me in: generic-painteditor/arrangeforwardORbackward**

--- /task ---

Sprites automatically sit on top of Backdrops so the menu will sit on top of the Backdrop that you have created. 

The menu sprite doesn't need any code.

--- task ---

At this stage, you may need to reposition the menu to one side of the stage's design area or change its size.

--- /task ---

*[Graphical User Interface (GUI)]: a visual way of interacting with windows, icons and menus so a user can input information and receive output from an application.

--- save ---
