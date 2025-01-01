# Quick Start
## Cloning the Repo
Open terminal on your PC, then press `win+R`, enter `cmd`

Navigate to the location where you want to clone the folder and excute the following command:
* For ssh:
`git clone git@github.com:aberkipek/concrete-compressive-strength-prediction.git`
* For https:
`git clone https://github.com/aberkipek/concrete-compressive-strength-prediction.git`

After cloning the repo, navigate to the project directory:
`cd concrete-compressive-strength-prediction`

## Create Virtual Environment for Python
Run the following command:
`python -m venv <your-venv-name>`

* To Activate: `<your-venv-name>\Scripts\activate`
* To Deactivate: `deactivate`

## Installing the Dependencies
After setting venv, run the following command to install all the project dependencies:
`pip install -r requirements.txt`

## Add the Virtual Environment as a Kernel in Jupyter
Run the following command:
`python -m ipykernel install --user --name=<your_venv_name> --display-name "<your_venv_name>"`
* To list kernels: `jupyter kernelspec list`
* To delete a kernel: `jupyter kernelspec remove <env-name>`

## Open the Project
Run `jupyter notebook` inside your directory to run the project.

You can use Jupyter Notebook or any IDE you like to open the project.

### Note: Do not forget to add your venv to .gitignore to separete it from version control :)
