# Lightbot Kernel

A Python-based backend simulation for grid-based pathfinding and state management, inspired by the puzzle game Lightbot.

**Project Overview:**
This kernel simulates an agent (bot) navigating through a 10x10 grid environment. The system processes a series of commands to update the bot's spatial coordinates, orientation, and interactions with the environment.

**Key Features (v1 & v2):**
* **Spatial Tracking:** Real-time updates of the bot's (x, y) coordinates and directional facing (up, down, left, right).
* **State Management:** Ability to toggle specific states on the grid ('light on/off').
* **Advanced Terrain Handling (v2):** Introduced verticality/elevation to the grid cells. The bot's logic includes collision/height detection, allowing navigation across different elevations using jump commands only when the height difference is exactly 1 unit.

**Technologies:** Python 3
