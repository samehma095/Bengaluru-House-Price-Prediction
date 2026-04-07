🏠 Bengaluru House Price Prediction

📊 Project Overview
This project is an End-to-End Machine Learning solution to predict real estate prices in Bengaluru, India. I performed extensive data cleaning, outlier removal, and built a regression model with **89% accuracy**.

🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Numpy, Matplotlib, Scikit-learn
* **Environment:** Jupyter Notebook (Anaconda)

🧹 Key Data Cleaning Steps
1. **Handling Missing Values**: Cleaned locations and bathroom data.
2. **Feature Engineering**: Extracted 'BHK' from size and handled non-numeric square footage ranges.
3. **Dimensionality Reduction**: Grouped 1000+ locations into 144 main locations.
4. **Outlier Removal**: Removed inconsistent data points (e.g., houses with too many rooms for their area).

 🚀 How to use
The trained model is saved in `banglore_home_prices_model.pickle`. You can use the `predict_price` function in the notebook to get price estimates.
