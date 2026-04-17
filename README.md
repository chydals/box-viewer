# 3D Packaging SaaS Viewer (P Style)

A dynamic 3D box viewer built with **Three.js** and integrated with **Google Sheets** to function as a low-code SaaS platform for packaging design.

## 🚀 Today's Achievements
* **GitHub Deployment:** Hosted a live web application using GitHub Pages.
* **Dynamic 3D Engine:** Implemented a parametric box generator that renders panels based on user input (L, W, H).
* **Google Sheets Integration:** Created a live sync between a Google Spreadsheet and the 3D Viewer. Changes to formulas in the sheet update the 3D model in real-time.
* **Hierarchical Animation:** Developed a "Parent-Child" hinge system where the tuck flap follows the lid rotation seamlessly.
* **Formula Solver:** Built a custom JavaScript parser that converts algebraic strings (like `W+1`) from the spreadsheet into 3D dimensions.

## 🛠 Features
- **Live Sync:** Status light indicates real-time connection to the Google Sheet database.
- **Interactive Controls:** Fold/Unfold simulation with a 160-degree range.
- **Orbit Controls:** 360-degree inspection of the 3D model via mouse drag and zoom.
- **Material Realism:** Rendered with Phong materials to simulate cardboard textures.

## 📊 Logic & Variables
The system uses three core parameters:
- **L (Length):** Front horizontal panel.
- **W (Width):** Depth/Side panel.
- **H (Height):** Vertical height.

All additional flaps (Lid A, Tuck B, Dust G) are calculated automatically using formulas pulled from the cloud.

## 📁 Repository Structure
- `index.html`: The main application containing the Three.js engine and Google Sheets fetch logic.
- `README.md`: Documentation of the project.

## 🔗 Live Demo
*Check the GitHub Pages settings to see the live link.*# box-viewer
Proyect for a 3D viewer for foldable cardboard boxes
