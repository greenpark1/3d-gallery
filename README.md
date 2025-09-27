# 3D Gallery Walkthrough

An interactive 3D art gallery built with Three.js that you can explore using keyboard and mouse controls. Walk through a corridor into a main exhibition room featuring various artworks and video installations.

## 🎨 Features

- **Immersive 3D Environment**: Navigate through a realistic gallery space with corridor and main exhibition room
- **Interactive Artworks**: Click on paintings and video installations to interact
- **Smooth Controls**: DOOM-style movement system with cursor-based camera control
- **Atmospheric Lighting**: Multiple spotlights create an authentic gallery ambiance
- **Video Support**: Playable video art pieces with modal player
- **Responsive Design**: Works on desktop browsers

## 🕹️ Controls

### Movement
- **W** - Move forward (in the direction you're looking)
- **S** - Move backward
- **A** - Strafe left
- **D** - Strafe right

### Camera
- **Move cursor** - Pan (horizontal) and tilt (vertical) camera view
- **Click on artworks** - Interact with paintings or play videos

## 🚀 Quick Start

### Option 1: Open Directly
1. Download `index.html`
2. Double-click the file to open in your browser

### Option 2: Run with Live Server (Recommended)
1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install the "Live Server" extension
3. Right-click `index.html` → "Open with Live Server"

### Option 3: View Online
Visit the live demo at: `https://yourusername.github.io/3d-gallery/`

## 📱 Mobile Access

To access on your smartphone:
1. Ensure your phone and computer are on the same WiFi
2. Run Live Server and find your computer's IP address
3. On your phone, navigate to: `http://[YOUR-IP]:5500/index.html`

**Note**: Mobile experience may vary. Touch controls are limited compared to keyboard/mouse.

## 🏗️ Gallery Layout

### Corridor
- Entrance hallway with decorative elements
- Plant and bench as ambient objects
- Leads into main gallery space

### Main Exhibition Room
- Central viewing seat
- **Left Wall**: Abstract Art, Landscape paintings
- **Right Wall**: Portrait, Modern Art, Still Life paintings  
- **Back Wall**: Two video art installations and Gallery Art piece

## 🛠️ Technical Details

- **Built with**: Three.js (r128)
- **No dependencies**: Single HTML file with embedded JavaScript
- **Browser compatibility**: Modern browsers with WebGL support
- **CDN**: Three.js loaded from Cloudflare CDN

## 🎯 Customization

Want to customize your gallery? Edit the code to:
- Change artwork colors (search for `createArtwork` function)
- Adjust lighting brightness (modify spotlight intensity values)
- Add more rooms (extend the floor and wall geometries)
- Replace video sources (update video `src` in onClick function)
- Modify movement speed (change `speed` variable in animate function)

## 📋 Browser Requirements

- Modern browser with WebGL support (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Recommended: Desktop/laptop for best experience

## 🐛 Troubleshooting

**Gallery won't load?**
- Check browser console for errors (F12)
- Ensure internet connection (Three.js loads from CDN)
- Try a different browser

**Movement feels wrong?**
- Movement is based on horizontal camera direction only (DOOM-style)
- Vertical look doesn't affect ground movement

**Video won't play?**
- Click directly on purple/pink colored artworks
- Check browser's autoplay policies
- Ensure internet connection for video streaming

## 📝 License

Free to use and modify for personal and educational purposes.

## 🤝 Contributing

Feel free to fork and customize this gallery for your own projects!

## 📧 Contact

Created as an interactive 3D experience. Enjoy exploring!

---

**Pro Tip**: For the best experience, use a mouse and keyboard. Look around by moving your cursor, and walk through the gallery using WASD keys!
