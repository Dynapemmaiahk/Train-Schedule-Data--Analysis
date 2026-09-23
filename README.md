### SYSSLAN IT SOLUTIONS
# TRAIN SCHEDULE ANALYSIS PROJECT

---

## 📌 Project Description

This project analyzes train schedule data and provides an interactive train route enquiry system.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## ✨ Main Features

- Train schedule data analysis
- Data cleaning and transformation
- Statistical analysis
- Pivot tables and crosstabs
- Data visualizations
- Interactive source and destination station search
- Direct train identification
- Departure and arrival time display
- Estimated journey duration
- Station name suggestions for invalid input

---

## 🚆 Train Enquiry System

The final system allows the user to:

1. Enter a source station.
2. Enter a destination station.
3. Find available direct trains between the stations.
4. Display departure time from the source.
5. Display arrival time at the destination.
6. Calculate estimated journey duration.
7. Suggest station names when an invalid station is entered.
8. Search for another route or exit the system.

---

## 📊 Visualizations

The project includes charts for:

- **Top 10 High-Traffic Stations**
- **Distinct Trains vs Total Stop Records**
- **Route Type Distribution at Top Stations**
- **Average Journey Duration by Route Type**

---

## 📁 Project Structure

- `Project.ipynb` — Main Jupyter Notebook containing the complete analysis and Train Enquiry System.
- `train_schedule_cleaned.csv` — Cleaned train schedule dataset.
- `train_schedule.csv` — Original train schedule dataset.
- `train_duration_analysis.xlsx` — Train duration analysis results.
- `Dataset1.xlsx` — Supporting dataset.
- `charts/` — Contains generated visualization charts.
- `README.txt` — Project documentation.

---

## ⚙️ Requirements

- Python 3.x
- Jupyter Notebook / JupyterLab
- Pandas
- Matplotlib
- Seaborn

---

## ▶️ How to Run

1. Open `Project.ipynb` using Jupyter Notebook or JupyterLab.
2. Run the notebook cells from top to bottom.
3. Run the final **Train Enquiry System** section.
4. Enter a source station.
5. Enter a destination station.
6. View the available direct trains and estimated journey duration.

---

## 📝 Notes

The Train Enquiry System uses the cleaned train schedule dataset.

Station names are normalized to improve search accuracy.

Only trains travelling in the correct source-to-destination direction are considered direct trains.