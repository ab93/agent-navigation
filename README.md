# Deep Reinforcement Learning: Navigation

This repository contains my solution for Udacity's Deep Reinforcement Learning Nanodegree's Navigation project

## Project Details

The main idea of this project is to make an agent navigate a virtual world, with the goal of collecting as 
many yellow bananas as possible, while avoiding blue bananas.

The virtual environment is provided by Udacity and is based on Unity ML agents. This is an episodic task.

The agent gets a reward of +1 from the environment for collecting a yellow banana, while for collecting a blue banana, it gets a reward of -1.

The state space is continuous and has 37 dimensions. Agent’s velocity, along with ray-based perception of objects around it’s forward direction.

The action space is discrete. Namely, there are 4 of them:

    • 0 – move forward
    • 1 – move backward
    • 2 – turn left
    • 3 – turn right

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started

### Install Python dependencies
- Clone the project for running in your local environment.
- Install the required Python dependencies as mentioned in the [Udacity DeepRL Nanodegree](https://github.com/udacity/deep-reinforcement-learning#dependencies).

### Download the Unity Environment
1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file inside the navigation-project repository, e.g. in Linux your project directory will look like this:
    
    - `Banana_Linux/`
    - `dqn_agent.py`
    - `model.py`
    - `...`
    
## Instructions

- Execute `Navigation.ipynb` notebook after following the steps in the "Getting Started" section.
- The trained weights by default will be saved in `checkpoint.pth` file.
- For the full report and explanation of the algorithm, checkout `Report.pdf`.
