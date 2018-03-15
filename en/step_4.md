## Joining letters together

Next you're going to join the letters together. 

+ Change your code so that it only creates the letter "C"

	![screenshot](images/coder-c.png) 
	
+ The `union` block joins shapes together. Let's start with the first two letters of "CODER". 

	![screenshot](images/coder-co.png) 
	
	Blocks are colour-coded, look under `Transforms` to find `union`. 
	
	Note that the `3D Text` block is found under `Text` even though it's green. 
	
+ Click `Render` and you'll see that we have a problem. The "C" and the "O" are in the same place. 

	![screenshot](images/coder-same-place.png)
	
+ You need to move the "0" along. 

	ingredient: xyz-axes

	Add a `translate` block to move the "O" 10mm in the x direction. 
	
	![screenshot](images/coder-translate.png) 
	
	Now the letters should be touching but not on top of each other. 
	
+ Click on the `[+]` image on the `union` block to add a space for another block. 

+ Right-click on the `translate` block and choose `duplicate` to create a copy. 

	![screenshot](images/coder-duplicate.png) 
	
+ 	Drag the copy into the `union` block and change the "O" to a "D".
	
	![screenshot](images/coder-d.png) 
	
+ Change the x value of the second `translate` block so that the D is in the right place. 

hint

+ Now add an "E" and an "R" to finish the word "CODER". 

hint

