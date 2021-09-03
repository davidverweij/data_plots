# data_plots
A collection of Jupyter Notebooks to re-use across data visualisation tasks

## Setup

[Poetry](https://python-poetry.org/) is used for dependency management, so please install on your local machine. Also ensure you have Python 3.0 installed; using [pyenv](https://github.com/pyenv/pyenv) is recommended. 

```shell
poetry install
```

Enter a `poetry shell` before running `jupyter notebook` **to ensure it has access to the dependencies in the virtual env.**
```shell
poetry shell
jupyter notebook
```

All notebooks are in the `/notebooks` folder.