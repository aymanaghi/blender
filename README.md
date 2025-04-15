# blender
🎞️ Animation Shortcuts

    Play Animation – Spacebar

    Insert Keyframe – I

    Delete Keyframe – Alt + I

    Move Frame Timeline – Left/Right Arrow

    Go to Start/End – Shift + Left/Right Arrow

    Graph Editor – Ctrl + Tab (or switch editors manually)

    Dope Sheet – Shift + F12

    Set Interpolation Mode – T in Graph Editor

    Add Marker – M

    Snap to Frame – Shift + S

🧱 Sculpting Shortcuts

    Enable Sculpt Mode – Ctrl + Tab → Choose "Sculpt Mode"

    Brush Size – F

    Brush Strength – Shift + F

    Smooth Brush (temp) – Shift

    Invert Brush – Ctrl

    Symmetry Toggle – X (in tool settings, not hotkey by default)

    Dynamic Topology – Ctrl + D (then enable in menu)

    Remesh – Ctrl + R (if using voxel remesh)

# 🌀 BlenderGlowUp – My 3D Journey

This repo tracks my personal progress in Blender – from sculpting my first donut to animating full walk cycles. I’m using this space to share cheat sheets, tips, and project files that helped me improve.

## ✨ Goals
- Master character animation
- Improve sculpting anatomy
- Share useful resources

## 🎮 Cheat Sheets
- [Animation Shortcuts](./cheatsheets/animation_cheatsheet.pdf)
- [Sculpting Shortcuts](./cheatsheets/sculpting_cheatsheet.pdf)

## 🛠️ Tools I Use
- Blender 3.x
- Plugins: Rigify, LoopTools, Dynamic Topology




/BlenderMastery (or /BlenderGlowUp – your call)
│
├── 📁cheatsheets
│   ├── animation_darkmode.pdf ✅
│   ├── sculpting_darkmode.pdf ✅
│   └── hotkeys_masterlist.md
│
├── 📁projects
│   ├── 2023_donut.blend
│   ├── 2024_walkcycle.blend
│   └── future/ ⤵️
│       └── character_animation.blend
│
├── 📁screenshots
│   ├── donut_before.png
│   └── donut_after.png
│
├── 📁resources
│   ├── links.md  ← YT tutorials, blogs, etc.
│   ├── add-ons.md ← your fav add-ons + settings
│   └── workflow_tips.md ← your personal Blender hacks
│
├── README.md
└── LICENSE (MIT, maybe)






# 🌑 Blender Mastery – My 3D Learning Vault

Welcome to my personal Blender archive. Whether you're just starting out or deep in the game, this repo is stacked with cheat sheets, project files, tips, and my journey of learning 3D.

> 🧠 From donut to dream scene — one keyframe at a time.

## 📌 What's Inside

- 🔥 Dark Mode Cheat Sheets (Animation, Sculpting)
- 💾 My .blend files (failures & glow-ups)
- 🧰 Add-ons and workflow tips
- 📸 Before & After screenshots of progress

## 🛠 Tools I Use

- Blender (obviously)
- Add-ons: Rigify, LoopTools, Auto-Rig Pro
- Keyboard shortcuts are life – see `cheatsheets/`

## 💡 My Why

I made this repo to:
- Track my own improvement
- Help others avoid the Blender learning curve
- Share dark-mode PDF cheat sheets with love

## 🖤 Made with patience, late nights, and Ctrl+Z




![ChatGPT Image Apr 7, 2025, 10_32_12 PM](https://github.com/user-attachments/assets/f1d65628-aec6-4840-957d-7f8d95f2c651)










# Blender Keybinds Reference Project

A comprehensive reference guide for Blender keyboard shortcuts, customization options, and keybinding management.

## Table of Contents
- [Introduction](#introduction)
- [Default Keybinds](#default-keybinds)
- [Customizing Keybinds](#customizing-keybinds)
- [Keymap Presets](#keymap-presets)
- [Importing & Exporting Keymaps](#importing--exporting-keymaps)
- [Common Workflows](#common-workflows)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Blender's keyboard shortcut system is powerful but can be complex to master. This project aims to document and simplify Blender's keybinding system, making it more accessible to users of all experience levels.

Blender allows extensive customization of its interface and controls, including full remapping of keyboard shortcuts. This project serves as both a reference and potentially a foundation for tools to better manage these customizations.

## Default Keybinds

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

## Customizing Keybinds

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

## Keymap Presets

Blender comes with several keymap presets to accommodate users coming from other software:

- **Blender (default)**: The standard Blender keymap
- **Blender 2.7x**: Legacy keymap from older versions
- **Industry Compatible**: Designed to be more familiar to users of other 3D software
- **Blender 27x**: Classic Blender keymapping style

To change presets:
1. Open Preferences > Keymap
2. Select a preset from the dropdown menu

## Importing & Exporting Keymaps

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

## Common Workflows

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

## Contributing

Contributions to this project are welcome! Here's how you can help:

1. **Document new shortcuts**: As Blender evolves, help keep this reference up-to-date
2. **Share custom keymaps**: Add your optimized keymaps to our collection
3. **Improve documentation**: Clarify explanations and add examples
4. **Report issues**: Let us know about inaccuracies or missing information

Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed guidance.

## License

This project is licensed under the [MIT License](LICENSE) - see the file for details.

---

**Project maintained by: [Your Name/Username]**

Last updated: April 2025

