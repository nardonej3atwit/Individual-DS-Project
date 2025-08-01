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

![Policy Reward](picture/W&B Chart 7_31_2025, 11_05_04 PM.png)

The pink line indicates the most recent run where I gave the agent a huge reward for hitting the ball and scoring, thhis is why it is so much higher than all the previous runs
