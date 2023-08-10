# Self-Driving-Car

Welcome to the Self-Driving Car with Q-Learning and Sand Drawing project! This project showcases a self-driving car simulation where the car learns to navigate an environment using Q-learning, a reinforcement learning technique. The user can interact with the environment by drawing sand, which acts as a slow-down zone for the car. 
## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Saving and Loading Learning](#saving-and-loading-learning)
6. [Drawing Sand](#drawing-sand)

## 1. Introduction

The Self-Driving Car with Q-Learning and Sand Drawing project demonstrates the application of Q-learning in creating a self-driving car that learns to navigate an environment. The car's speed varies based on the terrain it encounters: it slows down when driving on sand and maintains regular speed on other surfaces.

## 2. Features

- Self-driving car simulation using Q-learning
- Interactive sand drawing for creating slow-down zones
- Saving and loading learned Q-values
- Real-time visualization using the Kivy module

## 3. Installation

To run the project, you need to have Python and a few required packages installed. 
Modules:
1. numpy
2. pytorch
3. kivy
4. matplotlib

Install the required packages:

```
pip install -r requirements.txt
```

## 4. Usage

To start the self-driving car simulation, execute the following command:

```
python map.py
```

This will launch the simulation window, where you can observe the car's progress and interaction with the environment.

## 5. Saving and Loading Learning

The project allows you to save and load learned Q-values, enabling the car to resume learning from where it left off. Use the following commands:

- Save learning by pressing save button during simulation.
- Load learning by pressing load button during simulation.


## 6. Drawing Sand

You can interact with the simulation by drawing sand on the environment, which acts as a slow-down zone for the car. Follow these steps:

1. Press and hold the left mouse button to draw sand.
2. Release the mouse button to stop drawing.
