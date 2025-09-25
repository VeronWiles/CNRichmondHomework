# Orange Belt Level 1 Challenge

```blocks
scene.setBackgroundColor(8)
game.splash("Time for a Riddle!")
let Jeff = sprites.create(img`
    . . . . . . . . . . b 5 b . . . 
    . . . . . . . . . b 5 b . . . . 
    . . . . . . . . . b c . . . . . 
    . . . . . . b b b b b b . . . . 
    . . . . . b b 5 5 5 5 5 b . . . 
    . . . . b b 5 d 1 f 5 5 d f . . 
    . . . . b 5 5 1 f f 5 d 4 c . . 
    . . . . b 5 5 d f b d d 4 4 . . 
    b d d d b b d 5 5 5 4 4 4 4 4 b 
    b b d 5 5 5 b 5 5 4 4 4 4 4 b . 
    b d c 5 5 5 5 d 5 5 5 5 5 b . . 
    c d d c d 5 5 b 5 5 5 5 5 5 b . 
    c b d d c c b 5 5 5 5 5 5 5 b . 
    . c d d d d d d 5 5 5 5 5 d b . 
    . . c b d d d d d 5 5 5 b b . . 
    . . . c c c c c c c c b b . . . 
    `, SpriteKind.Player)
Jeff.setPosition(58, 91)
Jeff.sayText("What has hands, but can never clap?")
music.play(music.melodyPlayable(music.powerUp), music.PlaybackMode.UntilDone)
Jeff.setImage(img`
    ..............ffffff....
    .............f2feeeeff..
    ............f222feeeeff.
    .......cc...feeeeffeeef.
    .......cdc.fe2222eeffff.
    .......cddcf2effff222ef.
    ........cddcffeeefffffff
    .........cddce44fbe44eff
    ..........cdceddf14d4eef
    ..........cccdeddd4eeef.
    ...........edd4e44eeff..
    ............ee442222f...
    .............f2e2222f...
    .............f554444f...
    ..............ffffff....
    ................fff.....
    ........................
    ........................
    ........................
    ........................
    ........................
    ........................
    ........................
    ........................
    `)
Jeff.setPosition(107, 35)
Jeff.sayText("A Horse?")
music.play(music.melodyPlayable(music.spooky), music.PlaybackMode.UntilDone)
Jeff.setImage(img`
    . . . . . . . . . . b 5 b . . . 
    . . . . . . . . . b 5 b . . . . 
    . . . . . . . . . b c . . . . . 
    . . . . . . b b b b b b . . . . 
    . . . . . b b 5 5 5 5 5 b . . . 
    . . . . b b 5 d 1 f 5 5 d f . . 
    . . . . b 5 5 1 f f 5 d 4 c . . 
    . . . . b 5 5 d f b d d 4 4 . . 
    b d d d b b d 5 5 5 4 4 4 4 4 b 
    b b d 5 5 5 b 5 5 4 4 4 4 4 b . 
    b d c 5 5 5 5 d 5 5 5 5 5 b . . 
    c d d c d 5 5 b 5 5 5 5 5 5 b . 
    c b d d c c b 5 5 5 5 5 5 5 b . 
    . c d d d d d d 5 5 5 5 5 d b . 
    . . c b d d d d d 5 5 5 b b . . 
    . . . c c c c c c c c b b . . . 
    `)
Jeff.setPosition(58, 91)
Jeff.sayText("A Clock!")
effects.smiles.startScreenEffect()
music.play(music.melodyPlayable(music.beamUp), music.PlaybackMode.UntilDone)
```

## Part 1
Using the provided blocks, try your hand at:
 - Setting the ``background color`` (To any color you'd like!).
 - Creating a ``Player Sprite``. (Either make it yourself or use one from the gallery!)
 - Setting its ``position`` to somewhere in the screen! 

~hint Hint! Only use if you're stuck!
  Both the player sprite creation code and the set position code can be found in the Sprites tab! While the background color can be found in the Scene Tab!
hint~

## Part 2
Great Job! Now it's time to have the sprite say the riddle and then play a sound!
 - Make sure to add a ``say block`` to have the sprite say the riddle!
 - After that, ``play a sound`` before we move on to the next scene!
 - Normally, we play a sound to keep the text on screen, but for an extra challenge, click on the ``+`` for the say block and change the time its on screen!

~hint Hint! Only use if you're stuck!
  You can find the say block in the Sprites tab, and the sound tab in the Music tab! As a side note, every 1000 ms (Miliseconds) is 1 second!
hint~

## Part 3
Now it's time for our next scene! We're going to change the image and position of the player and have it respond to the other!
 - Right under the play sound block we're going to have a ``set image`` block, change it to the player thats going to ask what the riddle is!
 - Set their ``position`` to a different position than the first player!
 - Have them ``say`` text that asks for the answer to the riddle.
 - Dont forget to change how long they stay on screen!
 - Lastly, play another ``sound`` to end this scene!

~hint Hint! Only use if you're stuck!
  The Set Image block can be found in the scenes tab! For the other blocks, check the previous steps!
hint~

## Part 4
Finally, we're going to have the sprite tell us the answer! As well as tell the player what game theyre playing!
 - We need another ``set image`` block.
 - After making it, remember to set its ``position``!
 - Make sure to make them ``say`` the answer.
 - Then play a ``sound`` to end the final scene!
 - Now at the very top, we need to add a ``splash screen`` to tell the player this is a riddle! Make sure to put it above everything but below the set background!

~hint Hint! Only use if you're stuck!
  The splash block is under the Game tab, and make sure to put it under the background block!
hint~

## Completed Challenge!
Good job! You completed the challenge! Now if you're ready! You can head onto the Second White Belt Challenge!