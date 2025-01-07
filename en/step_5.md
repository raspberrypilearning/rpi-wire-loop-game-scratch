## Add a score

Add some code to keep a score of how the player is doing.

--- task ---

Create a new variable and call it `score`{:class='block3variables'}. When you run the program, the score should start at `10`.

```blocks3
when flag clicked
set [score v] to (10)
```

--- /task ---

--- task ---

Each time the loop touches the wire, the score should decrease by `1`. Alter the section of your code that starts with `when button 21 is pressed`{:class="block3extensions"} so that it looks like this:

```blocks3
when button (21 v) is [pressed v] ::extension hat
change [score v] by (-1)
turn LED (20 v) [on v] ::extension
```

--- /task ---

--- task ---

Now you can have **Sprite1** report the score by using a `forever`{:class='block3control'} loop:

```blocks3
when flag clicked
set [score v] to (10)
+forever
+say (join [Your score is ] (score))
```

--- /task ---

--- task ---

Run your program and **Sprite1** should tell you the score, and each time you touch the wire it should decrease.

--- /task ---

--- task ---

Add an `if ... then`{:class='block3control'} block to your code, so that you can tell the player that they have lost when their score is less than `1`.

```blocks3
when flag clicked
set [score v] to (10)
forever
say (join [Your score is ] (score))
+if <(score) < (1)> then
+say [You lose] for (2) seconds
```

--- /task ---

--- task ---

Run your program and then play your wire loop game. Every time you touch the wire, your score should drop.

--- /task ---

--- save ---
