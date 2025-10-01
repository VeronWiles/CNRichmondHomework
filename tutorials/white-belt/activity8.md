# White Belt Level 8 Challenge

## Part 1
For this final challenge, we're going to put together a full game using tons of blocks you've learned! No restrictions on blocks this time! Here's everything we need in the On Start Block!
 - Add a ``Splash`` Screen! To inform the player about the game!
 - ``Make`` the player, then start them at a ``random position``! As well as making sure they can ``move`` around while ``staying in the
 - Now ``make`` the ``food`` sprite, and have it both start in a ``random`` position and make it's ``velocity is random`` as well! Make sure it can ``bounce`` on walls!
 - Remember to set the ``score, life, and countdown`` variables too!
 - Lastly, create a ``melody`` that plays ``looping in the background`` as background music for your game!
 
## Part 2
Next, let's make the On Game Update Block for when the enemy spawns!
 - Set the update to spawn an enemy every few seconds. (How many is up to you!)
 - ``Create`` a basic ``enemy`` and make sure it's ``position is random`` on the screen!
 - In an ``If/Else`` block we want to check a ``chance`` for a normal enemy!
 - In the If part, we want to say if the chance is true, we should ``animate the enemy's image`` and set them to ``follow`` the food at a normal speed.
 - But if the chance is not true, in the else section, we want to make a super enemy! That ``Animates`` it's image faster and ``follows`` the food at a higher speed!

## Part 3
Now we need code for when the A Button is pressed!
 - ``Create`` a projectile that comes from  the ``player sprite``` and doesnt move.
 - To make it move we're going to make it ``follow`` the enemy sprite!


## Part 4
Next is the code for what the player overlaps with the food sprite!
 - ``Add 1`` to the score!
 -  Then make sure the ``other sprite`` which should be the ``food`` changes to a ``random position`` with a ``random velocity``!

## Part 5
Let's make sure we can win or lose the game once the countdown ends!
 - We need to check ``If/Else`` the ``score`` is ``equal to or greater than`` however many points you want!
 - If so, create a ``game over effect`` for winning and ``end the game`` with a win!
 - If not, create a ``game over effect`` for losing and ``end the game`` with a losing it!

## Part 6
Now we need to check what happens when the player overlaps with the enemy sprite!
 - We should ``play a sound`` to highlight it!
 - Then ``remove 1`` from life!
 - Lastly, make sure you ``destroy`` the enemy (or ``othersprite``) you run into!

## Part 7
Make sure to add code for what happens when the Enemy overlaps with the food now, if it beats you to the food!
 - ``Change the score`` by a big amount to punish the player!
 - Then make sure you ``destroy`` the ``enemy sprite``
 - And set the food (or ``othersprite``) to a ``random position and velocity``!

## Part 8
Now, let's have the game end when the player runs out of lives!
 - Just set a ``game over effect`` for losing and have it so the player ``loses the game``!

## Part 9
Lastly, Set simply code for if the projectile sprite overlaps with the enemy sprite!
 - Just ``destroy`` both the enemy sprite and the projectile sprite! (Or ``sprite`` and ``othersprite``!)

## Completed Challenge!
Good job! You completed all of the challenges! Now you're ready to move on to Yellow Belt!