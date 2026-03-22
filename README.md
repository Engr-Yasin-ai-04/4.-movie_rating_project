# 🎬 Movie Rating Prediction - Collaborative Filtering Project

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.2-green.svg)](https://www.djangoproject.com/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A complete Machine Learning web application that predicts movie ratings using Collaborative Filtering and Regression models. Built with Django and deployed with a beautiful interactive interface.

---

## 📸 Project Screenshots

### 🖥️ Main GUI Interface
The main dashboard where users can upload movie ratings data and view predictions.

![GUI Interface](1_Output_GUI.JPG)

### 📊 Prediction Results
Real-time movie rating predictions with model performance metrics.

![Prediction Result](2_Output_Program.JPG)

### 📈 Model Performance Analysis
Detailed analysis of model accuracy and performance metrics.

![Model Performance](2_Output_Program_02.JPG)

### 🎯 Final Prediction Output
Complete prediction results with user and movie information.

![Final Output](2_Output_Program_Last.JPG)

---

## 🏗️ Project Structure
Complete project structure for better understanding of the code organization.

![Project Structure](Program_Structure_Image.JPG)

---

## 📊 Project Overview

This project uses movie rating datasets to predict how a user might rate a movie they haven't seen yet using:

- **Collaborative Filtering**: Ridge Regression based approach
- **Regression Models**: Random Forest with engineered features
- **User-Item Matrix**: Sparse matrix factorization
- **Real-time Predictions**: Instant rating predictions

The application provides an interactive web interface where users can input user ID and movie ID to get predicted ratings.

---

## 🎯 Features

- ✅ **Data Upload**: Support for CSV files with ratings data
- ✅ **Multiple Models**: Collaborative Filtering & Regression
- ✅ **User-Item Encoding**: Label encoding for users and movies
- ✅ **Feature Engineering**: User averages, movie averages, rating counts
- ✅ **Model Evaluation**: MSE, RMSE, R² Score metrics
- ✅ **Real-time Predictions**: Instant rating predictions
- ✅ **Dataset Statistics**: Total ratings, unique users, unique movies
- ✅ **Responsive Design**: Works on all devices

---


---

## 🚀 Installation & Setup

### Prerequisites

- Python 3.9 or higher
- pip package manager

### Step-by-Step Installation

1. **Download the Project**
   - Download [4. movie_rating_project.rar](4.%20movie_rating_project.rar)
   - Extract the files to your desired location

2. **Create a virtual environment**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
