# SpriteFrames Generator from Sprite Sheets

A Godot Engine plugin to automatically generate `SpriteFrames` resources from sprite sheets.

## Features
- Import sprite sheets and automatically slice them into frames
- Generate `SpriteFrames` resources for use in animations
- Customizable slicing and configuration options
- Inspector UI for easy configuration

## Installation
1. Copy the `addons/sprite_frames_generator` folder into your Godot project's `addons` directory.
2. Enable the plugin in your project settings under `Project > Project Settings > Plugins`.

## Usage
1. Open the Inspector UI from the Godot editor.
2. Add your sprite sheets and configure slicing options.
3. Generate `SpriteFrames` resources for use in your project.

## Folder Structure
```
addons/
  sprite_frames_generator/
    plugin.cfg
    plugin.gd
    inspector_ui_scene/
      inspector_ui_scene.gd
      inspector_ui_scene.tscn
    sprite_sheet_generator_config/
      sprite_sheet_entry.gd
      sprite_sheet_generator_config.gd
      sprite_sheet_generator_config.tres
sprite_frames_sheet_generator_output/
```

## Contributing
Pull requests and suggestions are welcome!

## License
MIT License
