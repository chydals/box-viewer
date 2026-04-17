# 3D Packaging SaaS Viewer (Pacdora Style)

A dynamic 3D box viewer built with **Three.js** and integrated with **Google Sheets** to function as a low-code SaaS platform for packaging design.

## 🚀 Recent Updates & Achievements
* **Dynamic Export System:** Added capability for clients to download high-resolution snapshots (PNG) of their 3D designs.
* **Specification Export:** Integrated a CSV generator that exports live calculated dimensions (L, W, H, Lid, Tuck) for production use.
* **Orbit Camera System:** Implemented advanced user controls for 360-degree inspection and zoom.
* **GitHub Deployment:** Hosted as a live web application using GitHub Pages.
* **Live Google Sheets Sync:** Created a live bridge between a cloud-based spreadsheet (acting as a database) and the rendering engine.

## 🛠 Features
- **Live Sync Indicator:** Visual status bar confirming the connection to the Google Sheet database.
- **Parametric Modeling:** Real-time geometry updates based on millimetric precision inputs.
- **Fold Simulation:** Interactive slider to visualize the box opening/closing mechanics (0° to 160°).
- **Formula Parser:** JavaScript engine that evaluates algebraic packaging rules (e.g., `W + 1`) fetched from the cloud.

## 📊 Technical Logic
The application utilizes three primary global variables:
- **L (Length):** Front horizontal panel dimension.
- **W (Width):** Depth/Side panel dimension.
- **H (Height):** Vertical vertical dimension.

Secondary panels such as **Lid (A)** and **Tuck (B)** are calculated on-the-fly using formulas defined in the linked Google Sheet.

## 📁 Repository Structure
- `index.html`: Core application code (WebGL Engine + API Fetch Logic).
- `README.md`: Project documentation and feature log.

## 🔗 Live Demo
*Check your GitHub Pages deployment link to view the live app.*
