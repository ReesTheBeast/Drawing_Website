# Canvas Drawing App

A simple yet powerful drawing application built with HTML, CSS, and JavaScript, all combined into a single `index.html` file. This app allows users to create digital art on a canvas, offering features like adjustable brush sizes, color selection, and symmetry tools for creative designs.

## Features

### Core Features
- **Freehand Drawing**: Draw on the canvas with a smooth brush.
- **Adjustable Brush Size**: Increase or decrease the brush size with intuitive buttons.
- **Color Picker**: Choose from a wide range of colors to customize your brush.
- **Clear Canvas**: Erase the entire canvas with a single click.
- **Save Artwork**: Download your creations as PNG files.

### Unique Feature
- **Mirror Drawing Mode**: 
  - Toggle a symmetry tool that mirrors your strokes across the vertical axis in real time.
  - Perfect for creating symmetric designs, mandalas, and patterns.

## How to Use

1. **Start Drawing**:
   - Click and drag on the canvas to draw.
2. **Adjust Brush Size**:
   - Use the `+` and `-` buttons to increase or decrease the brush size (min: 5, max: 50).
3. **Select a Color**:
   - Use the color picker to set your desired brush color.
4. **Clear Canvas**:
   - Press the `X` button to clear the canvas.
5. **Save Artwork**:
   - Press the `Save` button to download your drawing as a PNG file.
6. **Mirror Mode**:
   - Toggle the `Mirror` button to enable or disable symmetrical drawing.

## Installation and Setup

No installation is required. Simply:

1. Download or clone this repository:
   ```bash
   git clone https://github.com/yourusername/canvas-drawing-app.git
Open the index.html file in any modern web browser.
File Structure
bash
Copy code
canvas-drawing-app/
│
├── index.html       # Single file containing HTML, CSS, and JavaScript
├── background.jpg   # Background image for the canvas
└── README.md        # Documentation file
Technologies Used
HTML: For the structure of the app.
CSS: For styling the layout and toolbox (embedded in <style> tags).
JavaScript: For canvas drawing logic and interactivity (embedded in <script> tags).
