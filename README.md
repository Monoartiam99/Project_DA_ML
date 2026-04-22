# Data Analysis and Visualization Assignment

This repository contains a practice assignment focused on beginner-friendly data analysis and visualization using Python.

The main work is in the notebook `assignment.ipynb`, where you explore datasets and generate different plot types with `seaborn` and `matplotlib`.

## Assignment Goal

Build familiarity with:

- loading and inspecting data
- creating common statistical and comparison plots
- understanding what each chart type is useful for
- basic customization of chart titles, labels, color, and layout

## Repository Structure

- `assignment.ipynb`: main assignment notebook
- `sample-data.csv`: sample CSV file provided in the repo
- `README.md`: assignment guide (this file)

## Topics Covered in the Notebook

The notebook includes examples of:

- dataset loading (`seaborn.load_dataset`) using `tips` and `iris`
- scatter plots
- line plots
- bar plots
- box plots
- histograms
- KDE plots
- pair plots / pair grids
- pie charts
- subplot layouts

It also includes basic DataFrame inspection with `head()` and `tail()`.

## Setup Instructions

1. Install Python 3.9+.
2. Install required packages:

```bash
pip install numpy pandas matplotlib seaborn notebook
```

3. Open the notebook:

```bash
jupyter notebook assignment.ipynb
```

Or open directly in VS Code / Google Colab.

## How to Complete the Assignment

1. Run cells from top to bottom.
2. For each plot cell:
- understand what the plot is showing
- observe axis labels and title
- modify color/style/title to practice customization
3. Try changing data columns and compare how the chart output changes.
4. Add short notes in markdown cells describing your observations.

## Expected Learning Outcome

After completing the notebook, you should be able to:

- select a suitable chart for a data analysis task
- read and explain common visualization outputs
- produce clean basic plots for exploratory data analysis (EDA)

## Notes

- Most notebook examples use built-in seaborn datasets, so internet may be needed the first time those datasets are downloaded.
- The final notebook cell currently reads `data.csv`. If you want to use the included file in this repository, change it to `sample-data.csv`.

## Optional Improvement Tasks

- add markdown headings to divide notebook sections by chart type.
- add interpretation below each plot (1 to 2 lines).
- compare at least two plot types for the same variables and explain which one is more informative.

### About CSV File
- This file contains some basic data on people that they are smoker or not.
- And also conatins the total_bill tips etc