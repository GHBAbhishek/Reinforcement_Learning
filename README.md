
# Agent Following Path using Reinforcement Learning

This project demonstrates how an agent can learn to follow a predefined path using **Q-learning**, a popular Reinforcement Learning (RL) algorithm. The environment is built on a simple 2D grid using **Tkinter**, where the agent learns to navigate toward the goal by updating its Q-values based on rewards.

## 🧠 Features

- **8x8 Grid Environment**
- **Q-learning Algorithm** for learning optimal paths
- Graphical visualization using **Tkinter GUI**
- Path-following behavior based on Q-values
- Custom reward setup for learning guidance

## 🗂️ Project Structure

- `Agent_Following_Path_RL.ipynb`: Jupyter Notebook containing the full implementation of the grid environment, agent logic, Q-learning loop, and visualization.
- Interactive simulation window powered by Tkinter GUI.

## ⚙️ Requirements

Make sure you have the following installed:

```bash
Python >= 3.7
```

Install required libraries:

```bash
pip install numpy
```

Tkinter is typically included with Python installations, but you can install it using:

- For Ubuntu/Debian:
  ```bash
  sudo apt-get install python3-tk
  ```
- For Windows: Included with default Python installation.

## 🚀 How to Run

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Agent_Following_Path_RL.ipynb
   ```
2. Run all cells step by step to initialize the grid, train the agent using Q-learning, and visualize its movement.
3. The agent will learn to follow a path toward the goal over multiple episodes.

## 📈 Learning Behavior

- The agent is initialized at a starting position.
- It explores the grid and learns optimal moves using the Q-learning algorithm.
- Rewards:
  - Positive reward for reaching the goal.
  - Negative or zero rewards for non-goal steps (can be configured).
- Over episodes, the agent improves its policy to minimize steps and reach the goal efficiently.

## 📝 Customization

- Grid size, rewards, and Q-learning parameters (learning rate, discount factor, exploration rate) can be modified for experimentation.
- Can be extended to support obstacles or multiple agents.

## 🔧 Q-learning Parameters

- **Learning rate (α)**: Controls how much new information overrides old information.
- **Discount factor (γ)**: Balances immediate vs future rewards.
- **Exploration rate (ε)**: Balances exploration and exploitation during training.

## 📌 TODO / Future Improvements

- Add support for **walls/obstacles**
- Add **SARSA agent** for comparative learning
- Implement **score tracking**
- Export learned Q-values for reuse
- Support for **multi-agent environments**

## 📄 License

This project is open-source and free to use for educational or research purposes.
