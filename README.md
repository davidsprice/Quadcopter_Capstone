# Quadcopter_Capstone
Capstone project for Udacity Advanced Machine Learning nanodegree.  THIS IS A DRAFT!  THE PROJECT PROPOSAL HAS NOT YET BEEN SUBMITTED AND THE CODE ISN'T WORKING!

# Quadcopter
Quadcopter project for the Advanced Machine Learning course of Udacity's Machine Learning nano-degree.

## Target :
Training a reinforcement learning (RL) agent (quadcopter controller) to learn to fly and perform the defined tasks in direction to maximise reward.

## Algorithm Class :
Deep Deterministic Policy Gradients (DDPG)

## Problem Type :
Continuous Control Task

## Final Result :
Final Reward-Episode Plot :

![](Final_Quadcopter_Reward_Plot.png)

# Project Instructions
1. Clone the repository and navigate to the downloaded folder.

~~~~
git clone https://github.com/davidsprice/Quadcopter
cd Quadcopter
~~~~

2. Create and activate a new environment.

~~~~
conda create -n quadcopter python=3.6 matplotlib numpy pandas keras-gpu
source activate quadcopter
~~~~

3. Create an [IPython kernel](https://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the quadcopter environment.

~~~~
python -m ipykernel install --user --name quadcop --display-name "quadcop"
~~~~

4. Open the notebook.

~~~~
jupyter notebook Quadcopter_Project.ipynb
~~~~

5. Before running code, change the kernel to match the quadcop environment by using the drop-down menu (Kernel > Change kernel > quadcop). Then, follow the instructions in the notebook.

6. You will likely need to install more pip packages to complete this project. Please curate the list of packages needed to run your project in the requirements.txt file in the repository.
