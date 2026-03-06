# Movie Preference Classification with k-Nearest Neighbors (k-NN)

## Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-Scientific%20Computing-8CAAE6?style=for-the-badge&logo=scipy)


## Overview
This project is an academic practice focused on introducing **supervised machine learning** concepts. The main goal is to implement a classifier based on the **k-Nearest Neighbors (k-NN)** technique (more specifically, a **radius-based neighbor classifier**) capable of categorizing users as **"Comedy"** or **"Drama"** based on the proximity of points in a **two-dimensional space**.

The project demonstrates the creation of **synthetic datasets**, the calculation of **Euclidean distances**, and the **visualization of spatial data**.

---

## Objectives

- Implement the classification logic using **Euclidean distance calculations**.
- Manipulate vectors using the **NumPy** library for efficient numerical computation.
- Visualize **data clusters** using **Matplotlib** to better understand class distribution and separation.
- Create **reusable functions** to test different user instances and adjust parameters such as the **neighborhood radius**.

---

## Key Features

### Synthetic Data Generation
Random points are generated to represent **user preferences for movie genres**.

### Euclidean Distance Calculation
Implementation of a function to measure similarity between the **target user (yellow point)** and the **reference clusters**.

### Dynamic Classification
A function `classification(radius, newUser)` processes the input and returns the user's predicted preference based on neighbors found within the defined radius.

### Data Visualization
Graphical plots display the position of users relative to the **Comedy cluster (blue)** and the **Drama cluster (red)**.
