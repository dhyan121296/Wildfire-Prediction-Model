
# Model Card: Wildfire Prediction Model

---

## Model Details
- **Type**: Machine Learning Model  
- **Purpose**: Predict wildfire occurrences and sizes based on weather and geospatial data.  
- **Framework**: Scikit-learn, LightGBM, and CatBoost  
- **Release Date**: December 7, 2024  

---

## Intended Use
- **Primary Goal**: Assist researchers, policymakers, and emergency responders in forecasting wildfires to mitigate risks.  
- **Use Cases**:  
  - Research on environmental and climatic factors influencing wildfires.  
  - Development of early warning systems for wildfire management.  
  - Optimizing resource allocation during wildfire events.  

---

## Dataset Details
- **Data Sources**: Combines wildfire event records, weather station metadata, and historical weather readings.  
- **Features Include**:  
  - Geographic coordinates (latitude, longitude)  
  - Temporal factors (date, time)  
  - Environmental variables (temperature, humidity, wind speed)  

---

## Metrics
- **Evaluation Metrics**:  
  - Classification Tasks: Accuracy, Precision, Recall, and F1-Score  
  - Regression Tasks: Mean Squared Error (MSE) and R-Squared (R²)  
- **Performance Highlights**:  
  - Random Forest Model: Macro-average F1-score of 0.86  
  - XGBoost Model: Macro-average F1-score of 0.86  
  - CatBoost Model: Macro-average F1-score of 0.86  
  - Other models (SVM, KNN, LightGBM): Lower F1-scores, indicating reduced performance for classification tasks.  

---

## Limitations
- **Data Dependency**: The model relies solely on the provided datasets, which may not capture all environmental or human factors influencing wildfires.  
- **Geographic Bias**: Predictions may be less accurate for regions with sparse data coverage or unique environmental conditions.  
- **Temporal Gaps**: Limited historical data may reduce the model's effectiveness in forecasting emerging trends.  
- **Scalability**: Model performance may degrade if applied to datasets significantly larger or more complex than those used during training.

---

## Ethical Considerations
- **Impact**: The model aims to improve decision-making during wildfire events, potentially reducing human, environmental, and economic losses.  
- **Bias**: Ensure diverse geographic and environmental data to reduce prediction biases. Evaluate the fairness of predictions across different regions and populations.  
- **Transparency**: Provide clear documentation of model processes, assumptions, and data usage. Ensure predictions are interpretable and explainable to users.  
- **Privacy**: Protect sensitive data, such as precise geographic coordinates of affected areas, to prevent misuse.  
- **Fairness**: Avoid over-reliance on features that could disproportionately affect certain regions or groups.  
- **Security**: Safeguard the model and data from unauthorized access or adversarial attacks to maintain reliability and accuracy.  

---

## Future Improvements
- **Data Enrichment**: Incorporate additional datasets, such as satellite imagery and social data, to improve prediction accuracy.  
- **Generalizability**: Test and refine the model for use across diverse geographic regions and environmental conditions.  
- **Real-Time Integration**: Enhance the model to process and predict wildfire risks using real-time weather and geospatial data.  
- **Ethical Auditing**: Regularly review the model’s fairness, transparency, and bias to ensure it meets ethical standards.  

---

**Contact Information**  
For queries or contributions, please contact:  
- Email: dbhavsar@ualberta.ca / spoudel2@ualberta.ca  
