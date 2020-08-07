## Stamp sprite

You've got the Graphical User Interface (GUI) created, so the next step is to make it interactive.

Right now, you are going to get the interaction working, and later you'll develop the stamping sprite's picture and/or pattern making costumes.

--- task ---

Choose any sprite. Remember you can change the sprite's costumes later.

--- /task ---

--- task ---

Rename your chosen sprite to **stamp** or with a name which relates to your unique project. 

**Add me in: scratch-renaming-sprite**

--- /task ---

--- task ---

Go to the project Fruit salad and explore the [Stamp fruit](https://project.raspberrypi.org/en/projects/fruit-salad/1){:target="_blank"} step.

--- /task ---

--- task ---

When you are in the step, search for the phrase `when I recieve`{:class="block3events"} and investigate this section of the step. It will take you through the process of creating the set-up code for your equivalent of the Ingredients sprite so you can begin to stamp graphics.

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

**Tip:** The final block, `go to x: y:`{:class="block3motion"}, gives the coordinates to return your sprite to its starting position within the menu. The sprite's  position in the menu will be noted automatically in `Motion block`{:class="block3motion"} so you shouldn't need to change the coordinates in the block.

**Add me in: scratch-x/yinMotionBlock-sprite**

--- /task ---

--- task ---

Try out your project by clicking on the design area.

Your equivalent of the Ingredients sprite moves from the menu to the mouse pointer, creates a stamp and then moves back to the menu. This happens quickly so you don't see it move!

You won't be able to create a stamp by clicking on the menu as the menu stops you doing this. Rememeber, the `add`{:class="block3events"} message only gets broadcast if you click on the Stage.

If you add a costume that overlaps the Stage then the stamp will automatically go behind the menu. 

**Tip:** On all projects, stamps go on top of Backdrops but underneath sprites. 

--- /task ---

--- task ---
Go to the Costumes tab of your sprite.

--- /task ---

--- task ---
Create a number of costumes relevant to your project, either by selecting costumes from the Choose a Sprite menu, adapting them in Paint Editor or by creating them yourself in the Paint Editor. 

**Tip:** In Paint Editor, you can select an area of a costumes to use to create a unique costume.

**Add me in: scratch-findingcostumessembeddedinsprites**
--- /task ---

--- task ---
Remember to delete existing costumes which you no longer require.

**Add me in: scratch-deletingcostumes**

--- /task ---

You now need to add two set up blocks of code. 

--- task ---
The first set up block clears the Stage of any stamps at the start when the user runs the app:
```blocks3
when green flag clicked
clear graphics effects :: looks
```
--- /task ---

--- task ---

The second set up block automatically changes to the next costume when your equivalent of the Ingredients sprite is clicked:

```blocks3
when this sprite clicked
change costume :: looks
```
--- /task ---

--- save ---

