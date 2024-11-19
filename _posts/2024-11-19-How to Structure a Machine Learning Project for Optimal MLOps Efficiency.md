---
layout: post
title: Sample blog post to learn markdown tips
subtitle: There's lots to learn!
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Bill Smith
---

{: .box-success}
This post will provide you a best practices to structure your ML project to facilitate MLOps success.

## Project Structure

```
├── api                 # api code to interact with model
│   └── models          # deployment ready models (copied from models/models)
├── config              # project level configurations
│   └── .env            # environment configurations, including settings for the project’s API (ex. dotenv)
├── deployment          # deployment related files
│   └── docker          # files for building and managing docker images
│   └── pipelines       # ci/cd pipelines (if your CI/CD system allows custom directory)
│   └── scripts         # supporting scripts for building and deploying
├── docs                # global documentation
├── infrastructure      # code for managing the project's infrastructure
├── reference           # Data dictionaries, manuals, and all other explanatory materials. 
├── reports             # Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures         # Generated graphics and figures to be used in reporting   
├── src                 # source code for model development
│   ├── __init__.py     # Makes src a Python module            
│   ├── data            # scripts for downloading, generating, collecting or processing data
│   │   ├── make_dataset.py
│   ├── datasets        # processed data (ex. medallion architecture)
│   │   ├── bronze      # raw, unprocessed data
│   │   ├── gold        # final processed data
│   │   └── silver      # intermediate processed data
│   ├── models          # deployment ready models
│   ├── notebooks       # jupyter notebooks
│   ├── scripts         # scripts to train, test models and then use the trained models to make predictions
│   │   ├── test_model.py       # scripts for running tests on models
│   │   └── train_model.py      # scripts for training models
│   │   └── predict_model.py    # scripts for prediction
│   └── utils           # utility scripts
├── ui                  # user interface for interacting with model api
├── .gitignore          # list of files and/or directories that are not stored in the repository
├── LICENSE             # Open-source license if one is chosen
├── Makefile            # file to automate common development tasks
└── README.md           # repository documentation
└── requirements.txt    # The requirements file for reproducing the analysis environment
└── setup.py            # Make this project pip installable with 'pip install -e'
```


