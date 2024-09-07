   ## CLICK NA IMAGEM ABAIXO PARA AMPLIAR E CONFERIR AS ETAPAS DO PROJETO, MUITO INTERESSANTE!
   
![DEMANDA HOR2](https://github.com/user-attachments/assets/d19c852f-056c-4f07-9e44-d2907274031b)



## Análise de Classificação de Churn de clientes da empresa Telco Comunicações.

A rotatividade de clientes no setor de telecomunicações, ou perda de clientes para concorrentes, é um problema crítico. 
Prever isso com antecedência permite implementar estratégias de retenção, e uma redução de 1% na rotatividade pode aumentar significativamente os lucros.

## Objetivo Pessoal
Esse projeto me proporciona experiência prática em ciência de dados, incluindo a manipulação de grandes volumes de dados, aplicação de técnicas de aprendizado de máquina, e implementação de estratégias de retenção de clientes, preparando-me para atuar em diversos setores e segmentos de negócios.

## O Problema

O problema a ser solucionado é identificar clientes propensos a sair e tomar ações preventivas antes que eles partam. 
	
Quando um cliente cancela o serviço a empresa não perdi somente o lucro que ele ofereci, mais deixa o cliente ir levando consigo a insatisfação e assim propagando para outros possiveis futuros clientes


## Demanda da Análise

A análise de churn envolverá:
 * Analisar as correlações entre os cliente", "um produto ou serviço" e "a probabilidade de abandono";

 * Realizar análise de dados e engenharia de recursos;

 * Desenvolver um modelo de aprendizado de máquina para prever quais clientes deixarão a empresa.


### O Conjunto de Dados

O conjunto de dados Telco Customer Churn da Kaggle foi utilizado, contendo 21 colunas e 7.043 linhas com informações como customerID, sexo, serviço telefônico e de Internet. Analiso essas colunas para identificar variáveis independentes (X) e dependentes.

![CHURN](https://github.com/user-attachments/assets/1a483c50-5a98-4548-8d05-8285716bb708)

## Abaixo, a estrutura padrão das pastas de todo o projeto
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
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
