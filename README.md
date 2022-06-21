# My personal Data Science Cookie Cutter

## What is this?

This repository is a custom template for a data science project. I took inspiration from [data-science-template](https://github.com/khuyentran1401/data-science-template) and [cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science).

## How to use this project

Install Cookiecutter:

```bash

pip install cookiecutter

```

Create a project based on the template:

```bash

cookiecutter https://github.com/demian-arenas/data_cookiecutter

```

## Project Structure

```bash
.
├── data
│   ├── final                       # data after training the model
│   ├── processed                   # data after processing
│   └── raw                         # raw data
├── models                          # store models
├── notebooks                       # all notebooks
│   ├── eda                         # exploratory data analysis
│   ├── evaluation                  # evaluate models and hypothesis
│   └── models                      # model building and training
├── docs                            # documentation for your project
├── .flake8                         # configuration for flake8 - a Python formatter tool
├── .gitignore                      # ignore files that cannot commit to Git
├── Makefile                        # store useful commands to set up the environment
├── .pre-commit-config.yaml         # configurations for pre-commit
├── README.md                       # describe your project
└── src                             # Source code for use in this project.
    ├── __init__.py                 # Makes src a Python module
    ├── data                        # Scripts to download or generate data
    ├── features                    # Scripts to turn raw data into features for modeling
    ├── models                      # Scripts to train models and then use trained models to make predictions
    │   ├── predict_model.py
    │   └── train_model.py
    └── visualization               # Scripts to create exploratory and results oriented visualizations
         └── visualize.py
```