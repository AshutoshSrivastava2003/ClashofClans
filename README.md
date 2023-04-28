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

### Balloon :

- j : spawn at point 1
- k : spawn at point 2
- l : spawn at point 3

### Stealth Archer :

- t : spawn at point 1
- y : spawn at point 2
- u : spawn at point 3

### Healer :

- e : spawn at point 1
- f : spawn at point 2
- g : spawn at point 3

The healer heals in a radius of 7, while the AOE is in a square of 3x3

q : Quit Game

## Assumptions :

- Rage and Heal Spell can be applied multiple times.
- The limit for troops in each level is as follows :
    'barbarian': 10,
    'dragon': 15,
    'balloon': 15,
    'archer': 10,
    'stealth archer':10,
    'healer':10
- You have to choose the type of troop movement at start of the game.
- You have to choose the hero after each level.

The level of walls, cannons, wizard tower are level 1, 3 ,5 in the game 3 game levels respectively.
