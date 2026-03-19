# Interactive UI Theme Studio

This directory contains a **visual theme editor** and a custom theme for `turing-smart-screen-python`.

## What's New

| Feature | Description |
|---------|-------------|
| **Theme Studio** (`studio.py`) | Visual WYSIWYG editor for editing `theme.yaml` files with drag-and-drop positioning |
| **Interactive Preview** | Real-time canvas with SVG overlays for element visualization and resizing |
| **Custom Theme** (`1_IUI/`) | A polished theme showcasing the editor's capabilities |

## Theme Studio Features

- **Drag & drop** positioning of all elements (text, graphs)
- **Resize handles** on all elements for dimension adjustments
- **Color picker** for bar and text colors
- **Inspector panel** for precise numeric input
- **Auto-save** to `theme.yaml` on every change
- **Display presets** for common screen sizes (3.5", 5", 7")

## Usage

```bash
# Activate conda environment (if using turing env)
conda run -n turing python studio.py
```

Then open http://localhost:8765 in your browser.

## Requirements

- Python 3.9+
- NiceGUI 3.8.0+
- PyYAML 6.0.3+

## Integration with Original Repo

This theme builds on top of the [turing-smart-screen-python](https://github.com/mathoudebine/turing-smart-screen-python) project. Please refer to the parent repository for:

- System monitor setup and configuration
- All available sensor types and stats
- Hardware compatibility
- Troubleshooting guides

## Author

Theme Studio developed by TehamC
Theme design by Gemini & User
