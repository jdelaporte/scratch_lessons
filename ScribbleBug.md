# Lesson 1: Scribble Bug!

![Scribble Bug Intro Picture](img/ScribbleBug.png)

Teach Scribble bug how to follow your mouse while he scribbles in fun colors.

## Step 1: Add the Bug

- If you want to, change the cat into a bug, or some other picture.
- ![Choose Costume From Library](img/chooseCostumeFromLibrary2.png)
- The links at the left are sets of pictures. The bug I chose is in the *Animals* set.
- ![Sprite Library](img/SpriteLibrary.png)
- ![Delete a sprite](img/deleteASprite.png) We don't need the Cat sprite for this program. Let's delete it.

## Step 2: Read the Scribble Bug Scratch Code

The following code blocks will make your bug move.
First we will find each block.
Then we will put them together like this:

![Scribble Bug Code](img/ScribbleBugCode.png)

## Step 3: Find the blocks we need

The blocks we need are:
- ![green flag](img/whengreenflagclicked.png) *when Green Flag clicked* 
- ![Pen Down](img/pendown.png) *pen down* 
- ![Forever](img/forever.png) *forever*
- ![Point Toward](img/pointtowardsmousepointer.png) *point towards moust pointer*
- ![Pen color by 10](img/changepencolorby10.png) *change pen color by 10*
- ![Move 10 steps](img/move10steps.png) *move 10 steps*

### Find 2 Motion Blocks

![Scripts Motion](img/ScriptsMotion.png)

| Block | Description | 
|--|--|
| ![Point Toward](img/pointtowardsmousepointer.png) | **Point Toward** is a *Motion* block. We will use it to tell Scribble Bug to point toward the mouse pointer. |
| ![Move 10 steps](img/move10steps.png) | **Move 10 steps** is another *Motion* block. It tell scribble bug to move forward a little bit. |

- Since *Point Toward Mouse* goes inside the *Forever* block, Scribble Bug will point toward the mouse forever.
- Since *Move 10 steps* goes inside the *Forever* block, Scribble Bug will always move forward. If we forget this command, Scribble Bug will forget to move.

You can double-click any block to try it out. Some blocks do not do much until they are connected to other blocks. But *Move 10 steps* is a good block to try double-clicking. *Move 10 steps* will make the sprite move a little bit.


### Find 1 Event Block

![Scripts Event](img/ScriptsEvents.PNG)

![green flag](img/whengreenflagclicked.png) 

*when Green Flag clicked* is an *Event* block. Find it in the *Events* section. It tells Scribble Bug when to get started.
Drag it from the *Block List* to the *Script* area to the right.

![Drag the block to the script area](img/dragBlockIntoScript.png)

### Find 1 Control Block

![Scripts Control](img/ScriptsControl.png)

![Forever](img/forever.png)

*Forever* is a *Control* block. Find it in the *Control* section. It makes any blocks inside repeat forever. We will use it to make Scribble Bug follow the mouse forever.

### Find 2 Pen Blocks

*Pen* is an Extension in Scratch 3. Let's add it now.

Find and press the `Add Extension` button in the bottom left.

![Add Pen Module](img/AddModule.PNG)

Choose the `Pen` extension.

![Add Pen Module](img/ChooseAnExtension.PNG)

You now have new *Pen* commands available.

![Scripts Pen](img/ScriptsPen.png)

![Pen Down](img/pendown.png)

*Pen Down* is a *Pen* block. Find it in the *Pen* section. You may need to scroll down in the scripts window. It tells Scribble Bug to touch the pen down to the page.

![Pen shade by 10](img/changepencolorby10.png)

*Change pen shade by 10* is another *Pen* block. It tells scribble bug to change its pen color just a little bit. If we call it enough times, the line becomes a rainbow! The *forever* block will make sure it gets called lots of times.

## Step 4: Assemble the blocks

Now that we have all the parts, here's the way to put them together:

![Scribble Bug Code](img/ScribbleBugCode.png)

Drag the blocks with the mouse until they snap together.

## Step 5: Play!

Congratulations! Press the *Green Flag* to play your new game!

![Scribble Bug Intro Picture](img/ScribbleBug.png)

You can also copy, remix and enjoy [My Version of Scribble Bug](https://scratch.mit.edu/projects/170692819/), too.

*Remixes*

- [Smokey Dragon by jdelaporte](https://scratch.mit.edu/projects/171658206/) This version fixes the bouncing when bug catches the mouse pointer. 
