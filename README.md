# Piggy Bank Blitz

This is an arcade-style game made for Electron. The goal of the game is to move your Piggy Bank left and right and catch as much money as you can in 3 minutes.

**Game is not complete; please do not expect it to work until the 1.0.0 final release**

## The Coins

Throughout the 3-minute game, coins of various U.S. currency values (pennies, nickels, dimes, quarters, half-dollars, and dollars) will fall at different speeds. The goal is to catch as much money as you can in a piggy bank at the bottom of the screen, which you move with the Z and / keys on your keyboard. The coins will fall at faster speeds as time runs out.

## Powerups

Throughout the game, green powerup coins may also fall. Collecting a powerup coin with your piggy bank can give you a boost in the game. The following 10 powerups exist in the game:

**Mystery Coin**: The value of this coin will range between 1 and 200 cents.
**Coin Shower**: For 10 seconds, a significantly greater number of coins will fall on the playing field.
**Golden Piggy**: For 10 seconds, another piggy bank above yours (gold color), controlled by the computer, will help collect higher-value coins. Any coins it collects is added to your score.
**Lasers**: You will acquire 5 lasers, which you fire one at a time with the space key. Lasers quickly fire up from your piggy bank, collecting any coins they strike.
**Lightning**: The game freezes and all coins on the playing field at the time this powerup is collected will turn into the coin of the highest value. For example, if the highest-value coin on the screen is a quarter, all of the coins on the screen will be changed to a quarter. If only pennies are on screen, then instead, one of the pennies at random will be changed to a dollar coin. If no coins are on screen when the powerup is collected, then the next coin that appears will be a dollar coin. After the coins are transformed, the game resumes after a 3-second countdown.
**Magnet**: You will acquire 1 magnet, which you activate with the V key. When activated, all of the coins on screen get magnetically attracted above your piggy bank so you can collect them all (providing you don't move your piggy bank). This powerup works best when deployed during coin shower, after lightning, or during coin wave.
**Electro-piggy**: For 10 seconds, your piggy has an electric forcefield, drawing coins close by towards it for optimal catching.
**Clock Freeze**: The game clock freezes for 10 seconds while game play continues. Essentially, you get an additional 10 seconds in the game.
**Warp Speed**: For 5 seconds, the coins fall at very fast speeds, and your piggy bank also moves very fast, allowing for super-speed collecting.
**Coin Wave**: A line of coins will fall down the screen at the same speed, often with a few high-value coins. Can you place your piggy bank in the optimal spot to get the most money?

## Debuffs

Throughout the game, debuffs (red bad coins) will also fall and try to strike your piggy bank. Unlike powerups which fall straight down, debuffs fall at a faster speed and try to aim for where your piggy bank is. If a debuff manages to hit your piggy bank, it will activate. The following 10 debuff coins exist in the game:

**Devil Piggy**: For 10 seconds, like the Golden Piggy Powerup, another (red) piggy controlled by the computer will appear above yours and will try to collect the higher value coins. Unlike the Golden Piggy, you do not score any of the coins the Devil Piggy collects; its job is to try and prevent you from collecting coins, especially the higher value ones. (Tip: you can still use lasers to get past the devil piggy and shoot down high-value coins).
**Thief**: You lose a random amount of money between 1 and 200 cents.
**Paralysis**: For 10 seconds, you cannot move your piggy bank nor deploy any powerups.
**Penny Pincher**: For 10 seconds, only pennies will fall down.
**Square of Death**: For 10 seconds, a red square will appear on the screen. Any falling coins that touch the square burst into flames and disappear, unable to be collected.
**Confusion**: For 10 seconds, Z makes your piggy move right instead of left, / makes it move left instead of right.
**Cash Me Outside**: For 10 seconds, all coins on the screen will also move left/right in addition to falling, making it harder to catch them.
**Piggy Odor**: For 10 seconds, the piggy smells bad, causing coins that get close by to try and move away from it.
**Blind Ambition**: For 10 seconds, the values of all the coins become hidden.
**Hurrah Robber**: The Hurrah Multiplier will decrease by up to 2X. If it's only at 1X, the debuff does nothing.


WARNING!: Be cautious about the use of certain powerups such as lasers, magnets, and the electro piggy. Powerups do affect debuff coins (eg. shooting a debuff with a laser will activate it. The magnets / electro piggy will attract them towards your piggy).

## Star Coin

Star Coins are the ultimate powerups. Unlike other coins which fall straight down, star coins might move side to side to make it even harder to catch. But they carry big rewards when caught.

A star coin will fall at the 2-minute mark in the game. If you collect it, then the chances of getting higher-value coins will increase.

In addition, if you collected the first star coin, another one will drop at the 60-second mark. If collected, the value of all money collected for the remainder of the game (with the exception of the Last Hurrah, which is governed by its own multiplier) will be doubled on your score. For example, every dollar coin will score you 2 dollars.

Finally, if you collected the two star coins above, a third and final star coin will be hidden among the other coins in the Last Hurrah (read down about the Last Hurrah). If collected, you will receive a bonus on one of the types of coins collected, multiplied by your Hurrah Multiplier. For example, if the game chooses nickels for your bonus, and you collected 80 nickels in the game ($4) with a 5X hurrah multiplier, you will receive a $20 bonus.

## End of the Game / "Finishing Up"

When your time runs out, all coins on screen freeze and you can no longer move your Piggy Bank. 

If you have any remaining power-ups, they will be deployed. If you have any remaining magnets you did not use, they will be deployed one by one, collecting the coins on screen, and lowering a new set of coins onto the screen between each deployment. If you have any remaining lasers, the piggy bank will be moved by the computer to any coins remaining on the screen starting with the ones closest to the bottom. The computer will then fire off your remaining lasers and collect the coins they strike. If the screen is cleared before all the lasers are used up, the game will lower a new set of coins to fire at with the remaining lasers.

If you do not have any power-ups remaining at the end of the game, the coins remaining on screen will fall down in hopes your piggy bank is in a location it can catch a few.

## Last Hurrah / Hurrah Multiplier

Throughout the game, a few "X" coins will also fall. These are Hurrah Multiplier coins, and they are good (so try and catch them!). Every time you catch a Hurrah Multiplier coin, the Last Hurrah multiplier will increase by 1X.

After the "Finishing Up" stage when the game ends, the Last Hurrah begins where 12 coins of unknown values appear on the screen in random spots. Then, you have 7 seconds to move your piggy bank to wherever you want in hopes of collecting the most money. Once time runs out, your piggy bank freezes, the values of the mystery coins are revealed, and they fall down. Any coins that strike your piggy bank are collected, and their values are multiplied by the Hurrah Multiplier.

The game ends completely after the Last Hurrah. Your game statistics and final score will then appear on the screen.