# 🏰 Knight’s Castle – AI Generated Levels  
🔗 Repository: https://github.com/Ashlehloh/Gemini-3-Game

This is a team-based game project built during the **Gemini 3 Hackathon**.

Knight’s Castle is a 2D pixel-art game inspired by the Game Boy style, where a knight explores procedurally generated levels with **AI-powered difficulty balancing and map generation** using Google Gemini.

The game adapts its levels based on how the player performs in a tutorial stage and generates new maps based on player-written descriptions.

---

## 🎯 Project Objective

The goal of this project is to:

- build a playable 2D game with AI-driven level generation
- use player performance data to dynamically adjust game difficulty
- allow players to describe custom maps and generate them using an AI model
- demonstrate how generative AI can be integrated into real-time game systems

---

## 🧱 Key Features

- **Tutorial level**
  - Learn the basics by defeating 3 dogs in a dark castle
  - Player metrics are collected during gameplay

- **AI-powered level generation**
  - Levels are generated using Google Gemini based on:
    - tutorial performance (time taken, remaining health, deaths)
    - player-written map description
    - randomly generated game styles (combat, puzzle, racing, etc.)

- **Dynamic difficulty adjustment**
  - Enemy count, enemy health and overall difficulty are automatically tuned based on player performance

- **Custom map generation**
  - Players can describe their own map (e.g. “a spooky forest with twisted trees”)
  - The AI generates the layout, theme and features

- **Procedural gameplay loop**
  - Players can continue playing newly generated levels indefinitely

---

## 👩‍💻 My Role

This was a team project completed during the Gemini 3 Hackathon.  
I contributed to the design and development of the game and the AI-driven level generation workflow together with my teammates.

---

## 🛠️ Tech Stack

- Python
- Pygame
- Google Gemini API
- AI-driven procedural content generation

---

## 🧠 What this project demonstrates

- Integrating generative AI into a real-time game system
- Using player performance metrics to drive adaptive difficulty
- Procedural content generation using natural language input
- Rapid prototyping and collaboration in a hackathon environment

---

## ▶️ Installation

```bash
pip install -r requirements.txt
