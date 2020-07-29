## Ingredients sprite or equivalent
Now you've got the graphical user interface designed you need to make it interactive.

At this stage, you are going to get the interaction working before you develop the Ingredient sprite's costumes. 

--- task ---

Choose any sprite. Remember you can change the sprite's costumes later.

--- /task ---

--- task ---

Rename your chosen sprite with a name which relates to your unique project. We will call the sprite "your equivalent of the Ingredients sprite".

**Add me in: scratch-renaming-sprite**

--- /task ---

--- task ---

Go to the Stamp fruit step in the project [Fruit salad](https://learning-admin.raspberrypi.org/en/projects/fruit-salad/1). 

--- /task ---

--- task ---

Search for the phrase when I recieve and investigate this section of the step. It will take you through the process of creating the set-up code for your equivalent of the Ingredients sprite so you can begin to stamp graphics.

**Add me in: projectadmin-wordsearchtool - possibly gif**

--- /task ---

--- task ---

Go to your equivalent of the Ingredients sprite's Code tab:

--- /task ---

--- task ---

Add the following code:
```blocks3
when I receive [add]
go to (mouse-pointer v)
stamp
go to x: ( ) y: ( )
```

**Tip:** The final block are the coordinates of the `go to x: y:`{:class="block3motion"} which return your sprite to its starting position within the menu. The sprite will note that location automatically in `Motion block`{:class="block3motion"} so you shouldn't need to change the coordinates.

**Add me in: scratch-x/yinMotionBlock-sprite**

--- /task ---

--- task ---

Try out your project by clicking on the design area.

Your equivalent of the Ingredients sprite moves from the menu to the mouse pointer, creates a stamp and then moves back to the menu. This happens quickly so you don't see it move!

You won't be able to create a stamp by clicking on the menu as the menu stops you doing this. Rememeber, the `add`{:class="block3events"} message only gets broadcast if you click on the Stage.

If you add a piece of fruit so that it overlaps the Stage then the stamp will automatically go behind the menu. 

**Tip:** On all projects, stamps go on top of backdrops but underneath sprites. 

--- /task ---

--- task ---
Go to the Cosumtes tab of your sprite.

--- /task ---

--- task ---
Create a number of costumes relevant to your project, either by selecting costumes from the Choose a Sprite menu, adapting them in Paint Editor or creating them yourself in the Paint Editor. 

**Tip:** In Paint Editor, you can select an area of a costumes to use to create a unique costume.

**Add me in: scratch-findingcostumessembeddedinsprites**
--- /task ---

--- task ---
Remember to delete existing costumes which you no longer require.

**Add me in: scratch-deletingcostumes**

--- /task ---

You now need to add two set up blocks of code. 

--- task ---
The first set up block is  to clear the Stage of any stamps when the user runs the app:
```blocks3
when green flag clicked
clear graphics effects :: looks
```
--- /task ---

--- task ---

The second set up block is when your equivalent of the Ingredients sprite is clicked, it automatically changes to the next costume:

```blocks3
when this sprite clicked
change costume :: looks
```
--- /task ---

--- save ---

