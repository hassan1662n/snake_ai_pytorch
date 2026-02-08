# 🐍 Snake AI Game (PyTorch + Pygame)

An AI-powered Snake game built using **Python**, **Pygame**, and **PyTorch**, where the snake learns to play the game using **Deep Q-Learning (DQN)**.

The project includes:
- A fully playable Snake game in Pygame
- A reinforcement learning agent trained with PyTorch
- Real-time training visualization
- An improved version where the agent learns better over time

---

## 🎮 Game Preview

### Snake Game Gameplay
> Below is a screenshot of the Snake AI game running in Pygame:

![Snake Game Screenshot](images/game.png)

---

## 📈 Training Progress

The graph below shows how the agent improves over time as it plays more games and learns from experience:

![Training Progress Graph](images/training_graph.png)

- X-axis: Number of games played  
- Y-axis: Score  
- The mean score increases as the agent learns better strategies

---

## 🧠 How the AI Works

This project uses **Deep Q-Learning (DQN)**:

- The game state is converted into numerical features (danger, direction, food position)
- A neural network predicts the best action:
  - Go straight
  - Turn right
  - Turn left
- The agent learns from:
  - Rewards for eating food
  - Penalties for crashing into walls or itself
- Experience replay is used to stabilize training

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **PyTorch**
- **Pygame**
- **NumPy**
- **Matplotlib**

---

## 📂 Project Structure


