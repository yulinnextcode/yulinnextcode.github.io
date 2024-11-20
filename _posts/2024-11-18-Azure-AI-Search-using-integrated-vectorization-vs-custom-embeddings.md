---
layout: post
title: Azure AI Search using integrated vectorization vs custom embeddings
subtitle: Azure AI Search default embeddings
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Gen AI]
comments: true
mathjax: true
author: Yulin Zhao
---

{: .box-success}
This article is to compare using Azure AI Search with integrated vectorization vs. with custom embeddings. The results will be displayed.

## Azure AI Searching using integrated data chunking and embedding

### Setup project folder
You can refer to [How to Structure a Machine Learning Project for Optimal MLOps Efficiency](https://github.com/yulinnextcode/yulinnextcode.github.io/blob/master/_posts/2024-11-19-How-to-Structure-a-Machine-Learning-Project-for-Optimal-MLOps-Efficiency.md) to know more about MLOps project structure.


### Create virtual environment
```
python -m venv GenAI_env      # create virtual environment
cd GenAI_env\Scriptsactivate  # activate 
```

### Install virtual environments
```
pip install -r requirements.txt
```

### Setup Jupyter notebook
Ctrl + Shift + P
Input Interpreter
Create or Select expected virtual environment
Click the "Select Kernel" button on the top right and select your virtual environment

```
from ragas.testset.generator import TestsetGenerator
from ragas.testset.evolutions import simple, reasoning, multi_context
# Above codes will cause
# ModuleNotFoundError: No module named 'ragas.testset.generator'
# ModuleNotFoundError: No module named 'ragas.testset.evolutions'
# This is because latest ragas version does not have generator.py under testset folder. Change ragas version to 0.1.1 and it will work
```


### 
