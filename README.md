# Breast-Cancer-Prediction-Logistic-Regression-Project

logistic regression breast cancer project by shrinivas pratapgiri

Project link: https://srinipratapgiri.medium.com/logistic-regression-breast-cancer-prediction-935ecd990b2a

my old project link : https://github.com/vipulwarthe/Breast-Cancer-Prediction-Logistic-Regression-Project

Dataset link:

https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

https://www.kaggle.com/uciml/breast-cancer-wisconsin-data?select=data.csv

First we Create instance with ubuntu AMI with t2.medium instance type with 30GB storage

1 sudo apt-get update && sudo apt-get upgrade -y (update the packages)

2 sudo apt install python3-venv -y (install python environment)

3 python3 -m venv MLPRO (create environment name MLPRO)

if you are connecting locally with jupyter notebook then use below 3 cmds:

1 python3 -m venv MLPRO python=3.9 ipykernal=Cancer

2 pip install notebook

3 jupyter notebook (paste the token)

4 source MLPRO/bin/activate (activate the environment)

5 deactivate (to deactivate the envirnoment)

5 mkdir mlproject (create one project directory)

6 cd mlproject (enter in project directory)

7 chmod 700 mlproject

OR you can directly clone the repo from github and start working...

Login to your github account and create a new repo git remote -v (additional command)

create setup.py and requirements.txt in mlproject repo add a code in setup.py & requirements.txt

setup.py will be responsible in creating my ML application as a package and also used to build and distribute Python packages.

requirements.txt file is a type of file that usually stores information about all the libraries, modules, and packages in itself that are used while developing a particular project

8 pip install -r requirements.txt
