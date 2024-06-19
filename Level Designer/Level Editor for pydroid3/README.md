# Level Designer for pydroid3

[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNzUuNjAwMDAyMjg4ODE4MzYiIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAxNzUuNjAwMDAyMjg4ODE4MzYgMzUiPjxyZWN0IHdpZHRoPSI5Mi4xODMzMzQzNTA1ODU5NCIgaGVpZ2h0PSIzNSIgZmlsbD0iIzEwMTExMSIvPjxyZWN0IHg9IjkyLjE4MzMzNDM1MDU4NTk0IiB3aWR0aD0iODMuNDE2NjY3OTM4MjMyNDIiIGhlaWdodD0iMzUiIGZpbGw9IiNkY2Y1MTkiLz48dGV4dCB4PSI0Ni4wOTE2NjcxNzUyOTI5NyIgeT0iMjEuNSIgZm9udC1zaXplPSIxMiIgZm9udC1mYW1pbHk9IidSb2JvdG8nLCBzYW5zLXNlcmlmIiBmaWxsPSIjY2ViYmM5IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBsZXR0ZXItc3BhY2luZz0iMiI+QlVJTFQgQlkgPC90ZXh0Pjx0ZXh0IHg9IjEzMy44OTE2NjgzMTk3MDIxNSIgeT0iMjEuNSIgZm9udC1zaXplPSIxMiIgZm9udC1mYW1pbHk9IidNb250c2VycmF0Jywgc2Fucy1zZXJpZiIgZmlsbD0iIzE0MmNhNyIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZm9udC13ZWlnaHQ9IjkwMCIgbGV0dGVyLXNwYWNpbmc9IjIiPlBZVEhPTjwvdGV4dD48L3N2Zz4=)](https://forthebadge.com)

This is a simple python script to design levels for your games on pydroid3. It works best when your coding vertical non-scrollable platformer games using pydroid3.

![Alt text](app.png?raw=true "Level Designer")

The Level Editor Is A Non Scrollable And Works Best With 16x16 Tiles.

## Requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install following packages :-

* Pygame

```bash
pip install pygame
```

Note :- pygame is already installed on pydroid3. No need to install it, just import it.

## Usage

Run the main.py file to open the level editor. Click load to load prevoisuly designed levels. Click save to save your current level. Click cross to remove a tile from certain place. This tile editor can be used to create non scrollable games.

Instructions for using the Level Editor with your own tilemaps.

* Split the tilemap and put all the tile images in the tiles folder. Make sure you have less than 90 tiles.
* Set the number of tiles in NUM_TILES variable at line 29 in main.py
* Set level in current_level variable at line 30 in main.py. This should be a integer representing the level which you want to create / edit.
* Run the main.py file, click load to load level data ( currently empty ), click anywhere on the empty screen to highlight the tile.
* Now click any asset tile to set the tile, and start creating your level.
* Finally click save to save the level data in a pickle file.
* press back on pydroid3 or ESC on pc to quit the program.
  