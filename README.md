# MG3
## Devlog
1.The default values for floats,ints, bools and strings are 0 for floats and ints. For bool it is false and string you leave empty. 0 is used since it serves as a starting point. Bools are false since it also acts as a 0. The same applies for string since leaving it empty since nothing is assigned to it. 

2.The update method gets called since the game asks for it. The game engine is built to understand when to update.

3.Kickweapon uses the timer to make it dissapear within less than a second. When the player kicks, in the code it is set to where a timer starts for the kicking and runs until told to stop. This is why update is used especially in the code when putting the if statement. The if statement lets the game know what to do using what the timer is told to do.
https://pearl-carp.itch.io/mg3

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)