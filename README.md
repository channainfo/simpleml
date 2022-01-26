# SIMPLEML
Machine Learning ( ML ) simple

## Development tool
- anaconda navigator

## Conda command

```
# conda info
> conda info

# manage conda env
# conda create -n [env_name]
# simpleml as env_name
> conda create -n simpleml
> conda env list

# conda activate [env_name]
> conda activate simpleml

# conda deactivate [env_name]
> conda deactivate simpleml

# installed packages
> conda list -e > requirements.txt

```
from the above example we create a new env called **simpleml**.



## VSCode and Jupyter Notebook
We use VSCode python and jupyter notebook debugger extensively, VSCode has a good support for Jupyter notebook come with anaconda.
To make sure you choose the right anaconda env, in vscode

### For Python file extension (.py)
1. open vscode command palette ( CMD + SHIFT + P)
2. Type **Python:**
3. Choose **Select Interpreter** from the menu
4. Choose your env name **simpleml** from the list

### For Jupyter file extension (.ipynb) file extension
1. open vscode command palette ( CMD + SHIFT + P)
2. Type **Jupyter:**
3. Choose **Select Interpreter..** from the menu
4. Choose your env name **simpleml** from the list 