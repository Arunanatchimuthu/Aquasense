# AquaSense: AI-Powered Water Threshold Management

## Project Overview
AquaSense utilizes machine learning to set optimal water usage thresholds based on household and environmental factors. This helps in preventing excessive water consumption and promoting sustainable water management.

## Features
- **AI-Based Threshold Setting**: Uses machine learning models to determine optimal water usage limits.
- **Multiple Model Comparisons**: Implements Gradient Boosting, Random Forest, and XGBoost for accuracy comparison.
- **User Input Evaluation**: Allows users to input household details and receive water threshold recommendations.
- **Feature Scaling & Encoding**: Preprocesses data for improved model performance.

## Dataset
- **Threshold Dataset** (`thershold_dataset.csv`): Contains sensor readings and household details for training the models to set appropriate water usage thresholds.

## Technologies Used
- **Machine Learning**: Scikit-learn, XGBoost for predictive modeling.
- **Data Processing**: Pandas and NumPy for dataset handling.
- **Feature Scaling & Encoding**: StandardScaler and LabelEncoder.
- **Evaluation Metrics**: Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score.
- **Programming Language**: Python.
  
## Usage
- Train and evaluate machine learning models for setting optimal water usage thresholds.
- Input household data to receive recommended water usage limits.
- Compare different models based on MAE, MSE, and R² score.

## Example Threshold Prediction
To predict an optimal water usage threshold based on user input:
```python
predicted_threshold = predict_water_threshold(model, "Jan", 4, 1, 40, 52.01, 1500, 3, 2)
print(f"Recommended Water Usage Threshold: {predicted_threshold}")
```

## Future Enhancements
- Add deep learning models for improved threshold accuracy.
- Develop a web-based interface for user-friendly interaction.
- Integrate IoT-based real-time monitoring for adaptive threshold adjustments.
