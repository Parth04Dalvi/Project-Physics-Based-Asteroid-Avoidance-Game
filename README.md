🚀 Asteroid Avoidance Game

Asteroid Avoidance is a classic-style arcade game built entirely with Vanilla JavaScript and the HTML Canvas API. It features physics-based movement and collision detection, demonstrating core web game development concepts within a single, portable HTML file.

✨ Features

Physics Simulation: Implements a custom Vector class to handle 2D vector mathematics. It applies thrust, rotation, and dampening (friction) for realistic, Asteroids-style spacecraft movement.

Canvas Rendering: Utilizes the HTML5 Canvas API for rendering all game visuals (the ship and asteroids).

Fixed Timestep Logic: Uses a fixed timestep (1/60th of a second) to ensure physics and game updates are consistent and decoupled from the browser's rendering frequency.

Object-Oriented Structure: The logic is organized using JavaScript classes for modularity: Vector, Entity (base class), Ship, Asteroid, and the main Game controller.

Aesthetic Design: Styled with a dark, space-themed aesthetic using Tailwind CSS (via CDN) and the Space Mono font. The canvas is responsive to screen size.

▶️ How to Play

Since the entire game is contained in a single HTML file, there is no complex setup required.

Getting Started

Save the File: Save the provided code snippet as a single HTML file (e.g., index.html).

Open in Browser: Double-click the saved file to open it directly in any modern web browser.

Start Game: Click the Start Game button to begin navigating the asteroid field!

Controls

Action

Key

Thrust (Accelerate)

W or Up Arrow

Rotate Left

A or Left Arrow

Rotate Right

D or Right Arrow

Goal

The objective is simple: avoid colliding with the asteroids for as long as possible.

Your score increases every fraction of a second you survive.

The asteroids gradually increase speed over time, making survival progressively more difficult.

🛠️ Technology Stack

HTML5: Structure, Canvas Element, and Controls.

Vanilla JavaScript (ES6+): Core game logic, custom physics engine, and state management.

HTML Canvas API: Graphics rendering.

Tailwind CSS (CDN): Styling (dark theme, responsive utilities).

Google Fonts: Space Mono for the retro-futuristic typography.

🧩 Key Game Classes

The JavaScript logic is divided into the following key classes:

Class

Description

Vector

The fundamental class for all 2D position and velocity calculations.

Entity

Base class for all moving objects, handling basic movement and edge wrapping.

Ship

Handles player input, rotation, and applying the thrust vector.

Asteroid

Represents the obstacles with randomized speed and size.

Game

The controller that manages the game loop, state (menu, playing, gameover), and the crucial collision checks.
