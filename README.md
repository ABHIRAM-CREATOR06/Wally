# Wally - Pillar Wallpaper Creator

```
▄▄▄▄  ▄▄▄  ▄▄▄▄   ▄▄▄▄   ▄▄▄      ▄▄▄      ▄▄▄   ▄▄▄
▀███  ███  ███▀ ▄██▀▀██▄ ███      ███      ███   ███
 ███  ███  ███  ███  ███ ███      ███      ▀███▄███▀
 ███▄▄███▄▄███  ███▀▀███ ███      ███        ▀███▀
  ▀████▀████▀   ███  ███ ████████ ████████    ███
```

The complete wallpaper solution - a web-based tool for creating custom wallpapers featuring stacked pillar designs. Generate high-resolution wallpapers with customizable colors, shapes, gradients, and layouts.

## Features

### Core Functionality
- **Canvas Ratios**: Choose from 16:9, 4:3, 1:1, 21:9, or 9:16 aspect ratios
- **Background Options**: Solid colors or linear gradients (vertical, horizontal, or diagonal)
- **Pillar Customization**:
  - Adjustable pillar count (3-12)
  - Individual pillar colors
  - Shape options: Rounded rectangles, circles, or triangles
  - Configurable width, height, roundness, overlap, and shading
- **Layout Controls**: Stack order reversal and horizontal/vertical orientation flipping
- **Presets**: Pre-built color schemes including Classic, Light, Dark, and Pastel themes
- **Randomization**: Generate themed color palettes with monochrome, analogous, complementary, triadic, or split-complementary schemes

### Advanced Features
- **Direct Manipulation**: Click and drag pillars to reorder colors (Shift+click for reordering)
- **Undo/Redo System**: Full history with Ctrl+Z/Ctrl+Y support
- **Project Management**:
  - Save/load projects to browser local storage
  - Import/export configuration files (JSON)
  - Shareable links with encoded settings
- **Keyboard Shortcuts**:
  - `Ctrl+Z`: Undo
  - `Ctrl+Y`: Redo
  - `Ctrl+S`: Export config
  - `Ctrl+E`: Export image
  - `Ctrl+R`: Reset
  - `Ctrl+I`: Import config
  - `Escape`: Exit fullscreen
- **Fullscreen Preview**: View designs in fullscreen mode
- **Export Options**:
  - Resolutions: 1080p, 4K, 8K, or custom
  - Formats: PNG, JPG, SVG
  - High-quality rendering for large exports

### Technical Details
- Single HTML file with embedded CSS and JavaScript
- No external dependencies
- Responsive design with mobile support
- Canvas-based rendering with fallback support
- Local storage for project persistence
- URL-based configuration sharing

## Usage

1. **Getting Started**:
   - Open `index.html` in a modern web browser
   - The app loads with default settings

2. **Customization**:
   - Use the left panel to adjust canvas ratio and background
   - Modify pillar properties in the right panel
   - Click on pillar swatches to change individual colors
   - Shift+click and drag pillars to reorder them

3. **Exporting**:
   - Select desired resolution and format
   - Click "Export" to download the wallpaper
   - SVG exports are vector-based and scalable

4. **Saving Work**:
   - Use "Save Project" to store in browser local storage
   - "Export Config" creates a JSON file for backup
   - Share the generated link to share your design

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

Requires canvas support and modern JavaScript features.

## File Structure

```
wally/
├── index.html          # Main application file
├── README.md           # This file
└── (optional screenshots)
```

## Contributing

This is a single-file web application. To contribute:

1. Fork the repository
2. Make changes to `index.html`
3. Test thoroughly across different browsers
4. Submit a pull request

## License

MIT License - see LICENSE file for details.

## Credits

Created as a demonstration of HTML5 Canvas and modern web technologies.
