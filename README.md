# data_science_template

This template aims to help the user to implement a systematic data science process. Including data preprocessing, data exploratory analysis (EDA), model training, model evaluation
The original template is from : [Cookiecutter Data Science](https://cookiecutter-data-science.drivendata.org/)

Each directory/file functions are describe as follow:

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
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes src a Python module
    │
    ├── ML_Pipeline                
    │   ├── __init__.py
    │   ├── make_dataset.py     <- Scripts to download, generate and reformat raw data
    │   ├── eda.py              <- Data exploratory analysis, including visualization, hypothesis testing
    │   ├── preprocess.py       <- Preprocess data, e.g., missing values, outliers, etc.
    │   ├── features.py         <- Feature extraction         
    │   ├── train.py            <- Code to train models
    │   └── predict.py          <- Code to run model inference with trained models 
    │
    └── engine.py               <- The backbone of the ml pipeline