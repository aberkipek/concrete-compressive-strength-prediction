# Quick Start
## Cloning the Repo
* Open terminal on your PC, then press `win+R`, enter `cmd`

Navigate to the location where you want to clone the folder and excute the following command:
* For ssh:
`git clone git@github.com:aberkipek/concrete-compressive-strength-prediction.git`
* For https:
`git clone https://github.com/aberkipek/concrete-compressive-strength-prediction.git`

After cloning the repo, navigate to the project directory:
`cd concrete-compressive-strength-prediction`

## Create Virtual Environment for Python
* Then run the following command:
`python -m venv <your-venv-name>`

* To activate/deactivate:
Activate: `<your-venv-name>\Scripts\activate`
Deactivate: `deactivate`

## Installing the Dependencies
After setting venv, run the following command to install all the project dependencies:
`pip install -r requirements.txt`

Finally, use Jupyter Notebook or any IDE you like to open the project.
(/src/concrete-compressive-strength.ipynb if you use Jupyter Notebook)

### Note: Do not forget to add your venv to .gitignore to separete it from version control :)
