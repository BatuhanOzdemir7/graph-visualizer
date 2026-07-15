# Graph Visualizer & Shortest Path Finder 🚀

A lightweight, interactive, and modern web application designed to build, visualize, and analyze graphs. It includes a step-by-step pathfinding visualizer powered by **Dijkstra's Algorithm**. 

Originally built as a developer tool for a personal game project to simulate map routing, NPC pathfinding costs, and quest/dialogue dependency trees directly from a browser.

---

## 🌟 Key Features

*   **Completely Interactive Sandbox:** Drag, drop, and rearrange nodes freely with an active physics-based layout (using `vis-network`).
*   **Coordinate-Based Persistence (NEW):** DND (Drag and Drop) positions are tracked. When you move a node, its exact `(x, y)` coordinate is saved. Refreshing the browser (`F5`) keeps everything exactly where you left them!
*   **Dynamic Graph Management:**
    *   Create nodes with custom string-based IDs.
    *   Establish weighted edges with custom names/labels (defaults to `weight = 1` if left blank).
*   **Double-Click to Edit:** Simply double-click any node to rename its display label, or double-click an edge to update its weight and label instantly.
*   **Robust State Management:**
    *   **Auto-Save:** Saves your progress locally in your browser's Local Storage after every node creation, connection, or repositioning.
    *   **JSON Export/Import:** Download your entire graph layout as a `.json` backup file and upload it later (or on another computer) to resume your work.
*   **Pathfinding Visualizer:** Enter start and end nodes to calculate the shortest path. The visualizer highlights the optimal route in green (nodes) and red (edges) with high contrast.

---

## 🛠️ Built With

*   **HTML5 & CSS3** (Responsive design, modern flexbox layout, and custom UI components)
*   **JavaScript (ES6+)** (Vanilla Dijkstra algorithm implementation, DOM events, and persistence APIs)
*   **[vis-network](https://github.com/visjs/vis-network)** (Graph rendering engine, real-time physics, and interaction handlers)

---

## 🚀 Getting Started

No installation or local server setup is required. The entire application runs directly inside the browser:

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/BatuhanOzdemir7/graph-visualizer.git](https://github.com/BatuhanOzdemir7/graph-visualizer.git)
    ```
2.  Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  *Note: An active internet connection is required to load the vis-network library via CDN.*

---

## 🎮 Game Development Context

This visualizer serves as an essential debugging and design tool in game development workflows:
*   **Waypoint Design:** Plot patrol paths for enemy AI and optimize node weights based on terrain difficulty (e.g., roads vs. swamps).
*   **Static Layout Testing:** Export the coordinate mapping data via JSON directly into your game's engine parsing pipelines.
*   **Quest & Dialog Nodes:** Wire visual flowcharts to structure complex branching narrative mechanisms.

---

## 📸 Preview

<img width="1468" height="761" alt="image" src="https://github.com/user-attachments/assets/497d30fb-429f-47d7-b2c3-6400d65d9188" />
<img width="1444" height="753" alt="image" src="https://github.com/user-attachments/assets/f30b9caa-7ceb-46d8-988b-4d9adf20d35d" />

---

## 📄 License

This project is licensed under the [MIT](LICENSE) License - feel free to customize and integrate it into your own games or projects!
