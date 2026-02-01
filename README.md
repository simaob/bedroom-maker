# 🏠 Bedroom Designer

A simple, interactive web-based tool for designing and planning bedroom layouts. Draw walls, add furniture, windows, and doors with precise measurements.

## Features

### 🎨 Drawing Tools
- **Walls** - Draw room boundaries with exact dimensions
- **Doors** - Add doors with swing arc visualization
- **Windows** - Place windows on walls
- **Built-in Wardrobes** - Add closets and storage
- **Radiators** - Mark heating element positions
- **Beds** - Place beds with customizable dimensions
- **Bookshelves** - Add shelving units
	- **Dimensions** - Measure distances between points
- **Markers** - Add labeled points (switches, outlets, etc.)

### ✨ Key Capabilities
	- **Precise Measurements** - All elements show dimensions in meters
	- **Grid Snapping** - 10cm precision for accurate placement
	- **Drag & Drop** - Move furniture by dragging selected items
- **Editable Dimensions** - Adjust sizes after placement (e.g., 3.082m walls)
	- **Label Control** - Show/hide dimension labels per element
	- **Save/Load** - Export and import designs as JSON files
	- **Undo** - Step back through changes

### 🎯 Usage

	1. **Select a tool** from the left sidebar
	2. **Click on the canvas** to start drawing
	3. **Click again** to finish the element
	4. **Select an element** from the right panel to edit its properties
	5. **Drag furniture** to reposition after selection
	6. **Press ESC** or right-click to cancel/deselect

### 💾 Keyboard Shortcuts
	- `ESC` - Cancel current action or deselect element
	- Right-click - Same as ESC

### 📐 Scale
	- **100 pixels = 1 meter**
	- Grid snaps to 10cm intervals
	- All measurements displayed with 3 decimal precision

## Getting Started

	Simply open `index.html` in any modern web browser. No installation or build process required.

## Saving & Loading

	Use the **Save** button to export your bedroom design as a JSON file. The **Load** button allows you to import previously saved designs and continue editing.

## Tips

	- Design walls first to establish room boundaries
	- Use the dimension tool to measure distances
	- Toggle labels off for cleaner views
	- Select furniture to adjust both length and width
	- Use markers to note electrical fixtures and switches

	---

	Built with vanilla HTML, CSS, and JavaScript • No dependencies required
