#  Lunar Lander – Deep Q-Network (DQN)

## **Overview**
This project implements a **Deep Q-Network (DQN)** agent to solve the **LunarLander-v3** environment from Gymnasium.  
The agent learns to control the lander's thrusters to achieve a safe landing on the target pad using **reinforcement learning** techniques.  

The environment is considered solved when the **average reward of the last 100 episodes exceeds 200**.

---

## **Key Features**
- **Environment**: `LunarLander-v3` (Box2D physics).
- **DQN Implementation**:
  - Neural network with 2 hidden layers of 64 neurons each.
  - Experience Replay buffer for stable training.
  - Target Q-network synchronization.
  - Epsilon-greedy policy with decay for exploration vs exploitation.
- **Training Performance**:
  - Solves the environment in ~**500 episodes**.
- **Video Generation**:
  - Renders agent performance as `.mp4` videos.
- **Visualization**:
  - Plots rewards over training episodes.

---

## **Tech Stack**
- **Language**: Python 3.11+
- **Libraries**:
  - `tensorflow` (for DQN model)
  - `gymnasium[box2d]`
  - `numpy`, `matplotlib`, `imageio`, `pandas`
  - `pyvirtualdisplay` (for headless rendering)

---

