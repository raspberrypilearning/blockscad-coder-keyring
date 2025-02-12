## Create 3D text

![The word 'CODER' rendered in BlocksCAD](images/coder-letters-joined.png) 

--- task ---

Open the BlocksCAD editor in a web browser [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_blank"}.

--- /task ---

--- task ---
Click on `Set Ops`{:class="blockscadsetops"} and drag a `union`{:class="blockscadsetops"} block onto the canvas. 

![The union block from the Set Ops group with an arrow showing it being dragged onto the canvas](images/coder-canvas.png)

--- /task ---

The `union`{:class="blockscadsetops"} block joins shapes together. 

Start with the first two letters of 'CODER'. 

--- task ---

Click on `Text`{:class="blockscadtext"} and then drag **two** `3D Text`{:class="blockscadtext"} blocks inside the `union`{:class="blockscadsetops"} block.

![The text blocks inside the union block](images/coder-3dtext.png) 

--- /task ---

--- task ---

Change the 3D text value (`abc`) on the first to `C`, then change the second block's 3D text value to `O`.

To make the letters bigger, change the `size` to `20`.

![The altered 3D text values ](images/coder-co.png) 

--- /task ---

--- task ---	

Click **Render**.

There is a problem: the 'C' and the 'O' are in the same place. 

![The letter O shows, but the C is not easily visible as it is in the same place](images/coder-same-place.png)

--- /task ---

You need to move the 'O' along the X axis so that it comes after the 'C'. 

--- task ---	

Add a `translate`{:class="blockscadtransforms"} block and set the value of `X` to `10` to move the 'O' 10mm along the X axis. 

Click **Render** again.	

![The letter O now appears to the right of the letter C](images/coder-translate.png) 
	
Now, the letters should be touching, but not on top of each other. 

--- /task ---

--- task ---	

Click the `[+]` button on the `union`{:class="blockscadsetops"} block to add a space for another block. 

![A new 'plus' section in the union block](images/coder-union-plus.png) 

--- /task ---
--- task ---

Right-click on the `translate`{:class="blockscadtransforms"} block and select **Duplicate** to create a copy. 

![The duplicate menu](images/coder-duplicate.png) 
	
--- /task ---
--- task ---

Drag the copy into the `union`{:class="blockscadsetops"} block and change the 'O' to a 'D'.
	
![The letter D in the same place as the letter O](images/coder-d.png) 

--- /task ---
--- task ---

Change the `X` value of the second `translate`{:class="blockscadtransforms"} block to `20`, (so that the 'D' is 10mm from the 'O'). 

![Another translate block added to the union block with values set for the letter D](images/coder-d-hint.png) 
  
--- /task ---

--- task ---

Now, add an 'E' and an 'R' to finish the word 'CODER'. 

Make sure that all of the letters are touching, and that there are no gaps between any of the letters.

You need to click the `+` on the `union`{:class="blockscadsetops"} block to add two more `3D Text`{:class="blockscadtext"} blocks.

You can duplicate the code you used to create a 'D' and then change the letters and the `X` values. 

![Another translate block added to the union block with values set for the letters E and R](images/coder-hint-er.png) 
  

--- /task ---

--- task ---

Look closely — are the 'E' and 'R' joined together? If they are not, you need to adjust your code.

--- /task ---

