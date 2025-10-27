# UFO Parametric Cutter

An interactive web-based tool for designing and generating cutting patterns for UFO-shaped structures made from foam board panels. Inspired by [Manning Makes Stuff's 48in Flying Saucer](https://manningkrull.com/manningmakesstuff/48-flying-saucer-halloween-decoration)

Try it out here on GitHub Pages: [UFO Parametric Cutter](https://point-source.github.io/ufo/)

## Overview

This single-file HTML application allows you to design a UFO-shaped structure by adjusting various parameters and automatically generates:

- Interactive 3D previews (top-down and side views)
- Flat panel cutting patterns with exact dimensions
- Material counts and specifications
- Support for both metric (mm) and imperial (inches) units

## Features

- **Parametric Design**: Adjust diameters, heights, and panel counts to create custom UFO shapes
- **Real-time Visualization**: See top-down and side views that update as you change parameters
- **Panel Generation**: Automatically calculates trapezoid and rectangular panel dimensions
- **Unit Conversion**: Switch between metric (mm) and imperial (inches) measurements
- **Color Coding**: Visual color coding for different sections (top cone, upper cone, cylinder, lower cone)
- **Window Support**: Optional circular windows in the cylinder section
- **Material Specifications**: Designed for 5mm foam board with hand-fitting tolerances

## Structure

The UFO consists of four main sections:

1. **Top Cone**: Small diameter cap transitioning to main outer diameter
2. **Main Upper Cone**: Transitions from main outer to main inner diameter
3. **Cylinder**: Straight-walled section with optional windows
4. **Main Lower Cone**: Transitions from main inner back to main outer diameter

## Usage

1. Open `calc.html` in any modern web browser
2. Adjust the parameters in the control panels:
   - **Diameters**: Small diameter, main outer diameter, main inner diameter
   - **Heights**: Individual heights for each section
   - **Panel Counts**: Number of panels for small-top and main sections
   - **Windows**: Optional hole diameter for windows
   - **Colors**: Visual color coding for each section
3. View the real-time previews and cutting specifications
4. Use the generated dimensions to cut foam board panels
5. Assemble panels with tape or adhesive

## Default Specifications

- **Small Diameter**: 260mm (top cap)
- **Main Outer Diameter**: 410mm (cone transitions)
- **Main Inner Diameter**: 914mm (cylinder walls)
- **Material Thickness**: 5mm foam board
- **Panel Counts**: 16 small-top panels, 32 main panels
- **Window Diameter**: 25.4mm (1 inch)

## Technical Details

- **File Format**: Single HTML file with embedded CSS and JavaScript
- **Browser Compatibility**: Works in all modern browsers
- **Dependencies**: None - pure HTML/CSS/JavaScript
- **Calculations**: Uses geometric formulas for cone slant heights and arc lengths
- **Export**: Built-in SVG export functionality for cutting patterns

## Building Instructions

1. Cut foam board panels according to the generated dimensions
2. Small-top panels are triangular/trapezoid shapes
3. Main panels are trapezoid shapes
4. Cylinder panels are rectangular
5. Assemble panels in order: top cone → upper cone → cylinder → lower cone
6. Use tape or adhesive suitable for foam board
7. Add windows to cylinder panels if desired

## Customization

The tool supports extensive customization:

- Adjust any diameter or height parameter
- Change panel counts (minimum 3 panels per section)
- Modify colors for visual organization
- Add or remove windows
- Switch between metric and imperial units

## License

This project is open source. Feel free to modify and distribute according to your needs.

## Contributing

Contributions are welcome! Areas for improvement:

- Additional export formats
- More complex window patterns
- Assembly instructions generator
- Material optimization suggestions
- 3D visualization enhancements
