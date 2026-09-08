# 🌌 Universe Simulation — 65 Orders of Magnitude

An interactive 3D visualization of the universe spanning **65 orders of magnitude**, from the quantum scale to the cosmic scale.

Built with **HTML5, JavaScript, Three.js and WebGL**, this project combines interactive 3D graphics, physics-inspired simulations, educational content, and real-time performance monitoring into a single browser-based experience.

---

## ✨ Features

### 🔬 Physics & Simulation

* Orbital mechanics based on Keplerian motion
* Orbital precession visualization
* Relativistic effects including time dilation and gravitational lensing
* Quantum wave-function visualization
* Quantum tunneling visualization
* Real-time sphere collision detection
* Elastic and inelastic collision responses
* Spatial hashing for optimized collision detection
* Real-time collision statistics

### 🌌 Universe Scale Navigation

Explore **24 different scales** ranging from:

* Quantum
* Atomic
* Microscopic
* Human
* Planetary
* Galactic
* Cosmic

The simulation covers approximately:

```text
10⁻³⁵ → 10³⁰ meters
```

That's **65 orders of magnitude** of scale.

---

## 🎮 Interactive Experience

### Mouse

| Action                  | Result              |
| ----------------------- | ------------------- |
| Drag                    | Rotate the universe |
| Scroll                  | Zoom in/out         |
| Click navigation points | Jump to a scale     |

### Keyboard

| Key     | Action                 |
| ------- | ---------------------- |
| `↑ / ↓` | Rotate vertically      |
| `← / →` | Rotate horizontally    |
| `+ / -` | Zoom                   |
| `S`     | Search                 |
| `B`     | Toggle bookmark        |
| `R`     | Reset view             |
| `E`     | Education panel        |
| `A`     | Advanced features      |
| `P`     | Performance statistics |
| `?`     | Help                   |

### Mobile / Tablet

* One-finger drag → Rotate
* Two-finger pinch → Zoom
* Tap → Interact with controls

---

## 🎨 Visual Experience

The simulation uses a futuristic space-themed interface featuring:

* Procedurally generated textures
* Dynamic lighting
* 8,000+ star particles
* Neon-style UI
* Responsive information panels
* Dynamic level-of-detail rendering
* Scale-dependent visual effects
* Real-time 3D object transformations

---

## 📊 Performance Monitoring

The built-in performance panel provides real-time information about:

* FPS
* Memory usage
* Active objects
* Collision count
* Collision markers

The application also uses optimization techniques such as:

* Level-of-detail (LOD) culling
* Spatial hashing
* Efficient buffer geometry
* GPU-accelerated particle rendering
* Resource management
* Adaptive rendering

---

## 🧠 Educational Content

The project is designed not only as a visualization but also as an educational tool.

It demonstrates concepts from:

* Astronomy
* Orbital mechanics
* Relativity
* Quantum mechanics
* Classical collision physics
* Computer graphics
* WebGL
* Algorithms and data structures

Each scale provides contextual information and physics-related data to help users understand the enormous range of scales present in our universe.

---

## 🛠️ Technology Stack

| Technology   | Purpose                        |
| ------------ | ------------------------------ |
| HTML5        | Application structure          |
| CSS3         | UI and visual design           |
| JavaScript   | Application logic              |
| Three.js     | 3D rendering                   |
| WebGL 2.0    | Hardware-accelerated graphics  |
| HTML5 Canvas | Procedural texture generation  |
| localStorage | Bookmarks and user preferences |

### Three.js

The project uses **Three.js r128** for its 3D rendering and visualization capabilities.

---

## ⚙️ Physics Algorithms

The project demonstrates several physics and computational techniques:

### Orbital Mechanics

Keplerian orbital calculations are used to simulate planetary and celestial motion.

### Collision Detection

The collision system uses:

* Sphere collision detection
* AABB-based checks
* Spatial hashing
* Collision response
* Momentum conservation concepts
* Friction and damping

### Relativistic Visualization

The simulation includes visual representations of:

* Time dilation
* Lorentz-related effects
* Gravitational lensing

### Quantum Visualization

Quantum-scale scenes include:

* Wave functions
* Probability clouds
* Quantum tunneling

---

## 🚀 Getting Started

### Requirements

You only need:

* A modern web browser
* WebGL 2.0 support

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

### Run Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/simulation-master-.git
```

Enter the project directory:

```bash
cd simulation-master-
```

Then open:

```text
index.html
```

in your browser.

No package installation or build process is required.

---

## 📁 Project Structure

```text
Simulation-main/
│
├── .github/
│   └── workflows/
│       └── static.yml
│
├── docs/
│   ├── README.md
│   └── index.html
│
├── index.html
│
└── LICENSE
```

---

## 🔧 Customization

The simulation can be customized directly from the source code.

### Visual Theme

CSS variables control the main visual theme:

```css
:root {
    --primary: #00f3ff;
    --accent: #ff0055;
    --bg: #0a0a12;
    --secondary: #00ffaa;
}
```

### Collision Parameters

Physics behavior can be adjusted through the collision configuration:

```javascript
this.collisionConfig = {
    elasticity: 0.85,
    friction: 0.15,
    damping: 0.95,
    minCollisionDist: 0.1,
    maxCollisionsPerFrame: 1000
};
```

### Universe Scales

Additional scales and objects can be added through the scale configuration.

---

## 🔐 Privacy

This project is designed to run locally in the browser.

* No user accounts required
* No personal data collection
* Bookmarks are stored locally using `localStorage`
* No tracking system
* No external backend required

---

## 🗺️ Roadmap

Potential future improvements include:

* [ ] Black hole visualization
* [ ] Advanced gravitational effects
* [ ] More particle physics simulations
* [ ] Multiplayer collaboration
* [ ] VR/AR support
* [ ] Scene image/video export
* [ ] Custom universe builder
* [ ] Time acceleration and reversal
* [ ] More educational datasets

---

## 🤝 Contributing

Contributions and improvements are welcome.

Areas where contributions could be useful:

* Performance optimization
* New physics simulations
* Additional universe scales
* Educational content
* UI/UX improvements
* Bug fixes
* Browser compatibility
* Documentation

### Contribution Workflow

```bash
git clone <repository-url>

git switch -c feature-name

# Make your changes

git add .

git commit -m "Add feature"

git push -u origin feature-name
```

Then open a Pull Request on GitHub.

---

## 📚 Learning Resources

Useful technologies and concepts related to this project:

* Three.js
* WebGL
* JavaScript
* Computer graphics
* Orbital mechanics
* Collision detection
* Spatial hashing
* Quantum mechanics
* Relativity

---

## 📄 License

See the [LICENSE](LICENSE) file for license information.

---

## 👨‍💻 Author

Created as an interactive 3D physics and astronomy visualization project.

---

## 🌌 Explore the Universe

> **From the quantum realm to the cosmic horizon — explore 65 orders of magnitude in an interactive 3D universe.**

**Version:** 1.0.0
