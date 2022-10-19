# intelcamp_S2S

Deep learning algorithms for probabilistic sequence-to-sequence (S2S) forecasting of time series campus building energy consumption.

This is a work-in-progress.

Author: Liang Zhang @ U of A

## Installation

Download and install the latest version of [Conda](https://www.anaconda.com/products/distribution)

Run Anaconda Prompt as Administrator

Create a new conda environment:

`$ conda create -n <enter-the-name-of-repository-here> python=3.8 pip`

`$ conda activate <enter-the-name-of-repository-here>`

Ensure that you have navigated to the top level of your cloned repository. You will execute all your pip commands from this location. For example:

`$ cd /path/to/repository`

Install the environment needed for this repository:

`$ pip install -e .[dev]`

## Run Jupyter Notebooks

`S2S/S2S_Cafe_Synthetic_Cafe_GitHub.ipynb` is the notebook to demonstrate the algorithms performance in two NREL buildings

`S2S/S2S_Self_Defined_Data_GitHub.ipynb.ipynb` is the notebook to use your own data to run under this algorithm. Follow the instructions in the notebook to correctly prepare your own data to be run successfully in the code.
