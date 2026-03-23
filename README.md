# Helicopter RL Agent

This project trains a reinforcement learning agent to master a retro helicopter arcade game. It uses a custom Gymnasium environment to interface with the game and the PPO algorithm from Stable-Baselines3 for learning optimal flight control. The work explores applying modern RL techniques to classic game dynamics.

## Key Features
* Custom Gymnasium environment for the helicopter game.
* Agent training using the PPO algorithm from Stable-Baselines3.
* Evaluation scripts to visualize and assess the trained agent's performance.
* Configurable hyperparameters for training and environment settings.

## Tech Stack
* Python
* Gymnasium
* Stable-Baselines3
* PyGame

## Getting Started
1. Clone the repository: `git clone https://github.com/zoreanuj/helicopter-rl-agent.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run training: `python train.py`
4. Evaluate the agent: `python evaluate.py`