## Cub3D
Cub3D is a 3D game project inspired by the classic Wolfenstein 3D. It is developed using the MLX42 library for graphics rendering and includes both standard and bonus features.

Table of Contents

* Installation
* Usage
* Project Structure
* Features
* Credits

## Installation
To build and run the project, follow these steps:

Clone the repository: git clone https://github.com/yourusername/cub3d.git
cd cub3d

Build the project: make

Build the bonus version: make bonus

Usage
To run the game, use the following command: ./cub3D path/to/map.cub
Replace path/to/map.cub with the path to your map file.

## Project Structure
```
 cub3d/
├── assets/
│   ├── Bricks.png
│   ├── Coal.png
│   ├── east.png
│   ├── north.png
│   ├── Planks.png
│   ├── Sand.png
│   ├── south.png
│   ├── west.png
│   └── wolf/
├── bonus/
│   ├── casting_bonus.c
│   ├── dda_bonus.c
│   ├── errors_bonus.c
│   ├── freeing_bonus.c
│   ├── gamestate_bonus.c
│   ├── lines_bonus.c
│   ├── main_bonus.c
│   ├── movement_bonus.c
│   ├── parsing_utils_bonus.c
│   ├── player_data_bonus.c
│   ├── render_bonus.c
│   ├── scene_loading_bonus.c
│   ├── scene_parsing_bonus.c
│   ├── scene_utils_bonus.c
│   ├── scene_validation_bonus.c
│   └── textures_bonus.c
├── includes/
│   ├── cub3d_bonus.h
│   └── cub3d.h
├── libft/
│   ├── ft_printerror/
│   └── ...
├── maps/
│   └── example.cub
├── src/
│   ├── casting.c
│   ├── dda.c
│   ├── errors.c
│   ├── freeing.c
│   ├── gamestate.c
│   ├── lines.c
│   ├── main.c
│   ├── movement.c
│   ├── parsing_utils.c
│   ├── player_data.c
│   ├── render.c
│   ├── scene_loading.c
│   ├── scene_parsing.c
│   ├── scene_utils.c
│   ├── scene_validation.c
│   └── textures.c
├── Makefile
└── README.md
```

## Features

* Standard Features:
  -Basic 3D rendering using raycasting.
  -Player movement and collision detection.
  -Texture loading and rendering.
  -Bonus Features:

* Mini-map display.
  -Additional textures and assets.
  -Enhanced error handling and validation.
  
## Credits

* Authors:

  [Github] (https://github.com/Deivylex)
  
  [Github] (https://github.com/davidbarren)
  
* Libraries:
  
    - MLX42
  
    - libft
