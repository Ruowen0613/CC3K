#  ChamberCrawler3000（CC3K）


## Overview
This Dungeon-Crawler game is a custom project developed by Ruowen Wang, Yanran Zhang, and Yuhang Guo for the CS246 course at the University of Waterloo. Crafted with C++, this game offers an immersive rogue-like experience where players navigate through a dungeon with 5 floors, facing challenges and making strategic decisions to progress.

## Technical Highlights
- **Object-Oriented Principles**: Implements advanced concepts such as polymorphism and encapsulation, which are foundational to the game's architecture and logic.
- **Modern C++ Features**: Extensive use of smart pointers to manage memory efficiently, thereby mitigating the risk of memory leaks.
- **Factory Method Pattern**: This design pattern is crucial for the dynamic and random generation of game elements, contributing significantly to the system's maintainability and flexibility.
- **Dynamic Functionality with Virtual Functions**: Leveraging virtual functions to create a more dynamic and flexible interaction system within the game, allowing for easy expansion and modification of game mechanics.

## Controls
- **Movement**: `no, so, ea, we, ne, nw, se, sw` to move the player character one block in the corresponding direction.
- **Use Potion**: `u [direction]` to use a potion in a specified direction (e.g., `u no` for north).
- **Attack**: `a [direction]` to attack an enemy in the specified direction.
- **Select Race**: `s, d, v, t, g` to choose the player's race at the start of the game.
- **Restart Game**: `r` to restart the game.
- **Quit Game**: `q` to admit defeat and exit the game.

## Potions
### Positive Potions
- **Restore Health (RH)**: Restores up to 10 HP (not exceeding the maximum limit set by race).
- **Boost Attack (BA)**: Increases Attack (Atk) by 5.
- **Boost Defense (BD)**: Increases Defense (Def) by 5.

### Negative Potions
- **Poison Health (PH)**: Loses up to 10 HP (HP will not fall below 0).
- **Wound Attack (WA)**: Decreases Attack (Atk) by 5.
- **Wound Defense (WD)**: Decreases Defense (Def) by 5.:

## Game Interface Snapshot
The accompanying screenshot offers a glimpse into the intricate game dynamics and interface of ChamberCrawler3000.

<img width="576" alt="截屏2023-12-07 上午2 47 02" src="https://github.com/Ruowen0613/CC3K/assets/133537454/e9d9df08-32c7-4634-9da5-ecab09e23e9d">
