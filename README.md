
# Drugs Classifier

  

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

* [Technologies Used](#technologies-used)

* [Results of the Project](#results-of-the-project)

*  [Installation](#installation)

*  [License](#license)

  
  

## About

> Using the dataset to  create a `machine learning` model that can predict  which `drugs` should be given to a patient taking some input data. 

>Machine Learning techniques like `Cross Validation` and `Parameter Tuning` are done to make the model better. Also viewing at `Classification Matrix` to look at scores of `recall`, `precision` and `f1-score` to verify whether the model is works fine or not.

## Technologies Used
  
> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

>  `Numpy` and `Pandas` are used to work with the data.

> `Matplotlib` and `Seaborn` is used to visualise the results.

> `Sciki-learn` is used for data preprocessing, creating machine learning model and evaluating it.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.

## Results of the Project

#### Count Plot

![Count](https://github.com/AkashSDas/Drugs-Classifier/blob/master/project-results-images/count.png)

#### Cross Validation Scores

![Cross Validation Scores](https://github.com/AkashSDas/Drugs-Classifier/blob/master/project-results-images/cross.png)


####  Metrics Scores

![Metrics Scores](https://github.com/AkashSDas/Drugs-Classifier/blob/master/project-results-images/metrics-scores.png)

#### Confusion Matrix

```python
		precision    recall  f1-score   support

       drugA       1.00      1.00      1.00         7
       drugB       1.00      1.00      1.00         5
       drugC       1.00      1.00      1.00         5
       drugX       1.00      0.95      0.98        21
       drugY       0.96      1.00      0.98        22

    accuracy                           0.98        60
   macro avg       0.99      0.99      0.99        60
weighted avg       0.98      0.98      0.98        60
```

## Installation

  

It is highly **recommended** to use **`virtual environment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'Drugs-Classifier'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash
git clone https://github.com/AkashSDas/Drugs-Classifier
```

  

- Start by installing **`pipenv`** if you don't have it

```bash
pip install pipenv
```

  

- Once installed, access the venv folder inside the project folder

```bash
cd  'Drugs-Classifier'/venv/
```

  

- Create the virtual environment

```bash
pipenv install
```

The **Pipfile** of the project must be for creating replicating project's virtual environment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash
pipenv shell
```
- dataset, jupyter notebook and model are in `'Drugs-Classifier'/venv/src` folder.
```bash
cd src/
```

  

- To start/view the jupyter notebook

```bash
jupyter noterbook
```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.
  

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
