# The Legend of Damopies

## Description

A C RPG inspired by *The Legend of Zelda*. Explore the world, fight enemies, interact with NPCs, and manage your inventory.

## Requirements

- Linux with `gcc`, `make`, and the development version of libc (`libc6-dev`)
- CSFML 2.5 : `libcsfml-dev`
- The CSFML Graphics, Window, System, and Audio modules

On Debian/Ubuntu:

```bash
sudo apt update
sudo apt install build-essential libc6-dev libcsfml-dev
```

## How to run

Depuis la racine du projet :

```bash
make
./my_rpg
```

To remove the build files and executable:

```bash
make fclean
```

## Controls

- `ZQSD`: move
- `F`: interact
- `Space`: attack
- `E`: open the inventory
- `Escape`: pause the game

Controls can be changed in the game settings.
