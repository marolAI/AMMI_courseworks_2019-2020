# Convolutional Network Tutorials (AMMI 2020)
These are the tutorials for the Convolutional Neural Networks class of the African Master's in Machine Intelligence given by Laurens van der Maaten and Aaron Adcock.

The tutorials are iPython Notebooks in which you have to implements missing parts of the code yourself, run small experiments, and answer questions about the results of your experiments. The notebooks should be pretty self-contained.

## Run notebooks on Google Cloud via colab

You can run the notebooks on Google Cloud via colab. The advantage of this approach is that your experiments will run on Google's servers, which are likely faster than your own laptop. You will need a stable wifi connection to use colab. The following links take you to the colab notebooks:

* [Tutorial 1](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/convnet_tutorial1.ipynb)
* [Tutorial 2](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/convnet_tutorial2.ipynb)
* [Tutorial 3](https://colab.research.google.com/github/lvdmaaten/convnet_tutorials/blob/master/convnet_tutorial3.ipynb)

## Run notebooks locally using Jupyter

You can also run the tutorial notebooks locally on your laptop. This way, you do not need an internet connection while you are working on most parts of the tutorial.

Running notebooks locally is done via [Jupyter](https://jupyter.org/). If you do not have Jupyter installed yet, you first we need to create a Conda environment (see [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for details). To do so, `git clone` this repository and run the following commands in your Terminal from the `ammi-2020-ConvNets` directory: 

Installing packages from conda environment:
```
conda env create -f ammi_2020_convnet_env.yml
conda activate ammi_2020_convnets
```
Installing the packages from requirements file:
```
conda create -n ammi_2020_convnets
conda activate ammi_2020_convnets
pip3 install -r requirement.txt
```
You can run `conda env list` to confirm the `ammi_2020_convnets` environment is activated.

Next, start Jupyter Notebook by going into the `ammi-2020-ConvNets` directory in your Terminal and running `jupyter notebook`. This will open a browser window with the Jupyter notebook interface. In this interface, you can navigate to the correct folder and open the tutorial notebooks (with the `.ipynb` extension) to run them.
