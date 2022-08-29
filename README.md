# Filmes Para Ti

O Filmes Pra Ti é um projeto para a disciplina MC855 A - Projeto em Sistemas de Computação, ministrada pela Prof. Dra. Juliana Freitag Borin e pelo PED Paulo Cesar Kussler.
Nosso grupo é composto por:
- Heigon Alafaire Soldera Pires RA:217638
- Luana Felipe de Barros      RA: 201705
- Lucas B.A. Farias RA:220650
- Marcela Medicina Ferreira RA: 183266
- Murilo de Lima Cruz RA: 138923
- Piethro Cesar de Andrade RA:223549

Neste repositório, deixaremos todo o projeto de Machine Learning. Para organização dele, decidimos utilizar o template do Cookiecutter, muito comum em projetos de Machine Learning e Data Science.

Organização do Projeto 
------------

    ├── LICENSE
    ├── Makefile           <- Makefile com comandos do tipo `make data` ou `make train`
    ├── README.md          <- O top-level README para os desenvolvedores usando este projeto.
    ├── data
    │   ├── processed      <- Dados finais, os que de fato serão usados no modelo.
    │   └── raw            <- Os dados originais, dados crus.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
