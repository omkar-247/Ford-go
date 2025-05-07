# 🚲 Ford GoBike Sharing Project

An Exploratory Data Analysis (EDA) and regression-based project focused on understanding usage patterns, user behavior, and system performance in the Ford GoBike bike-sharing network in the San Francisco Bay Area.

## 📁 Project Type
- EDA
- Regression
- Individual Project

## 👤 Author
Omkar Kummarikuntla

## 🧾 Project Summary

The **Ford GoBike system** is a public bike-sharing network serving the San Francisco Bay Area. This project analyzes its trip data to:
- Understand user demographics and usage trends.
- Explore the relationship between trip duration and user types.
- Apply regression techniques to predict ride durations.
- Identify peak usage times and route preferences.

The goal is to provide insights to improve service efficiency and user experience.

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib / Seaborn 📊
- Scikit-learn ⚙️
- Jupyter Notebook 📓

## 📂 Dataset

The dataset includes:
- Start and end times of trips
- Station locations
- User type (subscriber/customer)
- Gender and birth year
- Trip duration

> **Note:** Dataset not provided in this repo for licensing reasons.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ford-gobike-analysis.git
   cd ford-gobike-analysis
## Installation & Execution

### Install Required Dependencies

bash
pip install -r requirements.txt

### Launch the Notebook

bash
jupyter notebook "Ford_goBike_Sharing_Project.ipynb"

## 📌 Key Insights

- Subscribers account for the majority of trips, mostly during weekdays and rush hours.
- Customers tend to ride more on weekends and for longer durations.
- Age and gender significantly influence trip patterns.
- A regression model was built to predict trip durations based on user and trip features.
