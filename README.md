# 🐍 Snake Game

A classic Snake Game built using Python and Turtle, featuring user interactions, customizable messages, and a scoring system.



## 📌 Features

- User-friendly interface with Turtle Graphics
- Speed selection (Slow / Fast)
- Player name input for personalized experience
- Scoring system with high score tracking
- Game over prompts with custom messages
- Border collision detection
- Smooth movement and food consumption



## 🔧 Installation

Ensure you have Python 3.7+ installed.

### 1.Clone the repository:

```bash
git clone https://github.com/Guda-Tharunya-Varma/Snake_Game.git
cd Snake-Game

```
### 2.Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3.Install dependencies:

```bash
pip install -r requirements.txt
```
### 4.Run the game:

```bash
python snake_game.py

```


## 🎮 How to Play

- Arrow keys to control the snake.
- Eat the blue food to grow longer.
- Avoid hitting walls or yourself.
- Game ends if you collide, prompting a restart option.
##  🛠️ Dependencies

This project uses:
- Python 3.x
- Turtle (Built-in Python Library)
- PIL (Pillow) for displaying images
- Tkinter (Built-in) for user interactions


## 🕹️ Flow of the Game  

### 1️⃣ Start Screen  
- Asks the user if they want to play.  
  - If **Yes** → Proceed to **Name Input**  
  - If **No** → Exit the game  

  ![Image](https://github.com/user-attachments/assets/fbd80b74-e0f3-44d2-bfa2-6da1cec6a3d9) 

### 2️⃣ Enter Player Name  
- Prompts the user to enter their name.  
- After entering the name, a **"Have Fun!"** popup appears with:  
  - **✅ OK** → Proceeds to Game Board  
  - **❌ Exit** → Closes the game  

  ![Image](https://github.com/user-attachments/assets/4957d4ba-d394-4e69-959b-c757976cbd26) 

  ![Image](https://github.com/user-attachments/assets/e3e3e8ba-b38b-477f-bdc2-873ecda2002d)

### 3️⃣ Choose Speed  
- Asks the user to select game speed:  
  - **✅ Yes** → Slow speed  
  - **❌ No** → Fast speed  

  ![Image](https://github.com/user-attachments/assets/34b09f05-2268-4e36-b21c-bd8452bc2ac6) 

### 4️⃣ Game Board Appears  
- Displays **instructions** before the game starts:  
  - **Controls:** Arrow keys to move  
  - **Objective:** Eat food to grow, avoid hitting walls  
  - **Scoring:** Each food eaten increases the score  
- Press **any  Arrow key** to start the game  

  ![Image](https://github.com/user-attachments/assets/6f817293-9850-4d5c-aea9-f2415e609c11)

### 5️⃣ Gameplay Begins  
- The snake starts moving automatically.  
- Eat **blue food** to grow longer.  
- Avoid hitting **walls** or **your own body**.  

### 6️⃣ Game Over Screen  
- Displays a **custom message** with the player's score:  
- Options to:  
  - **Yes** – Play again  
  - **No** – Quit the game
     
  ![Image](https://github.com/user-attachments/assets/ab21b237-131d-414f-96d2-2bb71e3f4de6)   
 

------

## 📜 License  
This project is open-source and free to use.

---

## 🤝 Contributing  
Feel free to fork and contribute to enhance the game!

---

## 💡 Author  
Developed by **Guda Tharunya Varma**  
GitHub: [https://github.com/Guda-Tharunya-Varma]([https://github.com/your-username](https://github.com/Guda-Tharunya-Varma))

