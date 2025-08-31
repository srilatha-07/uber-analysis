# 🚖 Uber Ride Analysis

## 📌 Project Overview

This project analyzes Uber ride booking data to uncover patterns in ride
behavior, customer preferences, and factors affecting bookings.\
We also built machine learning models (Logistic Regression & Random
Forest) to predict ride outcomes and compared their performance.

The project includes:\
- 📊 **Data Analysis & Visualization** in Jupyter Notebook\
- 🤖 **Machine Learning Models** for classification\
- 🎤 **Presentation** summarizing insights

------------------------------------------------------------------------

## 📂 Folder Structure

    Uber-Analysis-Project/
    │
    ├── data/                 # Dataset
    │   └── ncr_ride_bookings.xlsx
    │
    ├── notebooks/            # Jupyter Notebook
    │   └── Uber_Analysis.ipynb
    │
    ├── presentation/         # PPT & visuals
    │   └── Uber_Analysis_Presentation.pptx
    │
    └── README.md             # Project Documentation

------------------------------------------------------------------------

## ⚙️ Tools & Technologies

-   **Python (Pandas, Matplotlib, Seaborn, Scikit-learn)**\
-   **Jupyter Notebook**\
-   **Excel** (Dataset preprocessing)

------------------------------------------------------------------------

## 🔍 Exploratory Data Analysis (EDA)

-   Distribution of rides by **status (completed vs canceled)**\
-   Ride trends across **hours of the day**\
-   Impact of **payment method** and **vehicle type**\
-   Relationship between **ride distance** and **booking value**

------------------------------------------------------------------------

## 🤖 Machine Learning Models

-   **Logistic Regression**
    -   Accuracy: \~53%\
    -   Struggled to classify canceled vs completed rides
-   **Random Forest Classifier**
    -   Accuracy: \~94%\
    -   Top features: **Ride Distance, Payment Method, Booking Value**

------------------------------------------------------------------------

## 📌 Key Insights

-   Random Forest significantly outperformed Logistic Regression.\
-   **Ride Distance** and **Payment Method** are the strongest
    predictors of ride outcome.\
-   Most cancellations happen in **short rides**.
