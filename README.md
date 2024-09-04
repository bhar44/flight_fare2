
# Flight Fare Prediction




## Table of contents
- [Demo](#Demo)
- [Overview](#Overview)
- [Installation](#Installation)
- [Deployement on Azure](#DeployementonAzure)
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
    
## Deployement on Azure
Login or signup in order to [portal.azure](https://azure.microsoft.com/en-in/free/search/?ef_id=_k_Cj0KCQjwiuC2BhDSARIsALOVfBI6rvkmL04cSG3BiMFdSG1ny_k_0mEY_1Ccz0Wo4Ly5l58qt4_rYtAaAtfwEALw_wcB_k_&OCID=AIDcmmf1elj9v5_SEM__k_Cj0KCQjwiuC2BhDSARIsALOVfBI6rvkmL04cSG3BiMFdSG1ny_k_0mEY_1Ccz0Wo4Ly5l58qt4_rYtAaAtfwEALw_wcB_k_&gad_source=1&gclid=Cj0KCQjwiuC2BhDSARIsALOVfBI6rvkmL04cSG3BiMFdSG1ny_k_0mEY_1Ccz0Wo4Ly5l58qt4_rYtAaAtfwEALw_wcB)
 to create  a web app. Create a resource, select web app option and connect your github repository to deploy this project.

 ![](./azure/Screenshot%202024-09-04%20193506.png)
 ![](./azure/Screenshot%202024-09-04%20193518.png)

 
 


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

7)Microsoft Azure: A cloud computing platform used for deploying the web application, ensuring scalability and global accessibility.

8)Git: Version control system used to track changes in the codebase and manage collaboration.

## Future Scope
1)Use multiple Algorithms

2)Optimize Flask app.py

3)Front-End
