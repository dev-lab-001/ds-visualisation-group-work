[![Shipping files](https://github.com/neuefische/ds-visualisation-group-work/actions/workflows/workflow-03.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-visualisation-group-work/actions/workflows/workflow-03.yml)
# Visualisation Group Work

In this repo you will find the assignment and data for our visualisation group work. Have a look at this [file](2-visualisation-task.md) for a detailed description of the task.

## Virtual Environment

In this repo you will find a [requirements.txt](requirements.txt) file. It contains all the libraries you will need for this exercise.

### Set up your Environment
Plotly in Jupter Lab requires node.you Check by run the following commands:
```sh
node -v
```
 If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 

`Step_1:` Update Homebrew and install Node by following commands:
```sh
brew update
brew install node
```

`Step_2:` Install the virtual environment and the required packages by following commands:

```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
### **`WindowsOS`** type the following commands :

`Step_1:` Update Chocolatey and install Node by following commands:
```sh
choco upgrade chocolatey
choco install nodejs
```

`Step_2:` Install the virtual environment and the required packages by following commands.

For `PowerShell` CLI :

```PowerShell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

For `Git-Bash` CLI :
```
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
```

**`Note:`**
If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:
```Bash
python.exe -m pip install --upgrade pip
```
