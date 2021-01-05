# MachineLearning-case-study
Project Work on Intelligent Systems, course of Master of Science in Computer Engineering.

## Description
In this project work I explore a **dataset which contains data about an energy management system with uncertain renewable generation and load demand.**  
More precisely there are a set of 100 different instances of these data, that are briefly called *PV* (PhotoVoltaic) and *Load*. These data are gathered from the observation of a Virtual Power Plant.  
On each of these istances an online fixing euristhic algorithm has run for 100 times, each with a different number of traces (from 1 to 100), with the aim to predict the value (in keuro) of the energy that has to be produced from the system to supply the Load. This value is briefly called *sol(keuro)*.  
For each instance, the dataset contains so, also information about the run of the euristhic, such as *time* to run, *memAVG* required to run, *nTraces* considered ecc...

After an **exploration of the dataset**, I studied and develop some different **Machine Learning Regression models** (Linear Regressor, Regression Trees, Multi Layer Perceptron Regressor) **to predict a given target with some known features.**  
I used the **Python** language and some useful libraries like *Numpy*, *Pandas*, *Scikit Learn*, *MatplotLib*...

To know more, you can read the *PIAZZA-Report_Finale.pdf* file that describe the entire project and the results obtained!  
Otherwise, you can follow the instruction in the next section, open the notebook file that contains the code, and explore it!

## Setup and run
1. Clone or Download the repository
2. Download and Install [Jupyter Notebook](https://jupyter.org/index.html!)
  - If you use Conda package manager type:   
    `conda install -c conda-forge notebook`
  - If you instead use pip package manager type:  
    `pip install notebook`
2. Open a terminal in the project folder and run  
   `jupyter notebook`
  
