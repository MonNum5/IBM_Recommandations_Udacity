# Recommendation System for IBM
This repository contains the code for a recommendation system for IBM Watson Studio community data. It is project for my Udacity Data Science course.

## Project Motivation
Recommendation systems are a common to increase the interactions of e.g. users with a internet platform. In this repo I build and apply recommendation systems based on different strategies to make predictions for the users of the IBM Waston Studio platform. 

## File description

```bash
├── Readme.md
├── Recommendations_with_IBM.html
├── Recommendations_with_IBM.ipynb
├── content_similarty_matrix.p
├── data
│   ├── articles_community.csv
│   └── user-item-interactions.csv
├── project_tests.py
├── requirements.txt
├── top_10.p
├── top_20.p
├── top_5.p
└── user_item_matrix.p
```
## Code Steps

### I. Exploratory Data Analysis

### II. Rank Based Recommendations

### III. User-User Based Collaborative 

### IV. Content Based Recommendations 

### V. Matrix Factorization

### VI. Extras & Concluding

## Installation

```bash
pip install -r requirements.txt
```

## If you can want to run the file in a new enviroment:
- Make sure conda is installed (Best practice, set up with virtualenv is not tested)
- Open a terminal or a anaconda prompt
- If desired make new enviroment: conda create -n name_of_enviroment python
- Activate enviroment conda activate: conda create name_of_enviroment
- Install dependencies: pip install requirements.txt
- If the new enviroment / kernel is supposed to be used in Jupyter, install kernel:
```bash
    python -m ipykernel install --name name_of_enviroment
```
- Open your Jupyter Notebook it should work now