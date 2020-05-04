## Join the letters together

Next, you will join the letters together so that the key ring looks like this:

![screenshot](images/coder-letters-joined.png)

--- task ---

Change your code so that it only creates the letter 'C'.

![screenshot](images/coder-c.png)

--- /task --- --- task ---

The `union`{:class="blockscadsetops"} block joins shapes together. Start with the first two letters of 'CODER'.

![screenshot](images/coder-co.png)

Blocks are colour-coded. Look under `Set Ops`{:class="blockscadsetops"} to find `union`{:class="blockscadsetops"}.

Note that the `3D Text`{:class="blockscad3dshapes"} block is found under `Text`{:class="blockscadstext"}, even though it's green.

--- /task --- --- task ---

Click **Render** and you'll see that there is a problem: the 'C' and the 'O' are in the same place.

![screenshot](images/coder-same-place.png)

You need to move the 'O' along the X axis so that it comes after the 'C'.

--- /task --- --- task ---

Add a `translate`{:class="blockscadtransforms"} block and set the value of `X` to `10` to move the 'O' 10mm along the X axis.

![screenshot](images/coder-translate.png)

Now, the letters should be touching, but not on top of each other.

--- /task --- --- task ---

Click the `[+]` button on the `union`{:class="blockscadsetops"} block to add a space for another block.

--- /task --- --- task ---

Right-click on the `translate`{:class="blockscadtransforms"} block and select **Duplicate** to create a copy.

![screenshot](images/coder-duplicate.png)

--- /task --- --- task ---

Drag the copy into the `union`{:class="blockscadsetops"} block and change the 'O' to a 'D'.

![screenshot](images/coder-d.png)

--- /task --- --- task ---

Change the `X` value of the second `translate`{:class="blockscadtransforms"} block so that the 'D' is in the right place.

--- hints --- --- hint ---

Think about what you changed to make the 'O' move to after the 'C'. The 'D' starts off in the same place as the 'C', and you need to move it to after the 'O'.

--- /hint --- --- hint ---

    ![screenshot](images/coder-d-hint.png)

--- /hint --- --- /hints ---

--- /task --- --- task ---

Now, add an 'E' and an 'R' to finish the word 'CODER'.

Make sure that all of the letters are touching, and that there are no gaps between any of the letters.

--- hints --- --- hint ---

You need to click the `+` on the `union`{:class="blockscadsetops"} block to add space for two more letters.

--- /hint --- --- hint ---

You can duplicate the code you used to create a 'D' and then change the letters and the `X` values.

--- /hint --- --- hint ---

    ![screenshot](images/coder-hint-er.png)

--- /hint --- --- /hints ---

--- /task --- --- task ---

Look closely — are the 'E' and 'R' joined together? If they are not, you need to adjust your code.

--- /task ---

