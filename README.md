# Deep RL Quadcopter Controller


In this project, I have designed an agent to take off a quadcopter, and then train it using a Deep Deterministic Policy Gradients reinforcement learning algorithm based on this [paper](https://arxiv.org/pdf/1509.02971.pdf).
## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/jcarlosgm30/RL_Quadcopter.git
cd RL_Quadcopter
```

2. Create and activate a new environment.

```
conda create -n quadcop python=3.6 matplotlib numpy pandas
source activate quadcop
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `quadcop` environment. 
```
python -m ipykernel install --user --name quadcop --display-name "quadcop"
```

4. Open the notebook.
```
jupyter notebook Quadcopter_Project.ipynb
```

5. Before running code, change the kernel to match the `quadcop` environment by using the drop-down menu (**Kernel > Change kernel > quadcop**). Then, follow the instructions in the notebook.

6. You will likely need to install more pip packages to complete this project. You will need the next packages:
```
matplotlib==2.0.0
numpy==1.14.1
pandas==0.19.2

```
