[![STATUS](https://img.shields.io/badge/Status-Alpha-orange)]()
[![three.js](https://img.shields.io/badge/three.js-0.160.0-blue)]()
[![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow)]()

```
██████╗ ██████╗     ██╗   ██╗██╗███████╗██╗    ██╗███████╗██████╗ 
╚════██╗██╔══██╗    ██║   ██║██║██╔════╝██║    ██║██╔════╝██╔══██╗
 █████╔╝██║  ██║    ██║   ██║██║█████╗  ██║ █╗ ██║█████╗  ██████╔╝
 ╚═══██╗██║  ██║    ╚██╗ ██╔╝██║██╔══╝  ██║███╗██║██╔══╝  ██╔══██╗
██████╔╝██████╔╝     ╚████╔╝ ██║███████╗╚███╔███╔╝███████╗██║  ██║
╚═════╝ ╚═════╝       ╚═══╝  ╚═╝╚══════╝ ╚══╝╚══╝ ╚══════╝╚═╝  ╚═╝
```

# 3D Animation Viewer

---

## ✨ Features

* Load multiple **FBX** and **GLB** animation files at once.
* Actors are automatically:

  * Scaled to a target height
  * Grounded on a stage
  * Arranged in a stage-like layout
* Plays the **first animation clip** of each file in loop.
* Floating **filename labels** above each actor:

  * Click name to copy filename
  * Copy button for quick access
* Basic **controls**:

  * Adjust spacing between actors
  * Adjust target height
  * Change animation speed
  * Play / Pause all
  * Clear stage
* **No mouse zoom** (to avoid breaking framing).
* **Drag & drop** support.

---

## ⭐ Recommendations

* Keep models under **50k vertices** for smooth playback.
* Prefer `.glb` over `.fbx` for faster loading and smaller file size.

---

## 📦 Prerequisites

* A modern browser with **ES Modules** support.
* `three.js` v0.160.0 (loaded via CDN, already included in HTML).
* Animation files (`.fbx` or `.glb`).

---

## 🚀 Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/3d-animation-viewer.git
   cd 3d-animation-viewer
   ```
2. Open `index.html` in your browser.
3. Drag & drop `.fbx` or `.glb` files, or use the file picker.
4. Adjust spacing, height, and animation speed with the UI controls.

---


## 💬 Support & Questions

* Open an issue on [GitHub Issues](https://github.com/yourusername/3d-animation-viewer/issues).
* Or contact me directly if needed.

---

## 📜 License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for details.

---
