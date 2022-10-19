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

## Interview Procedures

1. Install Python environment correctly and run the Jupyter Notebook S2S/S2S_Using_Synthetic_Data_Interview.ipynb
2. Answer the following question: 2.1 Please describe the mechanism of the algorithm and steps of the code. 2.2 How does the code deal with model uncertainties? 2.3 What can you do to improve the model accuracy?
3. Coding Task 1: Modify/Tune the model parameter to achieve higher accuracy
4. Coding Task 2: Apply better feature engineering to achieve higher accuracy
4. Coding Task 3: Select a machine learning algorithm by yourself and compare its performance with this model.
6. Write a short summary of your understanding of this code and what you learned from this practice

Follow the procedures above and save it as a new file named "S2S_Using_Synthetic_Data_Interview_Your Name.ipnyb". Send it back to Dr. Liang Zhang at liangzhang1@arizona.edu before deadline.
