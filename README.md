### Project Overview

This my final project, in this project I trained an agent to pick up yellow bananas that are scattered throughout a square world. The agent
 must learn to navigate in its environment to reach yellow bananas (reward of +1 each) while avoiding to collect
 blue bananas (reward of -1 each). 

### Instructions

Follow the instructions in `final_project.ipynb` to train an agent from scratch or simply watch a pretrained agent

### Settings
To set up your python environment to run the code, follow the instructions below.
1.	Create (and activate) a new environment with Python 3.6.

    o	Linux or Mac:
    
             conda create --name drlnd python=3.6
        
             source activate drlnd
        
    o	Windows:
    
             conda create --name drlnd python=3.6 
        
             activate drlnd
        
        
2. terminal:         
                                      
          pip install ipykernel

3. Create an IPython kernel for the drlnd environment.

          python -m ipykernel install --user --name drlnd --display-name "drlnd"
      
     
4. Before running code in a notebook, change the kernel to match the ‘drlnd’ environment by using the drop-down Kernel menu.
5. terminal: 

          pip install unityagents,torch,scipy
                 
7. I have download the unity file in the package ,if you want to update Banana.unity, go to this github source https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation

6. Follow the instructions in Navigation.ipynb to test the environment.
