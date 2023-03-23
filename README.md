# hello_ds

This is a test repository for the Data Science tutorial.

See <https://code.visualstudio.com/docs/datascience/data-science-tutorial>

## Setup

```bash
pyenv virtualenv 3.10.8 jupyter    # create virtualenv named "jupyter"
pyenv local jupyter                # set local python version
pyenv activate jupyter             # activate virtualenv
pip install pandas jupyter seaborn scikit-learn keras tensorflow   # install packages
```

## Run

Open the folder in VSCode and run the command `Jupyter: Create New Blank Notebook` from the command palette.
Select the kernel from the virtual environment created above.
