🌎 Pygame Sandbox
A simple 2D sandbox world built in Python using Pygame.
Place blocks, delete blocks, move around, and build anything you want.

Made by Adrian.

🖼️ Project Icon
(Insert your pixel icon here)

Code
![Icon](your-icon-file.png)
🎮 Features
🧱 Place and remove blocks

🎨 5 block types (dirt, grass, stone, sand, water)

🎒 Inventory hotbar with selection outline

🧭 WASD camera movement

💾 Save & load your world

🖥️ Grid‑based building

⚡ Smooth 60 FPS

More features coming soon.

🕹️ Controls
Action	Key / Mouse
Move camera	W A S D
Select block	1–5
Place block	Left click
Remove block	Right click
Save world	S
Load world	L


🧱 Inventory Hotbar
The hotbar shows your available blocks.
Press 1–5 to select a slot.
The selected slot has a white outline.

📸 Screenshots
(You can add these later)

Code
![Screenshot 1](screenshots/screen1.png)
![Screenshot 2](screenshots/screen2.png)
🧩 How It Works
The world is a 2D grid stored in a Python list:

Code
world[y][x] = block_id
Block IDs:

0 = empty

1 = dirt

2 = grass

3 = stone

4 = sand

5 = water

The camera moves by shifting the grid offset.

🚀 How to Run
1. Install Python
Download from: https://python.org

2. Install Pygame
Code
pip install pygame
3. Run the game
Code
python main.py
💾 Saving & Loading
Press S to save your world to world.json.
Press L to load it again.

📁 Folder Structure
Code
pygame-sandbox/
│
├── main.py
├── world.json
├── README.md
├── your-icon-file.png
├── screenshots/
│   ├── screen1.png
│   └── screen2.png
└── assets/   (optional for textures)
🛠️ Planned Updates
Block textures

Player character

Zoom in/out

More block types

Particle effects

Crafting menu

Infinite world chunks

⭐ Why I Made This
I wanted to learn Python and Pygame by making something fun.
This sandbox is my first step toward bigger games.

📜 License
MIT License — feel free to use, modify, and learn from this project. just gimme credit XD

🔗 Links
My GitHub profile: github.com/JellyOverloade

Project page: github.com/JellyOverloade/PyGames
