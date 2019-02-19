# jupyter-exec
Jupyter Subcommand to execute notebooks

## Installation
```
pip install jupyter-exec
```

## Usage
```
jupyter exec NOTEBOOK.ipynb
```

Equivalent to:
```
python <(jupyter nbconvert --to script --stdout NOTEBOOK.ipynb)
```
