<div align="center">

<p align="center">
   <img src="docs/images/logo.png" alt="DaiNam University Logo" width="200"/>
</p>

[![Fit DNU](https://img.shields.io/badge/Fit%20DNU-green?style=for-the-badge)](https://fitdnu.net/)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-red?style=for-the-badge)](https://dainam.edu.vn)

</div>

# Marketing Campaign Analysis and Prediction

This repository contains a comprehensive analysis and prediction of marketing campaigns using big data techniques. The project leverages Apache Spark for data processing and analysis, and builds a recommendation system to suggest products to customers.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Analysis and Results](#analysis-and-results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to analyze marketing campaign data and predict customer behavior. By using Spark, we can efficiently process large datasets and extract meaningful insights. The project also includes a recommendation system to suggest products to customers based on their past purchases.

## Installation

To run this project, you need to have the following dependencies installed:

- Python 3.7 or higher
- Apache Spark
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

You can install the required Python libraries using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/khuong-d4ng/Marketing_Campain_Analyze-Predict_Bigdata_CNTT1602.git
```

2. Navigate to the project directory:

```bash
cd Marketing_Campain_Analyze-Predict_Bigdata_CNTT1602
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook marketing_campain_anlyze&predict.ipynb
```

## Project Structure

- **data/**: Contains the dataset used for analysis.
- **results/**: Contains the results of the analysis and predictions.
- **marketing_campain_anlyze&predict.ipynb**: Jupyter Notebook with the main analysis and prediction code.

## Analysis and Results

The notebook `marketing_campain_anlyze&predict.ipynb` includes the following sections:

1. **Initialization**: Setup Spark session and read the dataset.
2. **Basic Analysis**: Perform basic data analysis, including schema inspection and missing value analysis.
3. **Data Visualization**: Visualize the data distribution and trends.
4. **Advanced Analysis**: Use Spark SQL for complex queries and insights.
5. **Recommendation System**: Build and evaluate a recommendation system using ALS (Alternating Least Squares).
6. **Visualization of Recommendations**: Visualize the top product recommendations for users.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

## License

CNTT1602 Group x
