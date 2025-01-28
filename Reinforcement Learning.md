#### Reinforcement Learning 

Reinforcement learning is used for training models through interaction with an environment and learning through rewards and penalties.

### 1. **Q-Learning**

- **What it does**: Learns the best actions to take in an environment by updating a "Q-table" of rewards for each action.
- **Example**: A robot learning to navigate a maze by trying different paths and receiving rewards for reaching the exit.

------

### 2. **Deep Q-Network (DQN)**

- **What it does**: Combines deep learning with Q-Learning to handle environments with large action spaces.
- **Example**: Training an AI to play video games like Atari, where it learns strategies by observing the screen pixels.

------

### 3. **Policy Gradient Methods**

- **What it does**: Directly learns the policy (action strategy) by optimizing it to maximize rewards.
- **Example**: Teaching a robot to walk by learning a smooth sequence of movements to minimize energy usage.

------

### 4. **Actor-Critic Algorithms**

- What it does

  : Combines two approaches:

  - **Actor** decides what action to take.
  - **Critic** evaluates the action and provides feedback to improve it.

- **Example**: A self-driving car learning to drive efficiently while avoiding accidents (actor decides moves, critic evaluates safety and speed).

------

### 5. **Proximal Policy Optimization (PPO)**

- **What it does**: A stable and efficient RL algorithm that balances exploration and exploitation while optimizing the policy.
- **Example**: Training robots like robotic arms to pick up objects without dropping them by improving stability and precision.