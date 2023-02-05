# Homework 1

The goals of this homework assignment are:
1. To install Python and Anaconda on your machine
2. To get familiarized with Jupyter notebooks and basic Python code
3. To see examples of clustering (k-means in this case) applied to real data sets

## Assignment Instructions:
1. Follow the steps described below to install python and anaconda on your machine
2. Download to your computer the file "notebook_HW1.ipynb"
3. Do the activities within the notebook
4. Save a pdf of the completed notebook (e.g., in the notebook go to File --> Print Preview --> Print: CTRL+P --> Save to pdf)
5. Submit via email the pdf for the completed notebook.


### Installation instructions

#### Step 1:
Get Python installed in your machine. I suggest using the latest Anaconda distribution: https://www.anaconda.com/products/distribution

#### Step 2:
We will first create and activate a separate conda environment for the course. This is so it does not conflict with any other packages in your Python installation. **Open a terminal (Linux/mac) | an Anaconda Powsershell Prompt (Windows)** and run
```
conda create -n TDA python=3.9
```
```
conda activate TDA
```
Every time you want to run code from this course, you will need to activate the TDA environment as described above.
Next, we install the needed dependencies by running
```
pip install glasbey jupyterlab
```

To deactivate it (don't do it now) and go back to your base Python installation, simply run:
```
conda deactivate
```
