[gravitational_sim_readme.md](https://github.com/user-attachments/files/20966054/gravitational_sim_readme.md)# 🌌 Gravity Simulation

![Gravity Simulation](https://github.com/user-attachments/assets/f07096f6-f313-4561-974a-ee976f88b72b)

A simple yet fascinating Pygame project demonstrating how gravity pulls objects toward a central planet.

---

## ⭐ Features

- Click anywhere to spawn objects.
- Objects are pulled by the central planet's gravity.
- Background and planet images for visual immersion.

## 🛠️ Requirements

- Python 3.x
- [Pygame](https://www.pygame.org/wiki/GettingStarted)

## 🚀 Installation & Running

1️⃣ Install dependencies:

```bash
pip install pygame
```

2️⃣ Download and place `main.py`, `bg.png`, and `moon.png` in the same directory.

3️⃣ Update the paths in `main.py`:

```python
bg_path = os.path.join("your/path/here", "bg.png")
planet_path = os.path.join("your/path/here", "moon.png")
```

4️⃣ Run the simulation:

```bash
python main.py
```

## 🎮 Controls

- **Mouse Click:** Spawn new objects.
- **Close Window:** Exit simulation.

## 📚 Notes

You can tweak constants in `main.py` to change gravitational force, masses, and more.

## 📄 License

Open-source for educational and personal use. Modify and enjoy!

## 🙏 Credits

Built with [Pygame](https://www.pygame.org/). Use your own images or ensure you have rights to existing ones.



