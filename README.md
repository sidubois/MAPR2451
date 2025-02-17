[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sidubois/MAPR2451/master)

# SuperTB
Special distribution of Supertb package (v1.0.1) for the purpose of the LMAPR2451 tight-binding tutorial


### Instructions to use the material remotely
The tutorial is accessible on Google Colab at:
https://colab.research.google.com/github/sidubois/MAPR2451/blob/master/MAPR2451.ipynb

### Instructions to use the material locally on your own computer.
If not done yet, install conda :
see https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

Get the files from github and change to the project directory : 
```
git clone https://github.com/sidubois/MAPR2451
cd MAPR2451
```
Create and activate an environment for the project :
```
conda create --name MAPR2451 python=3.12
conda activate MAPR2451
```
Install the Jupyter-notebook package : 
```
pip install notebook
```
You are now ready to run the jupyter notebook :
```
jupyter notebook &
```
The landing page of the Jupyter notebook web application, the dashboard, should show the MAPR2451 notebook that contains the instructions and codes for the tight-binding lab. You may open open it by clicking on its name, *MAPR2451.ipynb* .
