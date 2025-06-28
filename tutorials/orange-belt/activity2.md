# Orange Belt Level 2 Challenge

```typescript
scene.setBackgroundColor(4)
game.splash("Test Scenes")
// Scene 1
game.setDialogTextColor(8)
game.setDialogFrame(img`
    ..bbbbbbbbbbbbbbbbbbbb..
    .b11bb11bb11bb11bb11bbb.
    bbb11bb11bb11bb11bb11b1b
    bb1bbbbbbbbbbbbbbbbbb11b
    b11bb11111111111111bb1bb
    b1bb1111111111111111bbbb
    bbbb1111111111111111bb1b
    bb1b1111111111111111b11b
    b11b1111111111111111b1bb
    b1bb1111111111111111bbbb
    bbbb1111111111111111bb1b
    bb1b1111111111111111b11b
    b11b1111111111111111b1bb
    b1bb1111111111111111bbbb
    bbbb1111111111111111bb1b
    bb1b1111111111111111b11b
    b11b1111111111111111b1bb
    b1bb1111111111111111bbbb
    bbbb1111111111111111bb1b
    bb1bb11111111111111bb11b
    b11bbbbbbbbbbbbbbbbbb1bb
    b1b11bb11bb11bb11bb11bbb
    .bbb11bb11bb11bb11bb11b.
    ..bbbbbbbbbbbbbbbbbbbb..
`)
game.setDialogCursor(img`
    ....................
    ....................
    ....................
    ....................
    ....................
    ....................
    .......33...33......
    ......3333.3333.....
    ......333333333.....
    ......333333333.....
    .......3333333......
    ........33333.......
    .........333........
    ..........3.........
    ....................
    ....................
    ....................
    ....................
    ....................
    ....................
`)
game.showLongText("Hearts", DialogLayout.Bottom)
effects.hearts.startScreenEffect()
pause(2000)
effects.hearts.endScreenEffect()
// Scene 2
game.setDialogTextColor(7)
game.setDialogFrame(img`
    ...cc..............................cc.....
    ..c55c..bbbb...bbbbb...bbbbb......c55c....
    .cb55bcbdddbbbbbdddbbbbbdddbbbbbbcb55bc...
    b555555bbdddb111bdddb111bdddb11db555555b..
    bb5555bbbbdb11111bdb11111bdb1111bb5555bb..
    cb5555bcddd11111ddd11111ddd11111cb5555bc..
    .c5bb5c1111d111d111d111d111d111ddc5bb5c...
    .cbbbbc11111111111111111111111111cbbbbc...
    ..b1111111111111111111111111111111dddbb...
    ..b11111111111111111111111111111111dbbdb..
    ..bb1111111111111111111111111111111dbddb..
    .bbdb1d1111111111111111111111111111ddddb..
    .bdddd1111111111111111111111111111d1bdbb..
    .bddbd1111111111111111111111111111111bb...
    .bdb1d11111111111111111111111111111111b...
    .bb111d1111111111111111111111111111111b...
    ..b1111111111111111111111111111111d111bb..
    ..b11111111111111111111111111111111d1bdb..
    ..bb1111111111111111111111111111111dbddb..
    .bbdb1d1111111111111111111111111111ddddb..
    .bdddd1111111111111111111111111111d1bdbb..
    .bddbd1111111111111111111111111111111bb...
    .bdb1d11111111111111111111111111111111b...
    .bb111d1111111111111111111111111111111b...
    ..b1111111111111111111111111111111d111bb..
    ..b11111111111111111111111111111111d1bdb..
    ..bb1111111111111111111111111111111dbddb..
    .bbdb1d1111111111111111111111111111ddddb..
    .bdddd1111111111111111111111111111d1bdbb..
    .bddbd1111111111111111111111111111111bb...
    .bdbb111111111111111111111111111111111b...
    .bbbd111111111111111111111111111111111b...
    ..bcc11111111111111111111111111111dccdb...
    ..c55c1111111d111d111d111d111d1111c55cb...
    .cb55bcdd11111ddd11111ddd11111dddcb55bc...
    b555555bd1111bdb11111bdb11111bdbb555555b..
    bb5555bbdd11bdddb111bdddb111bdddbb5555bb..
    cb5555bcbbbbbbdddbbbbbdddbbbbbddcb5555bc..
    .c5bb5c......bbbbb...bbbbb...bbbbc5bb5c...
    .cbbbbc..........................cbbbbc...
    ..........................................
    ..........................................
`)
game.setDialogCursor(img`
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . b b . . . . . . .
    . . . . . . b 5 5 b . . . . . .
    . . . b b b 5 5 1 1 b b b . . .
    . . . b 5 5 5 5 1 1 5 5 b . . .
    . . . . b d 5 5 5 5 d b . . . .
    . . . . c b 5 5 5 5 b c . . . .
    . . . . c 5 d d d d 5 c . . . .
    . . . . c 5 d c c d 5 c . . . .
    . . . . c c c . . c c c . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
`)
game.showLongText("Stars", DialogLayout.Bottom)
effects.starField.startScreenEffect()
pause(2000)
effects.starField.endScreenEffect()
// Scene 3
game.setDialogTextColor(6)
game.setDialogFrame(img`
    999999999999999999999999999999999999999999999999
    999999999999999999999999999999999999999999999999
    999911119999119991111999111199999999119999999999
    999111111191111911111191111119911191111991111999
    999111111111111111111111111111111111111911111199
    999111111111111111111111111111111111111111111199
    999111111111111111111111111111111111111111111199
    999911111111111111111111111111111111111111111199
    999991111111111111111111111111111111111111111999
    999111111111111111111111111111111111111111111999
    991111111111111111111111111111111111111111119999
    991111111111111111111111111111111111111111111999
    999111111111111111111111111111111111111111111199
    999911111111111111111111111111111111111111111199
    999111111111111111111111111111111111111111111999
    999111111111111111111111111111111111111111119999
    999111111111111111111111111111111111111111111999
    999911111111111111111111111111111111111111111199
    999911111111111111111111111111111111111111111199
    999111111111111111111111111111111111111111111199
    991111111111111111111111111111111111111111111199
    991111111111111111111111111111111111111111111999
    991111111111111111111111111111111111111111119999
    991111111111111111111111111111111111111111111999
    999111111111111111111111111111111111111111111199
    999911111111111111111111111111111111111111111199
    999111111111111111111111111111111111111111111199
    991111111111111111111111111111111111111111111199
    991111111111111111111111111111111111111111111999
    991111111111111111111111111111111111111111119999
    991111111111111111111111111111111111111111119999
    999111111111111111111111111111111111111111111999
    99d1111111111111111111111111111111111dd111111199
    9ddd111111111111111111111111111111111dd111111199
    9ddd1111111111dd111111111111111111111dd1111dd199
    9d1d111111111ddddd11111111111ddddd111ddd111ddd99
    9ddd111ddd111d111d1111ddddd11d111d11dddd111ddd99
    9d1d11ddddd11ddddd1111ddddd11ddddd11d1dd111ddd99
    9ddd11d1d1d11d111d1dd1d1ddd11d111d11dddddddddd99
    9d1d11ddddd11ddddd1dd1ddd1d11ddddddddd1ddd111ddd
    dddd11d1d1d11d111d1dd1ddddd11d111ddddddddddddddd
    dd1d1ddddddddddddd1dd1d1ddddddddddddd1dddd111ddd
    dddd1dd1d1dddd111dddddddd1dddd111ddddddddddddddd
    dd1d1ddddddddddddddddddddddddddddddddd1ddd111ddd
    ddddddddddddddddddddddd1dddddddddddddddddddddddd
    ddddddddddddddddddddddddd1ddddddddddd1dddd111ddd
    .dddddddddddddddddddddddddddddddddddddddddddddd.
    ..dddddddddddddddddddddddddddddddddddddddddddd..
`)
game.setDialogCursor(img`
    . . . . . . . . . . . . . . . .
    . . . . . 1 . . . . . . . . . .
    . . 1 1 . . . 1 1 1 . . . . . .
    . . 1 1 . 1 1 1 1 1 1 1 . . . .
    . . . . 1 1 1 1 1 1 1 1 1 . . .
    . . . 1 1 1 1 1 1 1 1 1 1 1 . .
    . . . 1 1 1 1 1 1 1 1 1 1 1 . .
    . . 1 1 1 1 1 1 1 1 1 1 1 1 1 .
    . . 1 1 1 1 1 1 1 1 1 1 1 1 1 .
    . . 1 1 1 1 1 1 1 1 1 1 1 1 1 .
    . . . 1 1 1 1 1 1 1 1 1 1 1 . .
    . . . 1 1 1 1 1 1 1 1 1 1 1 . .
    . . . . 1 1 1 1 1 1 1 1 1 . . .
    . . 1 . . 1 1 1 1 1 1 1 . . . .
    . . . . . . . 1 1 1 . . . . 1 .
    . . . . . . . . . . . . . . . .
`)
game.showLongText("Clouds", DialogLayout.Bottom)
effects.clouds.startScreenEffect()
pause(2000)
effects.clouds.endScreenEffect()
```

## Part 1
For this one, you're going to create multiple scenes that all have different things happen each time! But before you make the scenes, we need to add:
 - First, set a ``background color`` to make any effects you add appear more noticably!
 - Use a ``splash screen`` to let the player know what your scenes are all about! 

~hint Hint! Only use if you're stuck!
  Remember to use quotation marks "" inside the splash for the text you use!
hint~

## Part 2
Now it's time to make your first scene! Let's start with the basics!
 - First, to seperate the scenes, use a ``comment`` to mark it as the first scene!
 - Set the ``dialogue text color`` to customize the long text text color!
 - Then set the ``dialogue box frame`` to a new frame type!
 - Lastly for this part, add the ``long text`` itself to say whatever you want it to say for the first scene!

~hint Hint! Only use if you're stuck!
  Remember to comment with // before the comment! Also to check colors you can check the assets tab and click colors for each number!
hint~

## Part 3
Now before we make any more scenes, we're going to add a screen effect to pop up in the game!
 - Add a ``start screen effect`` to the game, any type you want!
 - Before ending the screen effect, make sure to add a ``pause`` so the screen effect has time to play!
 - Lastly, add an ``end screen effect`` so the effect doesnt play into other scenes!

~hint Hint! Only use if you're stuck!
  Make sure the "Bounce on Wall" code is set to "True" or else it wont bounce at all! And if you find yourself wanting the sprite to go left or up instead of always right, try changing the minimum on the "randint"s to negative numbers! (Ex. -100)
hint~

## Part 4
For the last step, it's time to make multiple scenes!
 - Either copy all the previous code or type out everything again for 2 more scenes!
 - Make sure to change the dialogue ``text color``, ``box frame``, ``text contents``, and ``screen effects`` to make a fun scene or story!

## Completed Challenge!
Good job! You completed the challenge! Now if you're ready! You can head onto the Third Orange Belt Challenge!