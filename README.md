# Bayesian Linear Regression in Soccer Analytics

This project analyzes FIFA video game statistics to predict the ball control of Argentinian football players using their dribbling skills.

## Files

- `Code.ipynb`
- `Footballdata.csv`

## Requirements

- Python 3.x
- Arviz
- Matplotlib
- NumPy
- Pandas
- PyMC
- SciPy
- Seaborn

## Installation

1. Clone the repository or download the files.
2. Install the required libraries using pip:

    ```sh
    pip install arviz matplotlib numpy pandas pymc scipy seaborn
    ```

## Usage

### Running the Analysis

1. Open the `Code.ipynb` notebook using Jupyter Notebook or JupyterLab.
2. Run all the cells to perform the analysis. The notebook will:
    - Load and clean the dataset.
    - Filter the dataset to include only Argentinian players.
    - Perform statistical analysis on the dribbling and ball control variables.
    - Visualize the results.

## Dataset

The dataset used in this project is derived from FIFA video game statistics. It contains various attributes of football players, including their nationality, club, rating, and specific skills.

### Key Variables

- **Dribbling**: This variable represents the dribbling skills of the players.
- **Ball Control**: This variable represents the ball control abilities of the players.

### Dataset Source

The dataset can be found in the `Footballdata.csv` file. The initial dataset includes players of all nationalities, but for this project, we focus specifically on Argentinian players.

## Code Explanation

### Code.ipynb

This Jupyter notebook performs the following steps:

- **Data Loading**: Loads the dataset from the CSV file.
- **Data Cleaning**: Filters the dataset to include only Argentinian players and extracts the relevant variables (Dribbling and Ball Control).
- **Statistical Analysis**: Performs statistical analysis to explore the relationship between dribbling and ball control.
- **Visualization**: Creates visualizations to illustrate the findings from the analysis.

## Conclusion

The project aims to provide insights into how well dribbling skills predict ball control among Argentinian football players based on FIFA video game statistics.

