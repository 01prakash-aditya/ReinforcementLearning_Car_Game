Reinforcement Learning Car Game
This repository contains a reinforcement learning-based car game developed in Python. The game leverages reinforcement
learning algorithms to enable a car to autonomously navigate through a track, learning optimal driving strategies over time.

Features
Autonomous Driving: The car learns to drive itself using reinforcement learning techniques.
Customizable Tracks: Users can design and modify tracks to test the car's learning adaptability.
Performance Metrics: Track the car's learning progress and performance over time.

Files
agent.py – Implements the DQN-based agent using ray tracing for obstacle detection and decision-making.
updated_main.py – The main game loop managing rendering, event handling, and agent interaction.
track.py – Handles track generation and game physics.
config.txt – Stores configuration parameters for the game and agent.
racing.png & racing-car.png – Image assets used in the game.
requirements.txt – Lists dependencies needed to run the project.

Installation:: 

Clone the Repository:
git clone https://github.com/01prakash-aditya/ReinforcementLearning_Car_Game.git
cd ReinforcementLearning_Car_Game

Install Dependencies:
Ensure you have Python installed. Then, install the required packages:
pip install -r requirements.txt

Run the game:
python updated_main.py

Controls
The agent runs autonomously, adjusting direction based on sensor input.
In the Play Game option, user can play using arrow keys.
