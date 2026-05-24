# 🧬 BioChem Digital Lab 3D

[![Live Demo](https://img.shields.io/badge/demo-Live%20View-success)](#) *(<- Add your Vercel/GitHub Pages link here!)*

BioChem Digital Lab 3D is a highly interactive, WebGL-powered web application that allows users to search for chemical compounds and render their 3D molecular structures in real-time. 

## ✨ Features
* **Dynamic Fetching:** Integrates with the PubChem REST API to retrieve accurate 3D coordinates (SDF format) for a vast database of molecules.
* **Interactive 3D Rendering:** Utilizes `3Dmol.js` to provide smooth, browser-based WebGL rendering.
* **Customizable Views:** Users can seamlessly toggle between multiple representations:
  * Ball & Stick
  * Stick (Bonds only)
  * Space Fill (Volume)
  * Wireframe (Line)
* **Advanced Visuals:** Features toggles for Van der Waals electron density surfaces and auto-rotation for detailed inspection.
* **Responsive UI:** Built with a custom dark-mode aesthetic, vibrant gradients, and Bootstrap 5 for a modern, device-friendly experience.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (ES6+), jQuery
* **Styling:** Bootstrap 5, Custom CSS animations
* **3D Library:** `3Dmol.js` (WebGL)
* **Data Source:** PubChem REST API

## 🚀 How to Run Locally
Since this is a client-side web application, running it locally is incredibly simple:
1. Clone this repository: `git clone https://github.com/yourusername/biochem-digital-lab.git`
2. Navigate to the project folder.
3. Open `index.html` in any modern web browser.
