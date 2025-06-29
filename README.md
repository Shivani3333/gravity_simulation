# gravity_simulation

![image](https://github.com/user-attachments/assets/f07096f6-f313-4561-974a-ee976f88b72b)
Gravitational Pull Simulation

This is a simple Pygame-based simulation demonstrating the gravitational pull of a planet on objects in space. When you click anywhere on the screen, a small object is spawned at that position and is affected by the gravity of a central planet.

Features

Objects spawn at mouse click locations.

Gravity from the central planet pulls objects inward.

Visual representation with background and planet images.

Requirements

Python 3.x

Pygame

Installation

Install Python 3.x (if not already installed).

Install Pygame:

pip install pygame

Download the project files, ensuring you have:

main.py (this script)

bg.png (background image)

moon.png (planet image)

Update image paths in the script to reflect where bg.png and moon.png are stored on your machine:

bg_path = os.path.join("your/path/here", "bg.png")
planet_path = os.path.join("your/path/here", "moon.png")

How to Run

In your terminal, navigate to the project directory and run:

python main.py

Controls

Mouse Click: Spawns a new object at the cursor's position.

Close Window: Ends the simulation.

Notes

You can adjust gravitational strength, object mass, planet mass, and simulation constants directly in the script to observe different behaviors.

Ensure image paths are correct; otherwise, the simulation will run with a black background or without planet graphics.

License

This project is provided for educational and personal use. Feel free to modify and extend it!

Credits

Created using Pygame.

Background and planet images are user-provided; ensure you have rights to use them.
