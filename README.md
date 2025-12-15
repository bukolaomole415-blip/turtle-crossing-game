# turtle-crossing-game
Turtle Crossing capstone project built with Python Turtle (100 Days of Code)

# 🐢 Turtle Crossing Game

A Python implementation of the classic **Frogger-style crossing game**, built using the `turtle` graphics module.  
This project is the **Turtle Crossing Capstone** from my *100 Days of Code* Python course.

---

## 🎮 Gameplay Overview

- Control a turtle trying to cross a busy road  
- Avoid moving cars  
- Each successful crossing increases the level  
- Cars move faster as levels increase  

---

## 🚗 Game Features

### 🐢 Player Controls
- Move forward using the **Up Arrow key**
- Player resets to the starting position after each successful crossing

### 🚙 Dynamic Car System
- Cars spawn randomly  
- Cars move across the screen  
- Speed increases with each level  

### 📊 Level Tracking
- Current level displayed at the top of the screen  
- Game ends when the turtle collides with a car  

---

## 🧱 Project Structure

- `player.py` → handles turtle movement and reset  
- `car_manager.py` → creates and controls car objects  
- `scoreboard.py` → displays level and game over message  
- `main.py` → manages game loop and collision logic  

---

## 🧠 What I Learned

- Managing multiple moving objects  
- Collision detection with screen coordinates  
- Increasing difficulty dynamically  
- Structuring a capstone project with OOP  
- Writing clean, modular Python code  

---

## 🚀 How to Run
```

python main.py
Requires Python with the built-in turtle module.

💡 Part of My Python Learning Journey
This capstone project helped solidify my understanding of game loops, object interaction, and difficulty scaling using Python.

