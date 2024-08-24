# Starbucks Rewards Customer Analysis

This project aims to analyze customer engagement with promotional offers using data from the Starbucks Rewards mobile app. The dataset includes transaction records, demographic information, and details about various promotional offers (e.g., Buy-One-Get-One, discounts, informational ads).

## Project Structure

- **Data Preparation and Cleaning**: 
  - The initial phase involves cleaning and preprocessing the data. This includes handling missing values, transforming categorical variables, and merging multiple datasets to create a comprehensive dataset for analysis.
  
- **Exploratory Data Analysis (EDA)**: 
  - A detailed analysis of the dataset to uncover patterns, trends, and insights. Key areas of focus include age distribution, income levels, gender distribution, and customer engagement with different types of offers.
  
- **Modeling**: 
  - Two neural network models were built to predict customer responses to offers. The models are evaluated on their accuracy and loss values. The project explores different model architectures and feature selection techniques to improve prediction accuracy.

- **Results**: 
  - The models provide insights into which demographic groups are most responsive to specific offer types. While initial models show moderate accuracy, there is potential for improvement through further refinement of the models and features.

## How to Use

1. **Data Files**: 
   - Ensure you have the required data files (`portfolio.json`, `profile.json`, `transcript.json`) in the `data/` directory.
  
2. **Running the Analysis**: 
   - Use the provided Jupyter notebooks to run the data preparation, analysis, and modeling steps. The notebooks are designed to be executed sequentially.

3. **Dependencies**: 
   - Make sure to install the necessary Python libraries before running the notebooks:
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn keras tensorflow
     ```

4. **Outputs**: 
   - The final models' predictions and accuracy metrics will be displayed at the end of the modeling notebook.

## Conclusion

This project demonstrates the application of data science techniques to analyze customer behavior and optimize marketing strategies. By leveraging machine learning models, we aim to personalize offers based on demographic data and improve customer engagement. Further enhancements could include hyperparameter tuning, advanced feature engineering, and exploring alternative models.
