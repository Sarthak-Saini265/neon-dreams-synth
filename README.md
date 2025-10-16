# neon-dreams-synth

## Summary

Create Neon Dreams Synth - a visual music toy where clicking creates colorful orbs that make musical notes!

CONCEPT: Click to spawn glowing neon orbs at different Y positions = different musical notes (higher = higher pitch). Orbs glow, pulse to their note, and leave trailing light. It's like painting music with light.

VISUALS: Pure black background. Each orb is a glowing neon sphere (random neon colors: cyan, magenta, yellow, lime). Orbs pulse rhythmically. Light trails fade behind them. When orbs collide, they bounce and harmonize.

SOUND: Use Web Audio API. Y-position = pitch (top=high notes, bottom=low notes). Each orb plays its note on loop while alive. Different colors = different instruments (sine, square, triangle waves).

INTERACTION: Click = spawn orb. Orbs float slowly and bounce off edges. They live for 8-10 seconds, fading out. Can have 20+ orbs playing together creating ambient music.

UI: Minimal top corner - 'Clear All' button. Show active orbs count. That's it.

VIBE: Cyberpunk meets music toy. Mesmerizing, creative, sounds beautiful. Like Plink but neon and spatial.

## Features

This application was automatically generated to meet the following requirements:

- Black background
- Click spawns glowing neon orbs
- Y-position determines pitch
- Orbs play musical notes
- Multiple neon colors (cyan/magenta/yellow/lime)
- Orbs pulse to their rhythm
- Light trails behind orbs
- Orbs bounce off screen edges
- Orbs fade after 8-10 seconds
- Web Audio API for sound
- Different colors = different waveforms
- Shows active orb count
- Clear button
- Smooth 60fps canvas animation

## Setup

This is a static web application that requires no build process.

### Local Development

1. Clone this repository
2. Open `index.html` in a web browser
3. Or serve with a local server:
   ```bash
   python -m http.server 8000
   ```


## Usage

Simply open the `index.html` file in a modern web browser. The application includes:
- Bootstrap 5 for responsive design
- Inline JavaScript for functionality
- Embedded data for attachments

## Code Explanation

### HTML Structure
- Uses semantic HTML5 elements
- Bootstrap components for UI
- Responsive design that works on all devices

### JavaScript Functionality
- Handles user interactions
- Processes data from attachments
- Updates DOM elements dynamically
- Includes error handling

### Styling
- Bootstrap 5 framework
- Custom CSS for specific requirements
- Mobile-first responsive design

## Deployment

This application is deployed on GitHub Pages and accessible at the URL provided in the repository settings.

## License

MIT License - See LICENSE file for details

## Auto-Generated

This application was automatically generated using AI-powered code generation.
Generated on: neon-dreams-synth
