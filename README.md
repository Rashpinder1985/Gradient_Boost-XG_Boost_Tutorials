# 🔋 Gradient Boosting & XGBoost for EV Battery Life Prediction

This repository presents a structured tutorial and slide deck (PDF) exploring the theory and practical applications of **Gradient Boosting** and **XGBoost** in the context of electric vehicle (EV) battery life prediction.


## 📚 Contents

### 🎓 Slide Deck Structure
The presentation is divided into 6 educational sections:

1. **Introduction to Gradient Boosting**  
2. **Understanding Gradient Boosting with EVs**  
3. **Hands-On: Gradient Boosting with Matrices**  
4. **Hands-On: Gradient Boosting with Python**
    - 💾 **Importing Dataset in Google Colab**
        ```python
        from google.colab import files
        uploaded = files.upload()

        import pandas as pd
        df = pd.read_csv("synthetic_ev_battery_data.csv")
        df.head()
        ```
    - 🔍 Train/Test split, model training using `GradientBoostingRegressor`
5. **XGBoost Explained**
    - Training with `XGBRegressor`, evaluating with RMSE, R²
6. **Comparison: Gradient Boosting vs. XGBoost**
    - Metric-based comparison table (MAE, RMSE, R²)


## 🛠️ How to Use

### ▶ Read Slides
- Open the included PDF file: `gradient_boosting_xgboost_deck.pdf`
- Contains visuals, math, code, and model comparisons

### ▶ Run Notebook
- Open `gradient_and_xgboost_notebook.ipynb` in Google Colab or Jupyter.
- Upload `synthetic_ev_battery_data.csv` when prompted.


## 📦 Technologies Used

- `scikit-learn`, `xgboost`, `matplotlib`, `pandas`
- PDF-based LaTeX Beamer presentation


## 📈 Example Use Case

Predict EV battery life using:
- Charge Cycles  
- Average Temperature  
- Battery Age  


## 🧠 Learn More

See the notebooks and slides to explore:
- Gradient descent with trees  
- Residual fitting  
- Regularization in XGBoost  
- Evaluation metrics: MAE, RMSE, R²


## 📄 License

MIT License — use freely with credit.


## 🤝 Contributions

Fork the repo, open issues, or contribute improvements!
