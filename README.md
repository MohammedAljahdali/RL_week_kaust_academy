# Conda env setup

To create the env locally follow the following steps:

First create the env using the following command:

`conda env create -f conda_env.yaml`

Then activate the env using the following command:

`conda activate RL`

Finally, lunch jupyter lab using the following command:

`jupyter lab`


# Running on Collab
To run on google collab all you need is to open the notebook their, and install the correct version of the gym library using the following command in a code cell:

`!pip install gym==0.26.2`
