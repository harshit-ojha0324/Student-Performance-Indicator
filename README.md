# Student Performance Prediction

This repository contains the code and models for analyzing and predicting student performance using machine learning techniques. The project leverages exploratory data analysis (EDA), preprocessing, and model training using Ridge Regression and CatBoost.

## Project Structure

- **EDA Notebook (`eda_student_performance_indicator.ipynb`)**  
  - Explores the dataset to identify patterns, correlations, and key factors affecting student performance.
  - Visualizes relationships between different variables.

- **Preprocessing (`consistent_preprocessor.pkl`)**  
  - Ensures consistent feature transformations across training and inference stages.
  - Handles missing values, categorical encoding, and feature scaling.

- **Model Training (`model_training.ipynb`)**  
  - Implements Ridge Regression and CatBoost models for student performance prediction.
  - Includes hyperparameter tuning and performance evaluation.

- **Best Model (`best_ridge_model.pkl`)**  
  - Stores the trained Ridge Regression model optimized for performance.

- **CatBoost Training Log (`catboost_training.json`)**  
  - Captures learning metrics, including RMSE values over 1000 iterations.

- **Other Files**  
  - `stud.csv`: Processed dataset.
  - `learn_error.tsv`, `time_left.tsv`, `events.out.tfevents`: Training logs and diagnostics.

## Key Highlights

- **Data Processing**: Ensured robust and scalable preprocessing for consistent performance.
- **Exploratory Analysis**: Gained insights into student performance determinants.
- **Model Optimization**: Ridge Regression and CatBoost models fine-tuned for accuracy.

## Usage

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd student-performance-prediction
2. **Install dependencies:**
   ```sh
    pip install -r requirements.txt

3. **Run the Jupyter Notebooks for EDA and training:**

   ```sh
   jupyter notebook eda_student_performance_indicator.ipynb
   jupyter notebook model_training.ipynb

4. **Use the trained models for inference**

## Future Improvements
- Integrate deep learning models for performance enhancement.
- Deploy the best-performing model as an API for real-world applications.
