# Filmes Para Ti

O Filmes Pra Ti é um projeto para a disciplina MC855 A - Projeto em Sistemas de Computação, ministrada pela Prof. Dra. Juliana Freitag Borin e pelo PED Paulo Cesar Kussler.
Nosso grupo é composto por:
- Heigon Alafaire Soldera Pires RA: 217638
- Ian Loron de Almeida RA: 198933
- Luana Felipe de Barros      RA: 201705
- Lucas B.A. Farias RA:220650
- Marcela Medicina Ferreira RA: 183266
- Murilo de Lima Cruz RA: 138923
- Piethro Cesar de Andrade RA: 223549

Neste repositório, deixaremos todo o projeto de Machine Learning. Para organização dele, decidimos utilizar o template do <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">Cookiecutter</a>, muito comum em projetos de Machine Learning e Data Science.

Organização do Projeto 
------------

    ├── LICENSE
    ├── Makefile           <- Makefile com comandos do tipo `make data` ou `make train`
    ├── README.md          <- O top-level README para os desenvolvedores usando este projeto.
    ├── data
    │   ├── processed      <- Dados finais, os que de fato serão usados no modelo.
    │   └── raw            <- Os dados originais, dados crus.
    │
    ├── docs               <- Um projeto Sphinx; veja sphinx-doc.org para detalhes.
    │
    ├── models             <- Modelos treinados e serializados, predições do modelo, ou resumos do modelo.
    │
    ├── notebooks          <- Jupyter notebooks. O convenção de nomes é um número (para ordem), 
    │                         iniciais do nome da pessoa criou, e um `-` para delimitação da descrição.
    │                         ex: `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Dicionários de dados, manuais, e outros materiais explanatórios.
    │
    ├── reports            <- Análises geradas, como HTML, PDF, LaTeX, etc.
    │   └── figures        <- Figuras e gráficos usados nos reports.
    │
    ├── requirements.txt   <- O arquivo de requerimentos para reproduzir o projeto,
    │                         ele é gerado com: `pip freeze > requirements.txt`
    │
    ├── setup.py           <- faz o projeto ser instalado pelo pip (pip install -e .) e daí, o src pode ser importado.
    ├── src                <- Código fonte do projeto.
    │   ├── __init__.py    <- Cria src um módulo python.
    │   │
    │   ├── data           <- Scripts para baixar ou gerar dados.
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts tornar dados crus em features para o modelo.
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts para trainar os modelos e fazer previsões.
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts para visualizar e explorar resultados.
    │       └── visualize.py
    │
    └── tox.ini            <- Arquivo tox com configurações para rodar o tox; veja tox.readthedocs.io


--------
