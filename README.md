# Data-Driven Control Rovers Navigation
## Introduction
This is a project work that I developed, with the support of a team, for the MSc Computer Engineering course of Data Driven Control Design at University of Salerno, Italy.

The objective of the project is to develop two data-driven algorithms for unicycle robots to navigate in uncertain environments. The robot is required to:
- reach a desired destination;
- avoid obstacles.

In this context, we designed two algorithms that are crucial to enable autonomous navigation:
- a forward data-driven control algorithm (FOC) to compute the optimal policy given the position of the robot and the obstacles;
- an inverse data-driven control algorithm (IOC) to estimate, from observations, the robot navigation cost. 

Moreover, we validated the results by leveraging a state-of-the-art robotics platform: the Robotarium by Georgia Tech. The platform offers both a high fidelity simulator and a remotely accessible experimental hardware facility. 

## Contents
- `project_work.ipynb`: Main Jupyter notebook file for the project work. It is organized in sections, each of which corresponds to a specific task of the project.
- `img` folder: Contains some simulation images and plots referenced in the Jupyter notebook.
- `videos` folder: Contains some videos of the hardware deployment using the Robotarium platform.

## Requirements
Requirements are listed in the `requirements.txt` file.

## References
- [Forward Optimal Control](https://arxiv.org/abs/2306.13928)
- [Inverse Optimal Control](https://arxiv.org/abs/2306.13928)
- [Robotarium](https://www.robotarium.gatech.edu/)