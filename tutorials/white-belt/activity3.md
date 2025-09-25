# White Belt Level 2 Challenge
```blocks
scene.setBackgroundColor(4)
let Jeff = sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . f f f f f f . . . . . 
    . . . f f e e e e f 2 f . . . . 
    . . f f e e e e f 2 2 2 f . . . 
    . . f e e e f f e e e e f . . . 
    . . f f f f e e 2 2 2 2 e f . . 
    . . f e 2 2 2 f f f f e 2 f . . 
    . f f f f f f f e e e f f f . . 
    . f f e 4 4 e b f 4 4 e e f . . 
    . f e e 4 d 4 1 f d d e f . . . 
    . . f e e e e e d d d f . . . . 
    . . . . f 4 d d e 4 e f . . . . 
    . . . . f e d d e 2 2 f . . . . 
    . . . f f f e e f 5 5 f f . . . 
    . . . f f f f f f f f f f . . . 
    . . . . f f . . . f f f . . . . 
    `, SpriteKind.Player)
let Jen = sprites.create(img`
    . . . . . . 5 . 5 . . . . . . . 
    . . . . . f 5 5 5 f . . . . . . 
    . . . . f 6 2 5 5 6 f . . . . . 
    . . . f 6 6 6 6 1 6 6 f . . . . 
    . . . f 6 6 6 6 6 1 6 f . . . . 
    . . . f d f d 6 6 6 1 f . . . . 
    . . . f d f d 6 6 6 6 f f . . . 
    . . . f d 3 d d 6 6 6 f 6 f . . 
    . . . . f d d d f f 6 f f . . . 
    . . . . . f f 5 3 f 6 6 6 f . . 
    . . . . f 5 3 3 f f f f f . . . 
    . . . . f 3 3 f d f . . . . . . 
    . . . . . f 3 f d f . . . . . . 
    . . . . f 3 5 3 f d f . . . . . 
    . . . . f f 3 3 f f . . . . . . 
    . . . . . . f f f . . . . . . . 
    `, SpriteKind.Player)
Jeff.setPosition(25, 100)
Jen.setPosition(121, 14)
game.setDialogTextColor(8)
game.setDialogFrame(img`
    ..ccccc....333.....333.....333...ccccc....
    .c33b33c..39993...39993...39993.c33b33c...
    c3b33bb3c3999993339999933399999c3bb33b3c..
    c33b33b3c9911199999111999991119c3b33b33c..
    cb33b33bc9199919991999199919991cb33b33bc..
    c3b33bbbcb99999111999991119999bcbbb33b3c..
    c3bb3bbd1b11111999111119991111b1dbb3bb3c..
    .c33bbd1b1111111111111111111111b1dbb33c...
    ..cccc1b111111111111111111111111b1cccc....
    .3991bb11111111111111111111111111bb993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..3991911111111111111111111111111191993...
    ..399191111111111111111111111111191993....
    ..399191111111111111111111111111191993....
    .3991911111111111111111111111111191993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..3991911111111111111111111111111191993...
    ..399191111111111111111111111111191993....
    ..399191111111111111111111111111191993....
    .3991911111111111111111111111111191993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..699bb11111111111111111111111111bb1993...
    ..cccc1b111111111111111111111111b1cccc....
    .c33bbd1b1111111111111111111111b1dbb33c...
    c3bb3bbd1b11119991111199911111b1dbb3bb3c..
    c3b33bbbcb99991119999911199999bcbbb33b3c..
    cb33b33bc1999199919991999199919cb33b33bc..
    c33b33b3c9111999991119999911199c3b33b33c..
    c3b33bb3c9999933399999333999993c3bb33b3c..
    .c33b33c.39993...39993...39993..c33b33c...
    ..ccccc...333.....333.....333....ccccc....
    ..........................................
    ..........................................
    `)
game.showLongText("Knock Knock.", DialogLayout.Top)
game.setDialogTextColor(2)
game.setDialogFrame(img`
    ..66666666666666666666..
    .6699999999999999999966.
    669991111111111111199966
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    669991111111111111199966
    .6699999999999999999966.
    ..66666666666666666666..
    `)
game.showLongText("Who's There?", DialogLayout.Bottom)
game.setDialogTextColor(8)
game.setDialogFrame(img`
    ..ccccc....333.....333.....333...ccccc....
    .c33b33c..39993...39993...39993.c33b33c...
    c3b33bb3c3999993339999933399999c3bb33b3c..
    c33b33b3c9911199999111999991119c3b33b33c..
    cb33b33bc9199919991999199919991cb33b33bc..
    c3b33bbbcb99999111999991119999bcbbb33b3c..
    c3bb3bbd1b11111999111119991111b1dbb3bb3c..
    .c33bbd1b1111111111111111111111b1dbb33c...
    ..cccc1b111111111111111111111111b1cccc....
    .3991bb11111111111111111111111111bb993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..3991911111111111111111111111111191993...
    ..399191111111111111111111111111191993....
    ..399191111111111111111111111111191993....
    .3991911111111111111111111111111191993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..3991911111111111111111111111111191993...
    ..399191111111111111111111111111191993....
    ..399191111111111111111111111111191993....
    .3991911111111111111111111111111191993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..699bb11111111111111111111111111bb1993...
    ..cccc1b111111111111111111111111b1cccc....
    .c33bbd1b1111111111111111111111b1dbb33c...
    c3bb3bbd1b11119991111199911111b1dbb3bb3c..
    c3b33bbbcb99991119999911199999bcbbb33b3c..
    cb33b33bc1999199919991999199919cb33b33bc..
    c33b33b3c9111999991119999911199c3b33b33c..
    c3b33bb3c9999933399999333999993c3bb33b3c..
    .c33b33c.39993...39993...39993..c33b33c...
    ..ccccc...333.....333.....333....ccccc....
    ..........................................
    ..........................................
    `)
game.showLongText("Orange.", DialogLayout.Top)
game.setDialogTextColor(2)
game.setDialogFrame(img`
    ..66666666666666666666..
    .6699999999999999999966.
    669991111111111111199966
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    699911111111111111119996
    669991111111111111199966
    .6699999999999999999966.
    ..66666666666666666666..
    `)
game.showLongText("Orange Who?", DialogLayout.Bottom)
game.setDialogTextColor(8)
game.setDialogFrame(img`
    ..ccccc....333.....333.....333...ccccc....
    .c33b33c..39993...39993...39993.c33b33c...
    c3b33bb3c3999993339999933399999c3bb33b3c..
    c33b33b3c9911199999111999991119c3b33b33c..
    cb33b33bc9199919991999199919991cb33b33bc..
    c3b33bbbcb99999111999991119999bcbbb33b3c..
    c3bb3bbd1b11111999111119991111b1dbb3bb3c..
    .c33bbd1b1111111111111111111111b1dbb33c...
    ..cccc1b111111111111111111111111b1cccc....
    .3991bb11111111111111111111111111bb993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..3991911111111111111111111111111191993...
    ..399191111111111111111111111111191993....
    ..399191111111111111111111111111191993....
    .3991911111111111111111111111111191993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..3991911111111111111111111111111191993...
    ..399191111111111111111111111111191993....
    ..399191111111111111111111111111191993....
    .3991911111111111111111111111111191993....
    399199111111111111111111111111111191993...
    3991991111111111111111111111111111991993..
    3991991111111111111111111111111111991993..
    .399191111111111111111111111111111991993..
    ..699bb11111111111111111111111111bb1993...
    ..cccc1b111111111111111111111111b1cccc....
    .c33bbd1b1111111111111111111111b1dbb33c...
    c3bb3bbd1b11119991111199911111b1dbb3bb3c..
    c3b33bbbcb99991119999911199999bcbbb33b3c..
    cb33b33bc1999199919991999199919cb33b33bc..
    c33b33b3c9111999991119999911199c3b33b33c..
    c3b33bb3c9999933399999333999993c3bb33b3c..
    .c33b33c.39993...39993...39993..c33b33c...
    ..ccccc...333.....333.....333....ccccc....
    ..........................................
    ..........................................
    `)
game.showLongText("Orange you glad I didn't say Banana!", DialogLayout.Top)
effects.confetti.startScreenEffect()
```

## Part 1
This time, we're going to make 2 different sprites, and rename them after we set a background color!
 - Start by setting the ``background color`` in the scene!
 - Make sure to ``set 2 seperate sprites`` and ``rename`` them!
 - Set both sprites' ``positions`` to different places on the screen!

~hint Hint! Only use if you're stuck!
  Both the player sprite creation code and the set position code can be found in the Sprites tab! While the background color can be found in the Scene Tab!
hint~

## Part 2
Next we're going to set a custom textbox and text color for the first sprite!
 - Start by selecting a custom ``Dialog text color`` to make the text pop out!
 - After that, set the ``dialog frame`` to something unique for this sprite!
 - Lastly, we need a ``show long text`` to have the sprite actually say something! And dont forget to change it's ``layout``!
 - Remember all of these for the future, and have this sprite say the first part of your joke!

~hint Hint! Only use if you're stuck!
  All of the dialog text blocks can be found in the Game tab! Remember all of these settings for whenever this sprite is talking!
hint~

## Part 3
Now do the same but for the other sprite! Having them ask about the joke!
 - Set a new ``text color``, ``dialog frame``, and ``layout`` for this ``show long text``!
 - Have them ask about the joke inside of your ``show long text``!
 - Keep all of these settings in mind for whenever this sprite is talking!
 - For an extra challenge, try adding a third sprite with different settings if you can!

~hint Hint! Only use if you're stuck!
  Try to have enough to complete the whole joke! And try not ot have more sprites than 4.
hint~

## Part 4
Finally, add more show long text blocks to complete the joke! And after the joke is done, play a screen effect!
 - Make sure to remember the settings you put for each sprite! (If the first sprite has orange text, when it's talking again it should have orange text!)
 - After the joke is complete, play a ``screen effect`` to show that it's all done!

~hint Hint! Only use if you're stuck!
  Screen effect can be found in the Scene tab!
hint~

## Completed Challenge!
Good job! You completed the challenge! Now if you're ready! You can head onto the Third White Belt Challenge!