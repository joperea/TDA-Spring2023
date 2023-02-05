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
5. **Submit via email the pdf** for the completed notebook. **Due:** 2/12/2023 


### Installation instructions

#### Step 1:
Get Python installed in your machine. I suggest using the latest Anaconda distribution: https://www.anaconda.com/products/distribution

#### Step 2:
We will first create and activate a separate conda environment for the course. This is so we don't create conflicts with any other packages in your Python installation. **Open a terminal (Linux/mac) | an Anaconda Powsershell Prompt (Windows)** and run
```
conda create -n TDA python=3.9
```
```
conda activate TDA
```
Every time you want to run code from this course, you will need to activate the TDA environment as described above.
Next, we install the needed dependencies by running
```
pip install glasbey scikit-learn jupyterlab
```

To deactivate it (don't do it now) and go back to your base Python installation, simply run:
```
conda deactivate
```

#### Step 3:
Download the "notebook_HW1.ipynb" file to your computer. 
* Option 1: Use the following [link](https://joperea.squarespace.com/s/notebook_HW1.ipynb)
* Option 2: Clone this repository and the file will be in your machine locally
* Option 3: Click on the file name in the repository, click raw, download as .txt, rename to .ipynb ; see [this video](https://www.gitkraken.com/learn/git/github-download#how-to-downlaod-a-file-from-github)

#### Step 4:
Open the donwloaded juPyter notebook: In the currently opened terminal (with the TDA environment activated) run:
```
jupyter notebook
```
navigate to the location of the donwloaded file and click on it.

