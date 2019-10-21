# Navigation Project Submission

## Introduction

In this project , agent is trained using the Double DQN algorithm to navigate (and collect bananas!) in a large, square world.  

### Setup
The project uses environments from Unity.  In order to make the environments work:
1. Install the unityagents package using:
   * pip install unityagents --no-deps. 
2. Download the environment from one of the links below matching your environment your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

3. Place the file in this folder, and unzip (or decompress) the file. 


## Environment

### Reward:
 - A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.
 - The goal of the  agent is collecting  as many yellow bananas as possible while avoiding blue bananas.  

### State Space and Actions
- The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.

-Four discrete actions are available, corresponding to:
  - **`0`** - move forward.
  - **`1`** - move backward.
  - **`2`** - turn left.
  - **`3`** - turn right.

- The task is episodic.

### Instructions
Run the  `Navigation-submission.ipynb` to train and evaluate the agent. 

### Information
The code in this repo is heavily-based on the code given in the Udacity Nano Degree  Program resources.

