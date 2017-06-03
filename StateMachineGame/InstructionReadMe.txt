AI Assignment 2 Instructions

Use the numpad arrows to select directions. Eg. 7 = Up, 9 = Up + Right, 6 = Right etc.
When prompted to move, select the direction you wish to move in, or press space to not move.
When prompted to choose an attack, use q,w,e,r,t or space:
	-q selects the normal attack - deal 4 dmg in selected direction, 0 mana cost
	-w selects the swipe attack - deal 4 dmg to selected direction, 2 dmg to each node adjacent to both the player and attack target node, 20 mana cost
	           e.g:	002     or:024
		0P4	0P2
		0P2	000
	-e selects the line attack - deal 4 dmg to selected direction, deal 2 dmg to the next 2 nodes in that direction, 20 mana cost
	           e.g:	000    or:	00000
		0P422	0P000
		000	00400
			00020
			00002
	-r selects the AOE attack - deal 2 dmg to each node surrounding you, 50 mana cost
	-t selects the heal self move - restore 20 of your health, 50 mana cost

Different enemies have different amounts of health, shown by their health bar
Knights (Grey), Archers (Brown) and Mages (blue) will move to attack you, and retreat to a healer if they have low health
Healers (yellow) stand still and heal other enemies each turn

At the moment there is no win or lose criteria, so falling to 0 health will not end the game.
Defeating all enemies will alos not end the game.

The console is used to tell you what states enemies are in, and when you should move/attack.
To close the game, please close the console.