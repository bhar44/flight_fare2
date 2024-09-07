
# Flight Fare Prediction




## Table of contents
- [Demo](#Demo)
- [Overview](#Overview)
- [Installation](#Installation)
- [Deployement](#Deployement)
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
    
## Deployement 
#!/bin/bash

# Step 1: Clone the repository
echo "Cloning the repository..."
git clone https://github.com/bhar44/flight_fare2.git
cd flight_fare2 || { echo "Repository not found."; exit 1; }

# Step 2: Check for Python and Pip installation
echo "Checking Python version..."
python --version || { echo "Python is not installed. Please install Python."; exit 1; }

echo "Checking for pip installation..."
python -m ensurepip --upgrade || { echo "Pip is not installed. Installing pip..."; python -m ensurepip --upgrade; }

# Step 3: Install the required dependencies
echo "Installing dependencies..."
pip install -r requirements.txt || { echo "Failed to install dependencies."; exit 1; }

# Step 4: Run the application
echo "Starting the Flask application..."
python app.py || { echo "Failed to start the application."; exit 1; }

# Step 5: Provide the local access link
echo "Your application is running at http://127.0.0.1:5000/"

 
 


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
