
# Flight Fare Prediction




## Table of contents
- [Demo](#Demo)
- [Overview](#Overview)
- [Installation](#Installation)
- [Deployment](#Deployment)
- [Directory Tree](#DirectoryTree)
- [Technologies Used](#TechnologiesUsed)
- [Future Scope ](#FutureScope)

## Demo

![](./Screenshot%202024-09-04%20190147.png)



## Overview

The Flight Fare Prediction project is a machine learning-based web application designed to predict flight ticket prices based on user-provided inputs. By leveraging historical flight data, the application aims to help travelers make informed decisions about their travel plans by providing accurate fare estimates.
## Installation

The Code is written in Python 3.12.4.If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

```bash
  pip install -r requirements.txt
```
    
## Deployment 
To run the Flight Fare Prediction application locally, follow these steps:
Prerequisites

1)Python 3.x: Ensure Python is installed on your machine. You can check the version by running:
```bash
python --version
```
2)Pip: Make sure you have pip installed to manage dependencies. Install pip by running:
```bash
python -m ensurepip --upgrade

```
Installation Steps

1)Clone the Repository:
```bash
git clone https://github.com/bhar44/flight_fare2.git


```
2)Install Dependencies: Install the required Python libraries using the requirements.txt file:
```bash
pip install -r requirements.txt



```
3)Run the Application: Once the dependencies are installed, you can start the Flask app by running:
```bash
python app.py




```
4)Access the Application: Open your browser and go to http://127.0.0.1:5000/ to access the Flight Fare Prediction web application.

## Directory Tree

```bash
  ├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_rf.pkl
├── requirements.txt
```
## Technologies Used
1)Python: The primary programming language used for developing the backend and machine learning model.

2)Flask: A lightweight web framework for Python, used to create the web application and handle HTTP requests.

3)Scikit-learn: A machine learning library in Python, used for building and training the predictive model.

4)Pandas: A powerful data manipulation library in Python, used for data preprocessing and feature engineering.

5)NumPy: A fundamental package for numerical computations in Python, used for handling arrays and matrices in the model.

6)HTML5 & CSS3: Used for structuring and styling the web interface.

7)Git: Version control system used to track changes in the codebase and manage collaboration.

## Future Scope
1)Use multiple Algorithms

2)Optimize Flask app.py

3)Front-End
