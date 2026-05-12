# 3D Interactive Football Visualizer

An immersive, real-time 3D visualization of a classic soccer ball built with **Three.js**. Experience a photorealistic football with dynamic lighting, floating particles, and smooth orbital controls.

![Three.js](https://img.shields.io/badge/Three.js-r128-blue?logo=threedotjs)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
![Interactive](https://img.shields.io/badge/Interactive-3D-orange)

<img width="1901" height="907" alt="image" src="https://github.com/user-attachments/assets/81a29485-5340-48cd-b52f-5ebb12f951d1" />

## Features

- **High-Quality 3D Model** – Detailed sphere geometry with a procedurally generated leather texture featuring classic black pentagon and white hexagon panel patterns.
- **Dynamic Lighting System** – Multiple light sources (directional, point, hemisphere, and rim lights) create a realistic stadium-like ambiance with shadows and glow.
- **Interactive Controls** – Powered by `OrbitControls`:
  -  **Drag** to rotate the view around the ball.
  -  **Right-click + Drag** to pan.
  -  **Scroll** to zoom in/out.
- **Atmospheric Effects**:
  - Floating dust particles and energy orbs.
  - Rotating metallic rings around the ball.
  - Subtle CSS2D text label that floats gently.
  - Starfield background and soft volumetric fog.
- **Responsive** – Adapts to any screen size (desktop, tablet, mobile with touch support).

##  Live Preview

To see the ball in action, simply open the `index.html` file in any modern web browser. No build steps or server required!

![Screenshot Placeholder](screenshot.png) <!-- Add a screenshot of your project -->

##  Built With

- **[Three.js](https://threejs.org/)** – Core 3D library for WebGL rendering.
- **CSS2DRenderer** – For floating HTML labels.
- **JavaScript (ES6)** – Animation logic and procedural texture generation.

##  Project Structure

```
football-visual/
├── index.html          # Main application (includes Three.js script)
├── README.md           # Project documentation
└── assets/             # (Optional) External textures or images
```

> **Note:** All code is self-contained in the HTML file, making it easy to deploy or customize.

##  How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/football-visualizer.git
   ```
2. **Open the file**:
   Navigate to the folder and double-click `index.html`.
3. **Interact**:
   - Rotate, zoom, and pan to examine the ball from every angle.
   - Observe the dynamic lighting changes and particle motion.

##  Customization Tips

Want to tweak the ball? Edit the `createFootballTexture()` function inside the script:

- **Change colors**: Modify fill styles (e.g., `#f8f9fc` for white panels, `#1e1f22` for black patches).
- **Adjust panel layout**: Add more pentagons/hexagons by calling `drawPentagon()` or `drawHexagon()` with different coordinates.
- **Lighting intensity**: Tweak the `intensity` values of lights (e.g., `mainLight`, `rimLight`).
- **Animation speed**: Modify the `time` increment in the `animate()` function.

##  Media & Showcase

| Interactive View | Dynamic Lighting |
|----------------|------------------|
| ![View 1](demo1.gif) | ![View 2](demo2.gif) |

*Add your own GIFs/screenshots here.*

##  Contributing

Contributions are welcome! If you have ideas for new features (different ball designs, better shadows, AR support), feel free to:

- Fork the repository.
- Create a feature branch.
- Submit a pull request.

##  License

This project is open source and available under the **MIT License**. Feel free to use, modify, and distribute as you like.

## 🙏 Acknowledgements

- Inspired by classic soccer ball geometry and stadium aesthetics.
- Built with the amazing Three.js ecosystem.
- Special thanks to the open-source community for rendering techniques.

##  Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)

Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)

Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)

LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)

Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)
