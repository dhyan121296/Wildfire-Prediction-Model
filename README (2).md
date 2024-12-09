
# Wildfire Prediction Project

This project predicts wildfire spread rates using machine learning models. The focus is on building reusable components, ensuring transparency through a model card, and providing instructions for running the project.

## Project Structure
- **src/**: Contains Python scripts for preprocessing, training, evaluation, and utility functions.
- **notebooks/**: Research notebook for exploratory data analysis.
- **data/**: Includes the dataset (`engineered_features.csv`).
- **models/**: Stores trained models (`wildfire_rf_model.pkl`).
- **research/**: Holds non-evaluated research files.
- **README.md**: Overview of the project with setup and usage instructions.
- **MODEL_CARD.md**: Details of the best-performing model.

## How to Run the Project

### Step 1: Setup
Install the required libraries:
```bash
pip install -r requirements.txt
```

### Step 2: Train the Model
Run the training script to train and save the model:
```bash
python src/training.py
```

### Step 3: Evaluate the Model
Evaluate the model's performance:
```bash
python src/evaluation.py
```

### Step 4: Predict Wildfire Spread
Run the prediction script:
```bash
python src/predict.py
```

## Acknowledgements
This project is part of the ENG M 680 course, demonstrating advanced machine learning workflows.
