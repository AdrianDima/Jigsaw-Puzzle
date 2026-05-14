# High-Performance Jigsaw Puzzle Engine

A web-based, real-time jigsaw puzzle game built from scratch using a procedural **Flask** backend, native **JavaScript**, and **CSS**. This project explores the optimization of real-time state management, coordinate manipulation, and algorithmic geometry.

---

## 💡 Project Genesis & Collaboration
This application represents the culmination of an intensive **three-month development cycle**, building a bridge between a career as a **Structural Stress Engineer** and modern full-stack development. 

While leveraging years of core computer science principles (including algorithms and data structures through MITx, PennX, and Princeton), this system served as the practical application of those theories into a complex, integrated product. 

Throughout development, **Gemini** was utilized as a high-level technical consultant—leveraging the AI for rapid debugging, tracking library interactions, and refining asynchronous back-end communication constraints.

---

## 🛠️ Architectural & Technical Highlights

### 📐 Bézier Curves & Procedural Geometry
Drawing from a career manipulating complex aerospace and structural components in CAD environments (Catia, SolidWorks), this project steps "behind the curtain" of commercial UI. Edge geometries are calculated manually via dynamic coordinate matrices, allowing the system to procedurally map edges ranging from classic puzzle interlocking tabs to intricate Koch snowflake fractals.

### 🐍 Functional/Procedural Logic over OOP
To ensure the game engine remained incredibly lightweight, a strict functional, procedural architecture was chosen for the Python engine over a traditional Object-Oriented (OOP) system. Given the heavy mathematical overhead required for piece checking and neighbor grid evaluations, a functional data flow allows for transparent matrix transformations. This keeps the Flask server highly performant and ensures state transitions remain directly auditable against the geometric blueprints.

### 🖱️ Single-Merge Engine Stability
To ensure absolute UI predictability, the server-side engine restricts calculations to process exactly *one merge per move*. This design decision entirely prevents chaotic cascading snappings, ensuring game state tracking is stable and computationally bounded.

### 📦 UX Enhancements: Group Multi-Selection
Moving past standard single-element drag mechanics, the client-side interaction engine includes a custom-engineered multi-selection box gesture. Players can select, group, and sweep large clusters of pieces dynamically across the matrix array.

---

## 🚀 Tech Stack & Dependencies
* **Backend:** Python 3, Flask
* **Image Processing:** Pillow (PIL) for image slicing and canvas bounding
* **Frontend:** Core HTML5, CSS3 Grid/Flexbox, Native Vanilla JavaScript (ES6)

---

## 📬 Contact & Feedback
For inquiries regarding the underlying mathematics, the geometric blueprint tracking, or transitions within engineering disciplines:
* **Developer:** Adrian Vancea DIMA
* **Email:** [abcmat2000@gmail.com](mailto:abcmat2000@gmail.com)
