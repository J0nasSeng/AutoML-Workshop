# AutoML-Workshop
This repository contains all necessary resources to follow along the NHR4CES Workshop on AutoML.

Below you will find instructions on how to get started with this repository on your local system and on Google Colab.

## Local Setup
To start the notebooks in this repo, you have to install anaconda on your local system. If you haven't done this, please refer to the [official website](https://docs.anaconda.com/anaconda/install/linux/).

After you have installed anaconda, clone the repository and change in the notebooks-directory:
```
git clone https://github.com/J0nasSeng/AutoML-Workshop.git
cd AutoML-Workshop/notebooks/
```
Then, you have to install the conda environment, e.g. as follows:
```
conda env create --name aml --file=./env.yml 
```
If the environment is successfully installed, all required packages can be installed via pip:
```
pip install -r requirements.txt
```

Once alle commands succeed you should be able to start all notebooks and import all relevant packages.

## Google Colab
In Colab you have to open the notebook by navigating to *File --> Open Notebook*, then just enter the git-URL from above and open the hyperparameter-optimization notebook first. Then, copy the `requirements.txt` from this repository to your colab-space and rund the first cell of the notebook. Now you should be able to run the code.