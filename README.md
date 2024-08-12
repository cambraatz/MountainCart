# OpenAI Gymnasium Lab
<a href="https://gymnasium.farama.org/">OpenAI Gymnasium</a>

The OpenAI Gymnasium is a reinforcement learning playground, with MDP problems ranging from simple to complicated single agent environments. The following report has been prepared by Cameron Braatz as an academic project for CSPB 3202: Intro to Artificial Intelligence at CU-Boulder.

## Environment Selection
For this project, I decided to go with **Mountain Car** from the **Classic Control** library. According to the documentation, the Mountain Car MDP is a deterministic problem that sees a cart placed stochastically at the bottom of a sinusoidal valley. The goal of which is to teach our cart-agent to climb the hill on the right, reaching the goal state (ie: flag). 

The agent does not have the sheer power to drive directly uphill to the flag, instead needing to gather its momentum before making a successful ascent. See demonstration below.

https://github.com/user-attachments/assets/8229b780-892b-4f8b-80ab-cf080abb7184

Please refer to `IntroToGymnasium.ipynb` for the complete project notebook. Note: Video files do not seem to be rendering correctly in the GitHub environment, please see `https://github.com/cambraatz/MountainCart/assets` for all figures and videos used in the Python notebook.

<a href="https://gymnasium.farama.org/environments/classic_control/mountain_car/">OpenAI Gym: Mountain Cart</a>
