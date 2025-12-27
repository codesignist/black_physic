# Yugop Physics Demo

A faithful recreation of the classic 2005 Flash experiment **"Yugop"** by Yugo Nakamura, built with modern web technologies. This interactive physics simulation features falling balls that respond to gravity, collisions, and user interaction.

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🌟 Features

*   **Real-time Physics**: Powered by [Matter.js](https://brm.io/matter-js/) for realistic 2D rigid body physics.
*   **Dynamic Spawning**:
    *   Starts with a burst of 30 balls.
    *   Continuously spawns 1 new ball per second while removing the oldest to maintain equilibrium.
*   **Interactive Controls**:
    *   **Click & Drag**: Launch balls to scatter others.
    *   **Click & Hold (Empty Space)**: Grow a new ball; release to spawn it into the world.
*   **Visual Aesthetics**:
    *   Minimalist Black & White design.
    *   Rotating "+" markers on balls to visualize angular momentum.
*   **Audio Feedback**:
    *   Generative "beep" sound effects using the Web Audio API on every spawn.

## 🛠️ Technologies Used

*   **HTML5 & CSS3**: Core structure and styling.
*   **JavaScript (ES6+)**: Logic and interaction.
*   **Matter.js**: 2D Physics Engine.
*   **Web Audio API**: For procedural sound generation.

## 🚀 Getting Started

This project is a **static web application**. You don't need any complex build tools to run it locally.

### Prerequisites

*   A modern web browser (Chrome, Firefox, Safari, Edge).

### Installation & Running

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/YOUR_USERNAME/yugop-physics.git
    cd yugop-physics
    ```

2.  **Run Locally**:
    *   Simply open `index.html` in your browser.
    *   *OR* use a local server for a better experience (VS Code Live Server, `python -m http.server`, `npx serve`, etc.).

    ```bash
    # Example using npx serve
    npx serve .
    ```

## 📦 Deployment

This project is designed to be deployed easily to **GitHub Pages**.

1.  Push your changes to the `main` branch.
2.  Go to your repository **Settings** > **Pages**.
3.  Select **Source**: `Deploy from a branch`.
4.  Select **Branch**: `main` and **Folder**: `/ (root)`.
5.  Save. Your site will be live shortly!

## 🎨 Design Philosophy

The design pays homage to the original Flash experiment, focusing on high contrast, smooth motion, and satisfying physics interactions. The "Plus" signs on the balls are added to emphasize the rotational physics that were a signature detail of the original.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Inspired by Yugo Nakamura (yugop).*
