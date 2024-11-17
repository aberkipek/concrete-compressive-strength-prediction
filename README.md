# Quick Start
## Cloning the Repo
Navigate to the location where you want to clone the folder and excute the following command:
* Open terminal on your PC, then press `win+R`, enter `cmd`
* For ssh:
`git clone git@github.com:aberkipek/concrete-compressive-strength-prediction.git`
* For https:
`git clone https://github.com/aberkipek/concrete-compressive-strength-prediction.git`

## Create Virtual Environment for Python
* Then run the following command:
`python -m venv <your-venv-name>`

* To activate/deactivate:
Activate: `<your-venv-name>\Scripts\activate`
Deactivate: `deactivate`

## Installing the Dependencies
After setting venv, run the following command to install all the project dependencies:
`pip install -r requirements.txt`

Finally use Jupyter Notebook or any IDE you like to open the project file. 
(/src/concrete-compressive-strength.ipynb)

### Note: Do not forget to add your venv to .gitignore to separete it from version control :)
