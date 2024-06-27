# Analysis and Visualization of Crime in London City

## Project Overview
 [Uber and Lyft Dataset Boston, MA](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma) is the provided dataset. We can use the dataset to conduct analysis of the factors influencing the competition between Uber and Lyft in the Bostonm Massachusetts region. These tow companies offer similar services, specifically online transportation, but they vie for the market share through aspects such as pricing service quality, availability, and other variables. Consequently, this data analysis seeks to identify and evaluate the determinants that impact pricing strategies. In this data analysis, the linier regression method is employed as it aligns with our objective of identifying the factors influencing pricing by modeling several dependent variables and determining the best-fitting model.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgements](#acknowledgements)

## Dataset
The dataset used in this project is sourced from Kaggle:  [Uber and Lyft Dataset Boston, MA](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma).

## Installation
To run this project locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/mfarizky/ligres-uber-lyft.git
    cd ligres-uber-lyft
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To use this project, follow these steps:

1. Download the dataset from Kaggle and place it in the `data` directory.
2. Run the data analysis and visualization scripts:
    ```bash
    jupyter notebook
    ```
3. Open the `Linear_Regression.ipynb` notebook and run the cells to see the analysis and visualizations.

## Features
- **Data Cleaning:** Preprocessing and cleaning the dataset for analysis.
- **Exploratory Data Analysis (EDA):** Statistical analysis and visualization of several dependent variables.
- **Linear Regression:** Analyzing factor influencing pricing Uber vs Lyft.
- **Model Inference:**predicting dependent variable (prices) using influenced factors.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or issues, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Acknowledgements
- The [Uber and Lyft Dataset Boston, MA](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma) provided by Kaggle.
- Inspiration and guidance from various data science and machine learning communities.
---

Feel free to customize the above template according to your specific project details and preferences.
