# Assignment 3.1
### ROMICA RAISINGHANI(2021101053)
- Everything mentioned in the assignment has been implemented.
- **Bonus** :
    - King’s Leviathan Axe has also been implemented.
    - Dragon Character has been added, it can fly over walls.
    - Queen's Eagle Arrow has been added.
    - Movement avoiding walls has also been implemented.

- To run the game : `python3 game.py`
- To view replays : `python3 replay.py`  and select the replay you want to watch according to mentioned date and time.
- For Victory : All buildings apart from walls get destroyed from the map in all three levels.
- For Defeat : If all troops and King die before destroying all buildings apart from walls.

## Controls :

### Hero :

- w : move up
- a : move left
- d : move right
- s : move down
- 1 : Special Attack
- space : Normal Attack

### Barbarian :

- z : spawn at point 1
- x : spawn at point 2
- c : spawn at point 3

### Dragon :

- v : spawn at point 1
- b : spawn at point 2
- n : spawn at point 3

### Archer :

- i : spawn at point 1
- o : spawn at point 2
- p : spawn at point 3

### StealthArcher :

- 7 : spawn at point 1
- 8 : spawn at point 2
- 9 : spawn at point 3

### Healers :

- 4 : spawn at point 1
- 5 : spawn at point 2
- 6 : spawn at point 3

### Balloon :

- j : spawn at point 1
- k : spawn at point 2
- l : spawn at point 3

q : Quit Game

## Extensions

- StealthArchers and Healers have been added
- As part of bonus, levels are added for buildings, wizard towers, cannons and walls

### Assumptions

- When a healer is moving, it can't heal troops
- healers can't heal each other
- Each Healer will move towards the closest troop not at full health
- The limit of total number of archers applies to both normal and sneaky archers
- Level of the game decides level of building (2*level-1)
- Dead Troops cannot be healed
