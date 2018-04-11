[//]: # (Image References)
[image1]: ./docs/results.png "Agent Results"


# Reinforcement Learning
## Project: [Train a Smartcab How to Drive](https://github.com/udacity/machine-learning/tree/master/projects/smartcab)

## Project Overview

The objective of this project is to apply reinforcement learning techniques for a self-driving agent in a simplified world to aid it in effectively reaching its destinations in the allotted time. 

## Project Results 

![Agent Results][image1]

## Software Requirements
This project uses the following software and Python libraries:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [PyGame](http://pygame.org/)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer. `pygame` can then be installed using one of the following commands:

Mac:  `conda install -c https://conda.anaconda.org/quasiben pygame`  
Windows: `conda install -c https://conda.anaconda.org/prkrekel pygame`  
Linux:  `conda install -c https://conda.anaconda.org/tlatorre pygame`  

## Starting the Project
This project contains three directories in the **src** folder:

- `/logs/`: This folder will contain all log files that are given from the simulation when specific prerequisites are met.
- `/images/`: This folder contains various images of cars to be used in the graphical user interface. 
- `/smartcab/`: This folder contains the Python scripts that create the environment, graphical user interface, the simulation, and the agents. `agent.py`.

It also contains two files:
- `smartcab.ipynb`: The jupyter notebook.
- `visuals.py`: This Python script provides supplementary visualizations for the analysis.

Finally, in `src/smartcab/` are the following four files:
  - `agent.py`: Contains the agent code.
  - `environment.py`: This Python file will create the *smartcab* environment.
  - `planner.py`: This Python file creates a high-level planner for the agent to follow towards a set goal.
  - `simulation.py`: This Python file creates the simulation and graphical user interface. 


### Running the Code
In a terminal or command window, navigate to the top-level project directory `src` and run one of the following commands:

`python smartcab/agent.py` or  `python -m smartcab.agent`

Additionally, use the command `jupyter notebook smartcab.ipynb` from this same directory to open up a browser window or tab to work with the notebook.


