# 🐍 Snake Game (Python Turtle)

A simple and fun implementation of the classic **Snake Game** built with Python’s `turtle` graphics library.  
Move the snake, eat the food, and grow — but don’t hit the wall or yourself!

---

## 🎮 Features
- Classic snake mechanics  
- Real-time score tracking  
- Food spawns at random positions  
- Modular design using multiple Python files  
- Smooth game experience built with the `turtle` module

---

## 🧱 File Structure
```text
snake-game/
│
├── main.py          # Main game loop and controls
├── snake.py         # Snake class: movement, growth, collisions
├── food.py          # Food class: random placement and rendering
└── scoreboard.py    # Score display and reset logic
```
---

## ⚙️ Requirements
- Python 3.x  
- `turtle` module (comes pre-installed with Python)

No external libraries are needed.

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/snake-game.git
   cd snake-game
2. Run the game:
   ```bash
   python main.py

Use the arrow keys to move the snake.
Try to eat as much food as possible without colliding with the wall or yourself!

🧠 Future Improvements
* Add different difficulty levels
* Add sound effects
* Store high scores in a local file
* Create a start/restart menu
* Add wall wrap-around mode

📜 License
This project is open-source and free to use.
