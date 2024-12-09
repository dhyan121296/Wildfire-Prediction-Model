
# Model Card for Wildfire Spread Prediction

## Model Details
- **Model Name**: Random Forest Regressor
- **Model Version**: 1.0
- **Model Type**: Regression
- **Developers**: Dhyan and team
- **Release Date**: December 7, 2024

## Intended Use
- **Primary Use**: Predict wildfire spread rate to inform firefighting strategies.
- **Intended Users**: Emergency services, researchers, and environmental agencies.
- **Out-of-Scope Use Cases**: Prediction outside of trained geographic regions.

## Data Description
- **Dataset**: Includes engineered wildfire features, weather conditions, and fire types.
- **Features**: Temperature, wind speed, relative humidity, and fire type.
- **Preprocessing**: Missing values imputed, categorical features encoded.

## Training and Evaluation
- **Training Procedure**: Trained using Random Forest Regressor with hyperparameter tuning.
- **Evaluation Metrics**: R² Score, Mean Squared Error.
- **Best R² Score**: 0.99 on cross-validation.

## Limitations
- **Data Bias**: Limited to Alberta's wildfire data.
- **Generalizability**: May underperform in different climatic regions.

## Recommendations
- **For Deployment**: Integrate with a real-time weather API for dynamic predictions.
- **Future Work**: Extend to other regions and refine with additional features.

## Contact
For inquiries, contact [dbhavsar@ualberta.ca & spoudel2@ualberta.ca].
