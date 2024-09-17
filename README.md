# ECE2112---Experiment-4

# Data Wrangling and Visualization Project

## Overview

This project focuses on using data wrangling and data visualization to analyze and interpret a dataset related to college students' performance in different tracks. The goal is to create data frames and visualizations to understand how factors such as track, gender, and hometown contribute to students' average grades.

## Project Structure

The project is written in a Jupyter Notebook and includes the following components:

### **1. Data Wrangling**
- **Objective**: To create specific data frames based on filtering and manipulation rules.
- **Data Frames**:
  - **`Instru`**: A data frame that includes students in the Instrumentation track, from Luzon, and with an Electronics score greater than 70.
    - Columns: `Name`, `GEAS`, `Electronics > 70`
  - **`Mindy`**: A data frame that includes female students from Mindanao with an average score greater than or equal to 55.
    - Columns: `Name`, `Track`, `Electronics`, `Average >= 55`

### **2. Data Visualization**
- **Objective**: To analyze the relationships between students' average grades and various features like track, gender, and hometown through visualization.
- **Visualizations**:
  - **Bar Plot**: Displays the average score by `Track`.
  - **Box Plot**: Visualizes the spread of average scores by `Gender`.
  - **Scatter Plot**: Shows how `Hometown` influences average grades, using a color-coded scatter plot.

## How to Use the Project

1. **Prerequisites**:
   - Python (3.x)
   - Jupyter Notebook
   - Required Libraries: `pandas`, `matplotlib`, `seaborn`

2. **Execution**:
   - Open the provided Jupyter Notebook file (`CHAU_DataWranglingAndDataVisualization.ipynb`) in Jupyter Notebook.
   - Execute each cell to load the dataset, create the data frames, and generate the visualizations.

3. **Dataset**:
   - The notebook is designed to work with a specific dataset. Make sure the dataset is available in the appropriate location, and adjust the file path if necessary.
   - Columns in the dataset include:
     - `Name`: Student's name
     - `Gender`: Student's gender
     - `Track`: Academic track (e.g., Instrumentation, Communication)
     - `Electronics`: Score in Electronics subject
     - `GEAS`: Score in General Engineering and Applied Sciences (GEAS)
     - `Average`: The overall average grade
     - `Hometown`: Student's hometown (e.g., Luzon, Visayas, Mindanao)

## Key Insights

- **Track vs Average Score**: The bar plot shows the average scores across different tracks, revealing how track choices impact overall performance.
- **Gender and Score Distribution**: The box plot highlights the distribution of scores between male and female students, understanding performance variations.
- **Hometown Influence**: The scatter plot shows how students' hometowns correlate with their average scores, helping to visualize geographic trends in performance.
