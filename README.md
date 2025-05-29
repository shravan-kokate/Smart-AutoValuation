# Car Price Detection - Regression and Image Processing

This project implements a car price prediction system using machine learning techniques. It combines regression analysis with image processing to provide accurate car price estimations based on various features.

## Project Overview

The project consists of several key components:

1. **Data Cleaning** (`DataCleaning.ipynb`)
   - Data preprocessing and cleaning
   - Handling missing values
   - Feature engineering

2. **Data Visualization** (`dataVisualization.ipynb`)
   - Exploratory data analysis
   - Visualizing relationships between features
   - Understanding data distribution

3. **Regression Analysis**
   - Linear Regression implementation (`Linear_regression.ipynb`)
   - Random Forest implementation (`Random_Forest.ipynb`)
   - Model training and evaluation

## Dataset

The project uses a comprehensive car price dataset containing features such as:
- Car Name
- Location
- Year of manufacture
- Kilometers driven
- Fuel type
- Transmission type
- Owner type
- Mileage
- Engine capacity

## Project Structure

- `Car_price_data_cleaned.csv` - Cleaned dataset after preprocessing
- `ready_to_use_model.csv` - Processed data ready for model training
- `train.csv` - Original training dataset
- Jupyter notebooks:
  - `DataCleaning.ipynb` - Data preprocessing
  - `dataVisualization.ipynb` - Data exploration and visualization
  - `Linear_regression.ipynb` - Linear Regression implementation
  - `Random_Forest.ipynb` - Random Forest implementation

## Features

- Multi-model approach (Linear Regression and Random Forest)
- Comprehensive data preprocessing
- Feature importance analysis
- Model performance evaluation
- Visualization of results

## Getting Started

1. Clone the repository
2. Install required dependencies:
   ```
   pip install pandas numpy matplotlib scikit-learn
   ```
3. Run the Jupyter notebooks in sequence:
   - Start with `DataCleaning.ipynb`
   - Follow with `dataVisualization.ipynb`
   - Finally, run either `Linear_regression.ipynb` or `Random_Forest.ipynb`

## Results

The project provides:
- Predicted car prices based on input features
- Model performance metrics
- Feature importance analysis
- Visual representations of data relationships

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to the data providers for the car price dataset
- Special thanks to the scikit-learn team for their excellent machine learning library
