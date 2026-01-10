# Pima-Diabetes-Analysis-System.

# Project Overview
This repository contaqins a comprehensive data analysis pipeline and a Graphical User Interface (GUI) designed to analyse factors asssociated with diabetes. Using the Pima Indians Diabetes dataset, the system perfroms data cleaning, statistical auditing and interactive visualisation.

# Repository Structure
The project is organised into dedicated directories to ensure portability and clarity:
-  /data: Contains the raw dataset (diabetes.csv)
-  /notebooks: contains the primary Jupyter Notebook with the full analysis and GUI code.
-  /README.md: Project documentation and setup instructions.

# Key Features:
-  Section 1-3 (data cleaning): Automated detection of invalid "0" entries in mdeical columns and treatment using Median Imputation.
-  Section 4 (Visual Analytics): Distribuytion plots, correlation heatmaps, and trend analysis using Seaborn and Matplotlib.
-  Section 5 (interactive GUI): A custom Tkinter dashboard featuring:
     - Frame-switching navigation: A single window interface.
     - Data subsetting: Filtering tool sto isolate specific patient groups.
     - Web based plotly visualisation accessible directly via the GUI.
 
# Requirements:
- Python
Libraries required:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Plotly
- Tkinter
- Io
- Contextlib

# How to run
1 Navigate to /notebooks folder and open the .ipynb file in Jupyter.
2 Run all cells (run all cells option)
3 The Diabetes Data Analysis System window will launch automatically
