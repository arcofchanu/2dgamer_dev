# 2dgamer_dev

A lightweight helper tool for game asset preprocessing – designed for Godot 4 and similar 2D game engines.

## Installation

```bash
pip install 2dgamer_dev
```

### Quick Usage

After installation, the following commands become available:

Slice a sprite sheet into individual frames
```bash
2dgamer slice assets/spritesheet.png --output frames/
Pack multiple images into a single tilemap atlas
```

```bash
2dgamer pack assets/tiles/ --output tilemap.tres
Convert audio files to Godot-compatible OGG format
```

```bash
2dgamer convert audio/*.wav --format ogg
```

Requirements
-Python 3.8 or higher
-Pillow (installed automatically)

License
MIT
