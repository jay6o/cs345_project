# Requirements & Assignments

| Group | Group | Group | Group |
| :-: | :-: | :-: | :-: |
| Tasks | Tasks | Tasks | Tasks |



## Current Requirements

- Tilemap
    - Logic map (collisions & boundaries)

- Sprites
    - Player sprites
    - Enemy sprites

- character object
    - Player subclass
    - Enemy subclass


## Different modules/units we will need

- Main game file (setup() and draw() calling lots of other files)
- Character
    - All have stats e.g. current HP, max HP, defense, inventory (list of current weapons), sprite
    - Movement stats (accel vector, velocity vector, location on map) + movement methods (update movement with time / friction, update accel, etc.)
    - Switch current weapon method, fire weapon, etc.
    - Player
          - Movement controlled by player
    - Enemy
          - Movement controlled by automatic pathfinding towards player
- Weapon
  - Held by Character objects
  - Different types - 5 weapons for player, enemy "weapon" that every enemy has 1 of (their fists as a Weapon object)
        - Unless we want do this differently and not have Enemies holding weapons but instead having some sort of intrinsic attack stat (either works)
  - Properties including fire rate, damage, mode of fire (single/burst/auto), etc.
  - Methods including fire weapon, etc.
- UI
  - To handle all I/O
  - Show map + characters on screen, show inventory, player HP, etc.
  - Handle input from keyboard and mouse and call appropriate methods
  - Menus? Pausing game? What else do we need in the UI?
- Map
  - Multiple maps? or just one?
  - Map class reading map file into memory? Or do we hard-code the map information into the program?
  - Methods for collision detection between character and map, etc. (or just like a .isValidLocation(Location) to check if a character can move somewhere)
- How (and where) do we implement levels / waves?
- What other modules do we need?
- Unit tests + integration tests for all of these modules and the whole game
