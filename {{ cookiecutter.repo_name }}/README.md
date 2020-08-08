{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

├── LICENSE
├── Makefile                    <- Makefile with commands like `make data` or `make train`       
├── README.md                   <- The top-level README for this project.
├── data
│   ├── external                <- Data from third party sources.
│   ├── interim                 <- Intermediate data that has been transformed.
│   ├── processed               <- The final, canonical data sets for modeling.
│   └── raw                     <- The original, immutable data.
|
├── docs                        <- A default Sphinx project; see sphinx-doc.org for details
│
├── references                  <- Data dictionaries, manuals, and all other explanatory 
├── requirements.txt            <- The requirements file for reproducing the analysis
├── results                     <- Generated analysis in consumable format
│   └── figures                 <- Generated graphics and figures to be used in reporting                       
├── setup.py                    <- makes project pip installable (pip install -e .) so src can be imported
├── src                         <- Source code for use in this project.
│   ├── __init__.py             <- Makes src a Python module
│   ├── build_features.py       <- Turn raw data into processed featrues.
│   ├── make_dataset.py         <- Download/Sync/generate data (sample data)
│   ├── predict_model.py        <- Make predictions on processed input
│   ├── train_model.py          <- Train/save model
│   └── analysis.py             <- Exploratory/Main script for analysis projects
└── test_environment.py


--------

