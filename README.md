
# NYC 311 Calls Analysis

This project analyzes NYC 311 service requests using a Jupyter notebook. The dataset includes information on various types of complaints recorded through the 311 service. The analysis aims to identify trends, patterns, and insights from the data, and also includes a time series forecasting model.

## Project Structure

- **Data Loading and Cleaning**: The initial part of the notebook is dedicated to loading the data, handling missing values, and preparing it for analysis.
- **Exploratory Data Analysis (EDA)**: Various visualizations and summaries are provided to understand the distribution and frequency of different types of complaints.
- **Time Series Analysis**: A time series forecasting model is built to predict future complaints using the Prophet library.

## Notable Sections

1. **Data Import and Preparation**
    - Loading the dataset.
    - Data cleaning and preprocessing steps.
    
2. **Exploratory Data Analysis (EDA)**
    - Analysis of complaint types.
    - Visualizations of complaint trends over time.
    - Breakdown of complaints by borough and other relevant categories.

3. **Time Series Forecasting**
    - Splitting the data into training and testing sets.
    - Training a Prophet model on the data.
    - Predicting future complaint volumes.
    - Evaluating the model's performance using RMSE.

## Dependencies

- Python 3.11
- pandas
- numpy
- matplotlib
- seaborn
- fbprophet
- scikit-learn

You can install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn fbprophet scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/nyc-311-calls-analysis.git
```

2. Navigate to the project directory:

```bash
cd nyc-311-calls-analysis
```

3. Open the Jupyter notebook:

```bash
jupyter notebook nyc_311_calls.ipynb
```

4. Run the cells sequentially to reproduce the analysis.

## Results

- The notebook provides insights into the most common types of complaints, their distribution over time, and variations across different boroughs.
- The time series model forecasts future complaint volumes with a root mean squared error (RMSE) of approximately 1231.51.

## Conclusion

This analysis of NYC 311 calls provides valuable insights into the types of issues reported by residents and helps in understanding trends over time. The forecasting model can be used to anticipate future service requests, aiding in better resource allocation and management.

## Author

Anikait Arun Chavan

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
