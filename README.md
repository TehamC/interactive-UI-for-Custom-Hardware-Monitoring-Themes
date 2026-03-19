# Theme Studio

A visual WYSIWYG editor for creating and editing themes for `turing-smart-screen-python`.

[> View full documentation in the wiki](https://github.com/mathoudebine/turing-smart-screen-python/wiki)

---

## What is Theme Studio?

Theme Studio is a visual editor that lets you design themes for your Turing Smart Screen without manually editing YAML files. It provides:

- **Drag and drop** positioning of all elements
- **Resize handles** on all elements for dimension adjustments
- **Color picker** for bar and text colors
- **Inspector panel** for precise numeric input
- **Real-time preview** with on-canvas element visualization
- **Auto-save** to `theme.yaml` on every change

## Quick Start

```bash
conda run -n turing python studio.py
```

Then open http://localhost:8765 in your browser.

## Features

| Feature | Description |
|---------|-------------|
| Visual Canvas | Drag elements directly on the display preview |
| Resize Handles | Resize elements by dragging the corners/edges |
| Color Picker | Pick colors directly from the palette |
| Inspector Panel | Edit X, Y, width, height, colors, and text values |
| Display Presets | Quick select common screen sizes (3.5", 5", 7") |
| Layer Panel | Manage element order and visibility |

## Supported Elements

- **Text** - Display sensor values with custom fonts
- **Graph bars** - Horizontal and radial progress bars
- **Background images** - Static images on the display

## Requirements

- Python 3.9+
- NiceGUI 3.8.0+
- PyYAML 6.0.3+

## Integration with Original Repo

This Theme Studio builds on top of the [turing-smart-screen-python](https://github.com/mathoudebine/turing-smart-screen-python) project by mathoudebine.

**Please refer to the original repository for:**

- System monitor setup and configuration
- All available sensor types and stats
- Hardware compatibility
- Troubleshooting guides

## Author

Theme Studio developed by TehamC

Theme design by Gemini & User
