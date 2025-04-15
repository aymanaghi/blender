# 🎮 Blender Keybinds Reference Project

A comprehensive reference guide for Blender keyboard shortcuts, customization options, and keybinding management.

> From basic navigation to advanced workflows — mastering Blender one shortcut at a time.

## 📋 Table of Contents
- [Introduction](#introduction)
- [Default Keybinds](#default-keybinds)
  - [General Interface](#general-interface)
  - [3D Viewport Navigation](#3d-viewport-navigation)
  - [Selection](#selection)
  - [Modeling (Edit Mode)](#modeling-edit-mode)
  - [Animation](#animation)
  - [Sculpting](#sculpting)
- [Customizing Keybinds](#customizing-keybinds)
- [Keymap Presets](#keymap-presets)
- [Importing & Exporting Keymaps](#importing--exporting-keymaps)
- [Advanced Workflows](#advanced-workflows)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [License](#license)

## 🚀 Introduction

Blender's keyboard shortcut system is powerful but can be complex to master. This project aims to document and simplify Blender's keybinding system, making it more accessible to users of all experience levels.

Blender allows extensive customization of its interface and controls, including full remapping of keyboard shortcuts. This project serves as both a reference and potentially a foundation for tools to better manage these customizations.

## ⌨️ Default Keybinds

### General Interface
- **Spacebar**: Search menu
- **F1**: Help menu
- **Ctrl+Space**: Maximize area
- **Ctrl+Alt+Space**: Full screen/return from full screen
- **F2**: Rename selected item
- **F3**: Search menu (alternative)
- **F4**: File context menu
- **F5-F8**: Variable based on context
- **F9**: Adjust last operation
- **F11**: Show render
- **F12**: Render
- **Ctrl+N**: New file
- **Ctrl+O**: Open file
- **Ctrl+S**: Save file
- **Ctrl+Shift+S**: Save as
- **Ctrl+Q**: Quit Blender
- **Ctrl+Z**: Undo
- **Ctrl+Shift+Z**: Redo
- **Tab**: Toggle edit/object mode

### 3D Viewport Navigation
- **Middle Mouse Button**: Rotate view
- **Shift+Middle Mouse Button**: Pan view
- **Mouse Wheel**: Zoom view
- **Numpad 1**: Front view
- **Numpad 3**: Side view
- **Numpad 7**: Top view
- **Numpad 5**: Toggle perspective/orthographic
- **Numpad 0**: Camera view
- **Numpad .**: Focus on selected
- **Numpad /**: Isolate selected/restore
- **Z**: Shading mode menu

### Selection
- **Right Click** (default) or **Left Click** (can be changed in preferences): Select
- **A**: Select all
- **Alt+A**: Deselect all
- **Ctrl+I**: Invert selection
- **B**: Box select
- **C**: Circle select
- **Shift+Click**: Add to selection
- **Ctrl+Click**: Remove from selection

### Modeling (Edit Mode)
- **E**: Extrude
- **S**: Scale
- **R**: Rotate
- **G**: Grab/move
- **Ctrl+R**: Loop cut
- **K**: Knife tool
- **I**: Inset
- **Ctrl+B**: Bevel
- **X/Delete**: Delete menu
- **F**: Create face/edge
- **Alt+M**: Merge menu
- **Ctrl+J**: Join
- **P**: Separate

### Animation
- **Spacebar**: Play Animation
- **I**: Insert Keyframe
- **Alt+I**: Delete Keyframe
- **Left/Right Arrow**: Move Frame Timeline
- **Shift+Left/Right Arrow**: Go to Start/End
- **Ctrl+Tab**: Graph Editor (or switch editors manually)
- **Shift+F12**: Dope Sheet
- **T** (in Graph Editor): Set Interpolation Mode
- **M**: Add Marker
- **Shift+S**: Snap to Frame

### Sculpting
- **Ctrl+Tab → Choose "Sculpt Mode"**: Enable Sculpt Mode
- **F**: Brush Size
- **Shift+F**: Brush Strength
- **Shift**: Smooth Brush (temporarily)
- **Ctrl**: Invert Brush
- **X** (in tool settings): Symmetry Toggle
- **Ctrl+D**: Dynamic Topology (then enable in menu)
- **Ctrl+R**: Remesh (if using voxel remesh)

## 🔧 Customizing Keybinds

Blender allows you to fully customize its keybindings through the Preferences window:

1. Open Preferences: **Edit > Preferences** or **F4 > Preferences**
2. Select the **Keymap** section
3. Browse through the category tree to find commands
4. Click on a keybind to edit it
5. Press the new key combination to assign it

### Keymap Editor Components:

- **Keymaps section**: Lists the various modes and tools in Blender
- **Items list**: Shows the specific actions and their key assignments
- **Key-binding controls**: Interface for changing or removing bindings
- **Restore button**: Resets to default values

## 📦 Keymap Presets

Blender comes with several keymap presets to accommodate users coming from other software:

- **Blender (default)**: The standard Blender keymap
- **Blender 2.7x**: Legacy keymap from older versions
- **Industry Compatible**: Designed to be more familiar to users of other 3D software
- **Blender 27x**: Classic Blender keymapping style

To change presets:
1. Open Preferences > Keymap
2. Select a preset from the dropdown menu

## 💾 Importing & Exporting Keymaps

### Export Your Keymap
1. Open Preferences > Keymap
2. Click "Export" button
3. Choose a location and filename (*.py)
4. Save the file

### Import a Keymap
1. Open Preferences > Keymap
2. Click "Import" button
3. Navigate to and select a keymap file
4. Confirm the import

## 🔍 Advanced Workflows

### Creating a Custom Keymap for Specific Tasks
1. Start with a base preset
2. Modify commonly used functions
3. Export the custom keymap
4. Document your changes

### Setting Up Task-Specific Keymaps
Some users maintain different keymaps for:
- Modeling
- Animation
- Sculpting
- Video editing

### Recommended Add-ons That Enhance Keybinds
- **Pie Menu Editor**: Create custom pie menus for faster access
- **Keyboard Layout**: Display current keyboard shortcuts on screen
- **Auto-Rig Pro**: Adds specialized keybinds for character rigging

## 📁 Repository Structure

```
/BlenderKeybinds
│
├── 📁keymaps
│   ├── default_keymap.py
│   ├── animation_focused.py
│   ├── sculpting_focused.py
│   └── modeling_focused.py
│
├── 📁cheatsheets
│   ├── animation_cheatsheet.pdf
│   ├── sculpting_cheatsheet.pdf
│   ├── modeling_cheatsheet.pdf
│   ├── animation_darkmode.pdf
│   ├── sculpting_darkmode.pdf
│   └── hotkeys_masterlist.md
│
├── 📁resources
│   ├── keymap_editor_guide.md
│   ├── recommended_addons.md
│   └── workflow_tips.md
│
├── 📁scripts
│   └── keymap_converter.py  # For converting between formats
│
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

## 👥 Contributing

Contributions to this project are welcome! Here's how you can help:

1. **Document new shortcuts**: As Blender evolves, help keep this reference up-to-date
2. **Share custom keymaps**: Add your optimized keymaps to our collection
3. **Improve documentation**: Clarify explanations and add examples
4. **Report issues**: Let us know about inaccuracies or missing information
5. **Create dark mode cheat sheets**: Help make our PDFs more accessible

Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed guidance.

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the file for details.

---

**Project maintained by: [Your Name/Username]**

Last updated: April 2025
