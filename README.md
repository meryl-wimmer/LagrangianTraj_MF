# LagrangianTraj_MF

## Description: 
Scripts to compute Lagrangian trajectories for different models :

 - AROME
 - ARPEGE
 - ICON
 - ERA5

To come : LMDZ and adaptation for long time step

## How to use:

#### 1) Download the git repository: 

git clone https://github.com/meryl-wimmer/LagrangianTraj_MF.git

or

git clone git@github.com:meryl-wimmer/LagrangianTraj_MF.git

#### 2) Create and use a python virutal environnement (named MyVenv) in Jupyter Notebook: 

python -m venv MyVenv 

pip3 install --user ipykernel

python -m ipykernel install --user --name=MyVenv

pip install cfgrib # and other needed python packages that are not already installed in your virtual environnement

#### 3) Open Jupyter Notebook :

jupyter-notebook &

Then, select MyVenv in Kernel/Change Kernel

#### 4) To run each block :

Click on the play button

## Authors: 
 - Meryl WIMMER
 - Philippe ARBOGAST
 - Vinita DESHMUKH
 - Léo DUCONGE
 - Gwendal RIVIERE
 - Sébastien FROMANG
 - Nicolas CHIABRANDO
 - Carole LABADIE

Contact : meryl.wimmer@meteo.fr

