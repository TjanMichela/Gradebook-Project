# Pandas Project: Make a Gradebook With Pandas

The code in this folder is used to generate and process the data for the tutorial [Pandas Project: Make a Gradebook With Pandas_](https://realpython.com/pandas-project-gradebook).

## `generate_data.py`

The script `generate_data.py` uses the [Faker](https://faker.readthedocs.io/en/master/) library to generate fake student names and NumPy to generate scores for homework, exams, and quizzes. The data are stored as CSV files in the `data` folder. With the seed that is set in the script, the data used in the article can be reproduced. To try out new data, change the seed for the NumPy random number generator.

## Jupyter Notebook

In the article, I created a Jupyter Notebook called `gradebook.ipynb`. 

## Installing Dependencies

There are two `requirements.txt` files in this repository. The `data/requirements.txt` contains the dependencies for the `generate_data.py` script. The `requirements.txt` file in the root folder contains the dependencies for the `gradebook.py` script.
