# Orange Belt Level 4 Challenge

```typescript
info.setScore(0)
game.splash("Either side needs 10 points to win!")
info.startCountdown(120)

let Mine = sprites.create(img`
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
    . . . . . . . 7 7 . . . . . . .
`, SpriteKind.Player)
Mine.setPosition(10, 60)

let Yours = sprites.create(img`
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . 2 2 . . . . . . .
`, SpriteKind.Enemy)
Yours.setPosition(150, 60)

let Ball = sprites.create(img`
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . 3 1 1 3 . . . . . .
    . . . . . 2 1 1 1 1 2 . . . . .
    . . . . . 2 1 1 1 1 2 . . . . .
    . . . . . . 3 1 1 3 . . . . . .
    . . . . . . . 2 2 . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
`, SpriteKind.Projectile)
Ball.setPosition(80,60)

controller.moveSprite(Mine, 0, 100)
Mine.setStayInScreen(true)
Yours.setStayInScreen(true)
Ball.setVelocity(randint(-100, 100), randint(-100, 100))
Ball.setBounceOnWall(true)

game.onUpdate(function() {
    if (Yours.y > Ball.y) {
        Yours.setVelocity(0, -50)
    } else if (Yours.y < Ball.y) {
        Yours.setVelocity(0, 50)
    }

    if(Ball.x > 150){
        info.changeScoreBy(1)
        Ball.setPosition(80, 60)
        Ball.setVelocity(randint(-100, -50), randint(-100, 100))
    } else if (Ball.x < 10) {
        info.changeScoreBy(-1)
        Ball.setPosition(80, 60)
        Ball.setVelocity(randint(-100, -50), randint(-100, 100))
    }
})

sprites.onOverlap(SpriteKind.Player, SpriteKind.Projectile, function(sprite: Sprite, otherSprite: Sprite) {
    otherSprite.vx = -otherSprite.vx
})
sprites.onOverlap(SpriteKind.Enemy, SpriteKind.Projectile, function (sprite: Sprite, otherSprite: Sprite) {
    otherSprite.vx = -otherSprite.vx
})

info.onScore(-10, function() {
    game.gameOver(false)
})

info.onScore(10, function () {
    game.gameOver(true)
})
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
Good job! You completed the challenge! Now if you're ready! You can head onto the Fifth Orange Belt Challenge!