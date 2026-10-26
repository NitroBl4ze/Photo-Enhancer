# 📸 Photo Enhancer Web App

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![Tech Stack](https://img.shields.io/badge/Stack-JavaScript%20%7C%20HTML5%20Canvas%20%7C%20CSS3-orange.svg)

A lightweight, browser-based **Photo Enhancer & Image Editor** built with vanilla web technologies. It allows users to upload local images, tweak tonal and color grading parameters in real time using interactive sliders, preview side-by-side modifications, and export the enhanced image instantly without external server uploads.

---

## 🌟 Key Features

- **⚡ Real-Time Image Adjustments:**
  - **Brightness:** Lift shadows or dim exposure.
  - **Contrast:** Enhance visual depth and dynamic punch.
  - **Saturation & Vibrance:** Tune color intensity from muted tones to vivid hues.
  - **Grayscale & Inversion:** Quick stylistic monochrome conversions.
  - **Blur & Sharpness Controls:** Adjust spatial softening and fine detail clarity.
- **🖼️ HTML5 Canvas Pixel Manipulation:** Direct client-side pixel rendering using the Canvas 2D API for zero latency.
- **🔄 Instant Reset & Undo:** Revert all sliders and canvas filters back to the original image state with one click.
- **💾 High-Quality Export:** Download the final processed image directly to your device (JPEG / PNG format).
- **📱 Responsive & Dark-Themed UI:** Studio-grade dark workspace designed for focused photo editing across desktop and mobile browsers.
- **🔒 100% Privacy-Focused:** All image processing happens locally inside the client's browser — no images are uploaded to any third-party cloud or database.

---

## 🛠️ Built With

- **HTML5:** File input handling, drag-and-drop workspace, and semantic controls.
- **CSS3:** Studio dark theme, responsive grid/flex layouts, custom range slider aesthetics.
- **JavaScript (ES6):** Canvas 2D API, CSS filter strings / pixel buffer manipulation, event listeners, and blob download pipeline.

---

## 🚀 Live Demo / Preview

<!-- Enable GitHub Pages in your repo settings to access the live app -->
> 🌐 **Live Demo:** [Photo Enhancer Web App](https://nitrobl4ze.github.io/Photo-Enhancer/)

---

## 📂 Project Structure

```text
Photo-Enhancer/
├── index.html       # Editor dashboard, canvas viewport & controls
├── style.css        # Studio dark theme & slider styles
├── script.js        # Canvas rendering, filter math & download handlers
└── README.md        # Documentation
