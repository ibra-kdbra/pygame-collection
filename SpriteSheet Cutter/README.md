# Spritesheet Cutter

Image Cutter & Resizer is a simple python tkinter based application to resize, cut and divide spritesheets

![Alt text](app.png?raw=true "Spritesheet Cutter")

## How to Download

Download this project from here [Download Spritesheet Cutter]

## Requirements

Pillow : Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Pillow.

```bash
pip install pillow
```

## Usage

Double click the application.py to open the GUI application, then open a spritsheet, resize or scale it using the scaler at the bottom

Currently you can divide the spritesheet by following 4 mechanisms

* By tile size - divides the image in number of tiles of equal size
* By rows & Columns - divides the image in given number of rows and columns
* By custom coordinates - divides or crops the image based on the coordinates provided.
* By Rectangle - extension of cropping based on custom cordinates. To use this features select anywhere on the image to start selecting the rectangular part.
