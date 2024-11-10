# Matplotlib and Pyplot Data Visualization Project

Welcome to the Matplotlib and Pyplot Data Visualization Project! This repository contains a Jupyter Notebook assignment focused on creating and analyzing data visualizations using Python's Matplotlib library.

## Project Overview

This project is part of the Web Mining and Applied NLP (44-620) course, aiming to develop and showcase your proficiency in data visualization techniques. The tasks within the notebook include:

- Creating bar plots to display frequency distributions.
- Generating scatter and line plots with varied styles and colors.
- Comparing algorithm performance using dual plots with legends.

## Repository Contents

- **`pyplot.ipynb`**: The Jupyter Notebook containing the code, visualizations, and markdown explanations.
- **`pyplot.html`**: The exported HTML version of the notebook for easy viewing without running the code.
- **`requirements.txt`**: A file specifying the Python packages required to run the notebook.
- **`README.md`**: This document.

## Running the Project

To run the notebook locally, follow these steps:

1. **Clone the repository**:
```bash
   git clone https://github.com/bware7/pyplot_binware
   cd pyplot_binware
```

2. **Set up a virtual environment**:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Install dependencies**:
```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**:
```bash
jupyter notebook
Open pyplot.ipynb in your browser and run the cells to view the visualizations and outputs.
```


## Summary of Questions

Question 1: Character Frequency Bar Plot

Task: Create a bar plot to show the frequency distribution of characters in a given text using Python's collections.Counter.

Summary: This task involves parsing a text, counting the frequency of each character, and visualizing the result with labeled bars and axes.

Question 2: Scatter and Line Plot

Task: Generate a set of random numbers and visualize the data using both a scatter plot and a line plot on different axes.

Summary: Demonstrates the use of scatter and line plots for visualizing random data points, showcasing the differences in how each plot type represents the data.

Question 3: Styled Scatter and Line Plot

Task: Repeat Question 2 but change the color and style of both the scatter and line plots.

Summary: This task shows customization options in Matplotlib for visual elements such as color, line styles, and marker types to enhance data visualization.

Question 4: Algorithm Performance Plot

Task: Plot the time it takes to execute a sorting algorithm (insertion sort and merge sort) on a list of different sizes, using the given data sets.

Summary: This question emphasizes plotting comparative data on the same set of axes with appropriate labels, markers, and a legend to differentiate between the two algorithms.

