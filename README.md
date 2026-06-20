# Social Network Analysis with Python

A Python project that analyzes social network data stored in JSON format. This project demonstrates data cleaning and recommendation systems similar to those used by social media platforms.

## Features

### 1. Data Loading

Reads and parses JSON files into Python dictionaries for analysis.

### 2. Data Cleaning

* Removes users with missing names.
* Removes duplicate friend IDs.
* Removes duplicate page IDs.
* Generates cleaned JSON files.

### 3. People You May Know

Recommends users based on mutual friends, similar to Facebook's "People You May Know" feature.

### 4. Pages You Might Like

Recommends pages based on pages liked by users with similar interests.

---

## Project Structure

```
Project_1/
│
├── Project_1.ipynb              # Initial JSON loading and analysis
├── data_cleaning.ipynb          # Data cleaning operations
├── People_You_May_Know.ipynb    # Mutual-friend recommendation system
├── Pages_You_Might_Like.ipynb   # Page recommendation system
│
├── data.json
├── data2.json
├── data3.json
├── cleaned_data2.json
│
├── README.md
└── .gitignore
```

---

## Technologies Used

* Python
* Jupyter Notebook
* JSON
* Dictionaries
* Lists and Sets
* List Comprehensions

---

## Recommendation Algorithms

### People You May Know

Uses mutual friends to suggest new connections.

### Pages You Might Like

Uses shared interests and page likes to recommend new pages.

---

## Concepts Practiced

* File Handling
* JSON Parsing
* Dictionaries
* Sets
* List Comprehensions
* Sorting with Lambda Functions
* Recommendation Systems
* Data Cleaning
* Python Functions

---

## Future Improvements

* Convert notebooks into Python modules.
* Add graph visualizations using NetworkX.
* Build a GUI using Streamlit.
* Add friend recommendation weights.
* Export recommendations to CSV.

---

## Author

Syeda Mahnoor

Learning Data Science and Python through hands-on projects.
