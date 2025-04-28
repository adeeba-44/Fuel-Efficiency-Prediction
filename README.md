# 🚗 Fuel Efficiency Prediction Using Machine Learning

## 📚 Project Overview
This project focuses on predicting **fuel efficiency (miles per gallon - MPG)** using machine learning algorithms. The dataset includes key automotive features like **cylinders**, **horsepower**, **weight**, **acceleration**, and **origin** of the car. The goal is to accurately forecast a car’s MPG based on these characteristics.

## 📂 Dataset Information
The dataset contains the following columns:
- `mpg`: Miles per gallon (target variable)
- `cylinders`: Number of cylinders in the car
- `displacement`: Engine displacement
- `horsepower`: Engine horsepower
- `weight`: Vehicle weight
- `acceleration`: Time to accelerate from 0-60 mph
- `model year`: Model year of the car
- `origin`: Geographical origin of the car (1 = USA, 2 = Europe, 3 = Asia)
- `car name`: Name of the car (removed for modeling)

> **Note:** Missing values were carefully handled to ensure accurate model predictions.

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/fuel-efficiency-prediction.git
cd fuel-efficiency-prediction
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

**Required Libraries:**
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Alternatively, install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 How to Run

1. Ensure that `auto-mpg-3.csv` is in the working directory.
2. Run the Jupyter Notebook:

```bash
jupyter notebook "Fuel efficiency prediction using ML.ipynb"
```

3. Follow the notebook's structured steps:
   - Data Preprocessing
   - Exploratory Data Analysis
   - Model Training
   - Model Evaluation

## 📈 Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Others (as experimented)

### Evaluation Metrics
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

## 📊 Results
The project achieved a good level of accuracy in predicting fuel efficiency. Feature importance analysis and model tuning were performed to enhance prediction quality.

## 🤝 Contributing

Contributions are welcome!  
If you have suggestions for improvements, please fork the repo and submit a pull request.

Steps to contribute:
1. Fork the repository
2. Create a new branch:

```bash
git checkout -b feature-branch
```

3. Commit your changes:

```bash
git commit -m 'Add new feature'
```

4. Push to the branch:

```bash
git push origin feature-branch
```

5. Open a Pull Request

## 📄 License

This project is licensed under the [MIT License](LICENSE).

