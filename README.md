
# Genetic Algorithms and Climate Data Analysis

This project demonstrates the use of genetic algorithms for data analysis, specifically using the TPOT library, 
to work with climate change data. The notebook includes setting up the environment, data loading, and initial exploration.
It looks into equatiorial vs not equatorial variations.
## WIP

## Features

- **Genetic Algorithms**: Leveraging TPOT for automated machine learning and optimization.
- **Climate Data**: Working with a Kaggle dataset on global land temperatures.
- **Exploratory Data Analysis (EDA)**: Understanding and visualizing key data trends.

## Installation

To run this notebook, install the required Python libraries:

```bash
pip install tpot
pip install numpy
pip install pandas
pip install kaggle
pip install scikit-learn
pip install kagglehub
```

Ensure you have access to Kaggle and download the dataset manually or through the Kaggle API.

## Dataset

The dataset used in this project is the **Global Land Temperatures by City** dataset from Kaggle. It contains historical temperature records and is used for analysis.

**Dataset source**: [Kaggle Climate Change Dataset](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)

## Steps in the Notebook

1. **Environment Setup**: Installing necessary libraries.
2. **Data Loading**: Fetching data from Kaggle using `kagglehub` or manually downloading it.
3. **Data Exploration**: Basic insights into the data structure, size, and initial rows.
4. **Genetic Algorithm Implementation**: Using TPOT for data modeling and optimization.

## Usage

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook GeneticAlgos.ipynb
   ```

## Contributions

Feel free to fork the project, submit issues, or suggest features. Pull requests are welcome!

## License

This project is licensed under the MIT License.
