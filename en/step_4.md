## Joining letters together

Next you're going to join the letters together so that the keyring looks like this:

![screenshot](images/coder-letters-joined.png) 

+ Change your code so that it only creates the letter "C"

	![screenshot](images/coder-c.png) 
	
+ The `union` block joins shapes together. Let's start with the first two letters of "CODER". 

	![screenshot](images/coder-co.png) 
	
	Blocks are colour-coded, look under `Set Ops` to find `union`. 
	
	Note that the `3D Text` block is found under `Text` even though it's green. 
	
+ Click `Render` and you'll see that we have a problem. The "C" and the "O" are in the same place. 

	![screenshot](images/coder-same-place.png)
		
	You need to move the "0" along the X axis so that it comes after the "C". 
	
+ Add a `translate` block to move the "O" 10mm in the X direction. 
	
	![screenshot](images/coder-translate.png) 
	
	Now the letters should be touching but not on top of each other. 
	
+ Click on the `[+]` image on the `union` block to add a space for another block. 

+ Right-click on the `translate` block and choose `duplicate` to create a copy. 

	![screenshot](images/coder-duplicate.png) 
	
+ 	Drag the copy into the `union` block and change the "O" to a "D".
	
	![screenshot](images/coder-d.png) 
	
+ Change the X value of the second `translate` block so that the D is in the right place. 

--- hints ---
--- hint ---
Think about what you changed to make the "O" move along. The "D" starts off in the same place as the C and you need to move it after the "O". 
--- /hint ---
--- hint ---
	![screenshot](images/coder-d-hint.png) 
--- /hint ---
--- /hints ---

+ Now add an "E" and an "R" to finish the word "CODER". 

Take care that all the letters are touching, don't leave a gap between the E and the R.

--- hints ---
--- hint ---
You'll need to click the `+` on the union block to add space for two more letters. 
--- /hint ---
--- hint ---
You can duplicate the code for creating a "D" and then change the letter and the X value. 
--- /hint ---
--- hint ---
	![screenshot](images/coder-hint-er.png) 
--- /hint ---
--- /hints ---

+ Look closely, are the E and R joined together? If not, you will need to adjust your code. 
