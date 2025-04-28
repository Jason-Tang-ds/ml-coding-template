# credit-card-default-tutorial

## Setup 

In this project, we will be using the credit card default dataset from the UCI Machine Learning Repository. 

To set up the project, we will be using the cookiecutter data science project template. 

```
cookiecutter https://github.com/cookiecutter/cookiecutter
```

You can start by cloning the repository and then running the command above to create a new project. 

```
git clone https://github.com/Jason-Tang-ds/ml-coding-template.git
```

And navigate to the project directory. 

```
cd ./ml-coding-template/credit-card-default-tutorial
```




We are using UV to manage the dependencies. 

If you don't have UV installed, you can install it by following the instructions [here](https://docs.astral.sh/uv/getting-started/installation/). 

Once you have UV installed, you can install the dependencies by running the following command. 

```
uv sync
```

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
<!-- │ -->
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jt-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         credit_card_default_tutorial and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── credit_card_default_tutorial   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes credit_card_default_tutorial a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

