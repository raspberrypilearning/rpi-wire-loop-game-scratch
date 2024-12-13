## Challenge

Want to upgrade your project? 

You could:

--- task ---

Add sound effects to your wire loop game to play when the score drops to a certain level, to warn the player they are about to lose:

Choose a sound from the sounds library in Scratch to act as a warning sound and add it to Sprite1.

[[[generic-scratch3-sound-from-library]]]

On Sprite1, create a new script that looks like this:

```blocks3
when flag clicked
wait until <(score) = (3)>
start sound [Bonk v]
```

--- /task ---




--- task ---

Add a 'lose state' which will end the game if your score drops to 0:

On Sprite1, find the code that controls the score. At the very end of the script, simply add a `stop all`{:class="block3control"} block to the end.

```blocks3
when flag clicked
set [score v] to (10)
forever
say (join [Your score is ] (score))
if <(score) < (1)> then
say [You lose] for (2) seconds
+stop [all v]
```

This will stop the game from playing once the score reaches 0.

--- /task ---

--- task ---

If you wanted to further upgrade your wire loop game, you could get some more robust materials to create it from!

Upgraded Wire Loop Game:
<iframe width="560" height="315" src="https://www.youtube.com/embed/IAaq89YkdzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This example has used a lasercut box for the enclosure, while the shaped wire and loop are both made from a metal coat hanger bent into shape using pliers. The handle of the loop comes from a recycled paint roller, while the sound is made by a small USB speaker powered by the Raspberry Pi.

--- /task ---
