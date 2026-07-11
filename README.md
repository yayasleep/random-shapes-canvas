# Random Polygon Canvas Filler

Randomly places stretched polygons on a canvas, ensuring they neither overlap nor contain each other.  
This project uses the **Separating Axis Theorem (SAT)** for accurate collision detection, with an **AABB** axis-aligned bounding box as a fast broad-phase filter – striking a balance between readability and performance.

## Features

- Import custom polygons from a shape definition file (`shapes.txt`).
- Randomly assign colors (from seven preset options) and scale shapes (with adjustable stretch factor).
- **AABB broad‑phase + SAT narrow‑phase** to prevent overlaps.
- User‑configurable random seed, running duration, stretch factor, and early termination.
- Generates densely packed colorful polygon clusters on the canvas, with statistics shown both in the window title and the terminal.

## How to Use

### Dependencies
- Python 3.x (standard library only: `turtle`, `random`, `time`)

### Run
```bash
python main.py


