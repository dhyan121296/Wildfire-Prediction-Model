---

### Model Card for the Wildfire Prediction Model

```markdown
# Model Card: Wildfire Prediction Model

## Model Details
•⁠  ⁠*Type*: Machine Learning Model
•⁠  ⁠*Purpose*: Predict wildfire occurrences and sizes based on weather and geospatial data.
•⁠  ⁠*Framework*: Scikit-learn
•⁠  ⁠*Release Date*: December 7, 2024

## Intended Use
•⁠  ⁠*Primary Goal*: Assist researchers and policymakers in forecasting wildfires to mitigate risks.
•⁠  ⁠*Use Cases*:
  - Research on environmental factors affecting wildfires.
  - Development of early warning systems.

## Dataset Details
•⁠  ⁠Combines wildfire event records, weather station metadata, and extensive weather readings.
•⁠  ⁠Data includes geographic coordinates, temporal factors, and key environmental variables.

## Metrics
•⁠  ⁠*Evaluation Metrics*:
  - Accuracy
  - Precision
  - Recall
  - Mean Squared Error (for size prediction)
•⁠  ⁠*Baseline Performance*:
  - Random Forest Model: Accuracy of 1.00 with a macro-average F1-score of 0.86
  - XGBoost Model: Accuracy of 1.00 with a macro-average F1-score of 0.86
  - SVM Model: Accuracy of 1.00 with a macro-average F1-score of 0.33
  - KNN Model: Accuracy of 1.00 with a macro-average F1-score of 0.33
  - LightGBM Model: Accuracy of 1.00 with a macro-average F1-score of 0.37
  - CatBoost Model: Accuracy of 1.00 with a macro-average F1-score of 0.86

## Limitations
•⁠  ⁠Model predictions are based solely on the provided datasets.
•⁠  ⁠Accuracy may decrease for regions with sparse data coverage or unique environmental conditions.

## Ethical Considerations
•⁠  ⁠*Impact*: May guide resource allocation during wildfire events.
•⁠  ⁠*Bias*: Ensure diverse geographic data coverage to reduce prediction biases.

## Future Improvements
•⁠  ⁠Incorporate additional datasets, e.g., satellite imagery.
•⁠  ⁠Test model generalizability across different regions.

---

*Contact Information*: For queries or contributions, please contact dbhavsar@ualberta.ca / spoudel2@ualberta.ca