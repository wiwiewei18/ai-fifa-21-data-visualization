# FIFA21 Data Cleaning and Visualization Project

## Overview

This project focuses on cleaning and analyzing the FIFA21 dataset. Using `pandas` for data preprocessing, `matplotlib` and `seaborn` for data visualization, we’ll explore player statistics, performance metrics, and trends to derive insights from the data.

## Dataset

- **Dataset**: FIFA21 Player Dataset
- **Source**: [FIFA21 Dataset](https://storage.googleapis.com/rg-ai-bootcamp/assignment-1/fifa21_raw_data.csv)
- **Description**: This dataset includes player information from the FIFA21 video game, featuring player attributes such as name, position, nationality, club, ratings, and physical and technical skills.

## Project Structure

- `datasets/`: Contains the FIFA21 dataset files.
- `notebooks/`: Jupyter notebooks for data cleaning and visualization of FIFA21 data.
- `utils/`: Python utils scripts.
- `visualizations/`: Visualization of FIFA21 data.
- `README.md`: This file.

## Installation

### Prerequisites

- Python 3.7 or above
- [venv](https://docs.python.org/3/library/venv.html) for creating a virtual environment.

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/wiwiewei18/ai-fifa-21-data-visualization.git
   cd ai-fifa-21-data-visualization
   ```

2. Create a virtual environment:

   ```bash
   python3 -m venv .venv
   ```

3. Activate the virtual environment:

   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Data Cleaning

The data cleaning process includes:

- Removing unnamed column.
- Removing newline character `\n`.
- Removing star character `★`.
- Filling missing value.
- Converting financial data.

### Visualization

Visualizations showcase player distributions, key performance metrics, and trends in player attributes. Using `matplotlib` and `seaborn`, we can:

- Visualizing preferred foot using pie chart.
- Visualizing top 6 FIFA21 players using bar plot.
- Visualizing top 8 FIFA21 teams by ova using bar plot.
- Visualizing top 10 FIFA21 teams by value using bar plot.
- Visualizing top underpaid valuable players using scatter plot.

### Jupyter Notebooks

Explore step-by-step data cleaning and visualization in the `notebooks` folder

## Requirements

- `pandas`
- `matplotlib`
- `seaborn`

Install all dependencies with:

```bash
pip install -r requirements.txt
```
