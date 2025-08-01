# Rocket League Bot

A simple RL-based agent that learns to play Rocket League using RLGym.

## Overview
This project trains a Rocket League bot with custom reward functions (goals, ball touches, speed toward ball, time in air) in a self-play environment.

## Prerequisites
- Python 3.11  
- RLGym 2.0.1 (`pip install rlgym[all]`)  
- Rocket League (Steam/Epic) installed  

## Policy Reward

The policy reward is the cumulative feedback signal that your PPO agent receives each episode. It reflects how well the agent is achieving your defined objectives (e.g., scoring goals, hitting the ball). You can plot this reward over training runs to see how learning progresses:

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/nardonej3atwit/Individual-DS-Project/blob/main/pictures/W%26B%20Chart%207_31_2025%2C%2011_04_46%20PM.png" alt="Policy Reward" style="width:45%;">
</div>

The pink line indicates the most recent run where I gave the agent a huge reward for hitting the ball and scoring, thhis is why it is so much higher than all the previous runs
