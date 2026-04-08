# BMI-calculator
📖 Overview

This project is a GUI-based BMI (Body Mass Index) tracking system built using Python. It allows users to calculate BMI, store multiple records, and visualize health data using graphs.

The system integrates user input, database storage, and data analysis to provide a simple yet effective health monitoring tool.
🚀 Features
Calculate BMI using height and weight
Store multiple user records
View historical BMI data
Visualize Height vs Weight using scatter plot
Analyze BMI trend over time using line graph
🛠 Technologies Used
/Python
/Tkinter
/SQLite
/Matplotlib
🧠 How It Works
1. Database Setup
/Uses SQLite database (bmi.db)
/Stores user details:
>Name
>Height
>weight
>BMI
>date
2. BMI Calculation

The BMI is calculated using the formula:BMI = weight / (height × height)
>Takes input from GUI
>Displays result instantly
>Saves data into database
3. Data Storage
>Each calculation is stored in the database
>Supports multiple users and multiple entries
4. History Viewing
Displays all stored records
Shows:
>Name
>Height
>Weight
>BMI
>Date
5. Data Visualization

Height vs Weight Graph

>Scatter plot
>Shows relationship between height and weight

BMI Trend Graph

>Line chart
>Displays BMI changes over time
▶️ How to Run
>Install Python
>Install required library:pip install matplotlib
>Run the program:python bmi_calc.py
# SMART BMI TRACKER

Weight
BMI
Date
