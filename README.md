# 📊 High-Flying project

Flight-high project is a data base for clients and their activities, using EDA to explore the data base and its behavior is analyzed to answer questions and create data visualizations.

This project is designed to demonstrate understanding and skills in Python for `Exploratory Data Analysis (EDA)`, `Handling Missing Data`, and `Data Visualization` using the `matplotlib` and `seaborn` libraries. It utilizes CSV files: `Customer Flight Analysis.csv` and `Customer Loyalty History.csv`, which contain data simulating customer behavior within an airline loyalty program.

---

## Phase 1: Exploratory Data Analysis
In this phase, the CSV files are processed independently to perform data exploration and cleaning. This is done using the pandas and numpy libraries for reading dataframes, and the seaborn and matplotlib libraries for generating initial visualizations.

---

## Phase 2: DataFrame union
In this phase, Pandas is used to combine the cleaned dataframes into a single dataframe that contains both flight information and customer information.

---

## Phase 3: Data Visualization
Using Python's data visualization libraries (Seaborn and Matplotlib), questions about customers are answered, and the conclusions are based on solid data.

---

## Phase 4: Hypothesis evaluation
Different hypothesis testing methods are used to determine if there is a difference between two groups in the dataset.

---

## 💡 Technologies Used

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) 

---

## 📁 Repository structure

```
airline_analysis_mar
│
├── README.md
│
├── data/
│   ├── Customer Flight Activity.csv
│   ├── Customer Loyalty History.csv
│   ├── customer_flight_activity_clean.csv
│   ├── customer_loyalty_activity_complete.csv
│   └── customer_loyalty_history_clean.csv
│
├── notebook/
│   └── airline_analysis_mar.ipynb
│
└── screenshots/
    ├── 01.01evolution_flights_month_lineplot.png
    ├── 01.02evolution_flights_month_barplot.png
    ├── 02.01relation_distance_points_scatterplot.png
    ├── 02.02relation_distance_points_scatter.png
    ├── 03.01relationship_customer_province.png
    ├── 04.01relationship_salaty_education_barplot.png
    ├── 05.01relationship_loyaltycard_customer_barplot.png
    ├── 05.02relationship_loyaltycard_customer_countplot.png
    ├── 05.03relationship_loyaltycard_customer_pie.png
    ├── 06.01relationship_gender_maritalstatus_barplot.png
    ├── 06.02relationship_gender_maritalstatus_countplot.png
    ├── 07.01representation_hypothesis_barplot.png
    ├── 07.02results_hypothesis.png
    ├── extra_01_df_flight_numeric.png
    ├── extra_02_df_flight_numeric.png
    ├── extra_03_df_flight_numeric.png
    ├── extra_04_df_flight_numeric.png
    ├── extra_05_df_flight_numeric.png
    ├── extra_06_df_flight_numeric.png
    ├── extra_07_df_flight_numeric.png
    ├── extra_08_df_flight_numeric.png
    ├── extra_09_df_loyalty_numeric.png
    ├── extra_10_df_loyalty_numeric.png
    └── extra_11_df_loyalty_numeric.png
```
---

## 📝 Instructions for use

1. Clone the repository.
2. In the folder `notebook` run the main file using Visual Studio Code: `airline_analysis_mar`.
3. Follow the instructions in the file to run the code and to extract the data from the CSV files, perform the EDA and create a new CSV files with the final data.

---

## ✍️ Author

- Mar Pastor

---

## ✅ Project status

Completed

---

## 📷 Screenshots

In the folder `screenshots` the graphs showing the results of the database queries are located here.

- Example of a barplot:

![Example_01](https://github.com/MarPastor/airline_analysis_Mar/blob/main/screenshots/01.02evolution_flights_month_barplot.png)

- Example of pie graphic

![Example_02](https://github.com/MarPastor/airline_analysis_Mar/blob/main/screenshots/05.03relationship_loyaltycard_customer_pie.png)

- Example of multiple bar charts:

![Example_03](https://github.com/MarPastor/airline_analysis_Mar/blob/main/screenshots/06.02relationship_gender_maritalstatus_countplot.png)

- Example of scatterplot:

![Example_04](https://github.com/MarPastor/airline_analysis_Mar/blob/main/screenshots/02.01relation_distance_points_scatterplot.png)


---

## 📦 Data folder

In the folder [data](https://github.com/MarPastor/airline_analysis_Mar/tree/main/data) the following files are located:

- `Customer Flight Activity.csv` which contains information about customers' flight activity.

- `Customer Loyalty History.csv` which provides a detailed customer profile and information about their membership in the loyalty program.

---