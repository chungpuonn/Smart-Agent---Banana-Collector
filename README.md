# Smart-Agent---Banana-Collector
For this project, an agent is being trained to navigate (and collect bananas!) in a large, square world.

[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

****
  
## Getting Started
### Dependencies 

By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to run this project.

#### __Step 1__
To set up your python environment to run the code in this repository, follow the instructions below. 



1. Create (and activate) a new environment with Python 3.6. 

    - __Linux__ or __Mac__:  

    ```bash 

    conda create --name drlnd python=3.6 

    source activate drlnd 

    ``` 



2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.   

    - Install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d). 
    
    ****

3. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies. 

    ```bash 

    git clone https://github.com/chungpuonn/Smart-Agent---Banana-Collector.git 

    cd Smart-Agent--Banana-Collector/python 

    pip install . 

    pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org torch===0.4.0 torchvision===0.2.0 tensorflow==1.7.1 -f https://download.pytorch.org/whl/torch_stable.html

    ``` 

  

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.   

    ```bash 

    python -m ipykernel install --user --name drlnd --display-name "drlnd" 

    ``` 

****
#### __Step 2__
Download the Unity Environment:

For this project, you need not to install Unity - the environment have already built, and you can download it from one of the links below. You need only select the environment that matches your operating system:

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)


Then, place the file in the `p1_navigation/` folder in the course GitHub repository, and unzip (or decompress) the file.  Next, open `Navigation (Solution).ipynb` and follow the instructions to learn how to use the Python API to control the agent.

****
## Instruction

### How-to run the code

Open the Jupyter Notebook of "Navigation (Solution).ipynb", and then follow the written instruction inside to train and deploy a smart agent!

__Note:__ Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu.  
  

[//]: # (Image References)

[image2]: /src/Value-based-methods/Smart-Agent---Banana-Collector/image/ipynb_kernel.png "Trained Agent"

![Jupyter Notebook Kernel][image2]

****
