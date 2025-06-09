# ⭐️ Tower Defense Game ⭐️

This is a custom-built Tower Defense game designed and developed entirely in Java using JavaFX. The goal of the game is to protect a castle from waves of enemies by strategically placing towers and building walls. It was developed as part of my effort to explore object-oriented design, real-time rendering, and JavaFX-based UI systems.

## 🎯 Gameplay Overview

- Place towers to damage enemies approaching the castle.
- Build walls to delay enemy attacks and gain time to strategize.
- Enemies follow the shortest path to the nearest object.
- Two types of towers with different durability and attack range.
- Towers can be upgraded or sold depending on strategy.
- You earn money by killing enemies and can spend it on upgrades.
- Castle health decreases with each enemy attack — the game ends when it reaches zero.

## 🧱 Core Features

- 🎯 Strategic tower placement and upgrades
- 🧱 Wall building and enemy distraction logic
- 🧠 Pathfinding that ensures enemies choose the shortest route
- 💰 In-game economy with upgrade and sell logic
- 💥 Multiple types of enemies with different strengths and rewards
- 📊 Final scoreboard and high score tracking

## 🗺 Map Variants

- **Basic** – standard gameplay with towers and walls
- **Flood** – includes areas that cannot be built on due to water
- **Extended** – allows castle health regeneration, tower upgrades, and tower selling

## 🛠 Technology Stack

- Java 17
- JavaFX
- Gradle (build tool)
- Object-Oriented Programming (OOP)
- Event-driven UI with JavaFX
- Custom game loop and rendering engine

## 🕹 Game Preview

To run the game, simply compile the project using Gradle and launch the main application. You'll start at the home screen, input your name, and select the map variant.

During the game:
- Click on a grid square to place a tower or wall.
- Upgrade or sell towers by selecting them during the game.
- Track your castle's health and survive all enemy waves.

## 🏁 Game End

The game ends when:
- The castle is destroyed (game over), or
- All waves of enemies are defeated (you win!)

A final screen displays your score and top records, and allows you to restart or exit.

---

## 📌 Developer Note

This project helped me gain deeper understanding of:
- JavaFX scene management and animation
- Game state handling
- Real-time pathfinding and strategy-based enemy behavior
- Resource management and in-game economy

---

Feel free to clone or fork this project. Suggestions and improvements are welcome!
