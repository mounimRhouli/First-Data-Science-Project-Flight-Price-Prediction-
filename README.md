# First Data Science Project: Flight Price Prediction ✈️

![Flight Price Prediction Banner]([https://via.placeholder.com/1200x300?text=Flight+Price+Prediction](https://www.google.com/imgres?q=Flight%20Price%20Prediction%20image&imgurl=https%3A%2F%2Fwww.datascienceportfol.io%2Fstatic%2Fprofile_pics%2Fpr5_E9FC1E287B3376C45EB9.jpg&imgrefurl=https%3A%2F%2Fwww.datascienceportfol.io%2FSavitar%2Fprojects%2F5&docid=c-YFkjTfej45lM&tbnid=9FDif6FiiZM_3M&vet=12ahUKEwj567KV-9uPAxVOVqQEHRo8FAk4ChAzegQIJxAA..i&w=697&h=208&hcb=2&itg=1&ved=2ahUKEwj567KV-9uPAxVOVqQEHRo8FAk4ChAzegQIJxAA))

## Overview

This is my first data science project. This project predicts flight prices using machine learning. It leverages features such as airline, source & destination cities, departure/arrival times, stops, class type, duration, and days left before departure.  

The pipeline includes:
- Exploratory Data Analysis (EDA)
- Data Preprocessing (encoding, scaling)
- Model Training (Linear Regression, Decision Tree, Random Forest, Gradient Boosting)
- Evaluation (MSE, RMSE, R²)
- Saving the best model
- Prediction function
- Streamlit web app for interactive predictions  

The flight price dataset is **cleaned** and ready to use.

## Dataset

- CSV file: `flight_prices.csv`  
- Columns:  
  - `airline`, `source_city`, `departure_time`, `stops`, `arrival_time`, `destination_city`, `class`, `duration`, `days_left`, `price` (target)  

Upload the dataset to Colab or mount Google Drive.

## Prerequisites

- Google Colab
- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `pickle`, `streamlit`
- Optional: Google Drive for saving models

## Installation

```bash
!pip install pandas numpy matplotlib seaborn scikit-learn streamlit -q
!npm install -g localtunnel
````

## Usage

### Run Notebook

1. Load the dataset.
2. Perform EDA and preprocessing.
3. Train and evaluate models.
4. Save the best model.
5. Test predictions.
6. Launch Streamlit app.

### Launch Streamlit App in Colab

```bash
!streamlit run app.py &>/dev/null&
!lt --port 8501
```

Use the provided URL to access the interactive app.

## Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/new-feature`
3. Commit: `git commit -m 'Add new feature'`
4. Push: `git push origin feature/new-feature`
5. Open a Pull Request

## License

MIT License.

