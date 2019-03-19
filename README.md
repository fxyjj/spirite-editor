As the specification described, for this part, the core game coding team have asked for a tool to support the graphics development of the game. the task is to write a simple Sprite Editor to edit the graphics assets in the game.

-- In this tool app, there are several functions that this tool covered.

1: Paint on the canvas;

2: Adjust the bursh size and color;

3: Import pictures from the computer;

4: Remove the contents on the current canvas;

5: Export the canvas with a ".png" format;

6: Adjust the export image size;

--Details

1: Painting

** Brush button, Choose painting model to bursh;

** Erase button, Choose panting model to erase allowing user to erase;

** ColorPicker button, Choose a bursh color. In the color picker, user can either choose the color existed in the color grid or customise new color
   by themselves;

** Brush Slider, allow the user adjust the bursh size from 5 to 20;

** Erase Slider, allow the user adjust the erase size from 5 to 20;

** Remove button, remove all of the contents on the current canvas;

** Reovke button, remove the most recently painting contents ,click it for removing one pixel and dragging mouse in the button for removing 
   continuous pixels, Pay attention: this button cannot get access when user import a picture outside;

2: Menu options

** File

  ## Import Picture... : Ask the user to choose a image file to import;

  ## Save...           : Save current canvas as a ".png" file in the computer;

  ## Save As...        : Save the canvas while user can name the image file ;

** Edit                : Adjust the export file size;
   
  ## 32 x 32(Default) 

  ## 64 x 64

  ## 128 x 128

** Help 
 
  ## About             : Help menu 


















