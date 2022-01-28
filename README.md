# textGame

A simple but fun text adventure game! The user is put in a dungeon where they must battle an enemy. A string array contains the different potential enemies, and a random one is generated. The users health is set at 100, while the maximum possible health for the enemy is 75. The enemy health is a random number generated between 0 and 75. When the enemy is generated, your HP alongside the enemies HP is presented, and the user must decide if they will 

1. Attack
2. Drink health potion
3. Run!

If the user decides to attack, the damage dealt to the enemy is a random integer generated between 0 and 50. The enemyAttackDamage is set at a maximum of 25, and when the enemy retaliates, a random integer is generated between 0 and 25. The enemey and users health is presented with each hit. If the users health hits 0, the user is forced to exit. 

If the user chooses to drink a health potion, a loop will confirm that the player has at least 1 potion. If this is true, the users health will increase 30 points. The number of health potions the user has will also be subtracted. If the user does not have any potions, it will be told that they do not have any, but defeating an enemy gives the user a chance to recieve one.

If the user chooses 3, run, the game moves to next iteration of the loop and is set back to the menu. If the user enters an invalid command, i.e. anything that is not 1,2 or 3, the game presents an error message.

Once the enemy is (hopefully) defeated, there is a chance that it will drop a health potion! If this happens, the number of potions the user has increases by one. The user is also prompted if they want to either

1. continue fighting
2. Exit the dungeon

If they choose to fight, the game menu pops up again. If not, they are given a thank you note!

This was just a quick program, but there are many ways to improve it. Maybe two enemies can generate at once, you can add armor, you can aquire strength potions, etc!
