# TexturePacker/ShoeBox Importer

This is a plugin for [Godot Engine](https://godotengine.org) to import
`TileSet`s and `AtlasTexture`s from [TexturePacker](https://www.codeandweb.com/texturepacker) and [ShoeBox](https://renderhjs.net/shoebox/)

**Note: This is compatible only with Godot 3.0 or later.**


## Installation

Download or clone this repository and copy the contents of the
`addons` folder to your own project's `addons` folder.

ShoeBox users: double click TexturePacker-GodotImporter.sbx to load the appropiate config when creating your atlasses. 
TexturePacker users: use "Godot Spritesheet" or "Godot TileSet" when creating your atlasses

Important: Enable the plugin on the Project Settings.

## Features

* Import sprite sheets as AtlasTextures
* Import sprite sheets as TileSets
* Supports trimmed sprites (margin)
* Supports MultiPack

## Usage (once the plugin is enabled)

1. Save your sprite sheets / tile maps in your project folder
2. Watch Godot import it automatically.

## License

[MIT License](LICENSE). Copyright (c) 2018 Andreas Loew / CodeAndWeb GmbH
TexturePacker-GodotImporter.sbx based on https://github.com/piratesephiroth/GodotTexturePackerShoeBoxConfig (MIT Licensed)
