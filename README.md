
# Wildfire Prediction Project

This project predicts wildfire occurrences and sizes using machine learning models based on weather and geospatial data. It combines multiple datasets to enhance predictive accuracy and provides insights into the relationships between environmental factors and wildfire activity.

## Project Workflow

The project is divided into the following stages:
1. **Data Loading**: Import wildfire data, weather readings, and weather station metadata.
2. **Data Cleaning**: Preprocess the datasets to handle missing values, inconsistencies, and errors.
3. **Dataset Merging**: Integrate datasets based on geographic and temporal attributes.
4. **Exploratory Data Analysis (EDA)**: Analyze data patterns, correlations, and outliers.
5. **Feature Engineering**: Create derived features to improve model performance.
6. **Model Training**: Train machine learning models to predict wildfire occurrences and sizes.
7. **Evaluation**: Assess model accuracy using appropriate metrics.
8. **Output Saving**: Store model results for reporting and future use.

## Datasets

### 1. **Wildfire Dataset**
- **Size**: ~61 columns.
- **Attributes**: Fire event details, geospatial information, and associated environmental conditions.

### 2. **Weather Readings**
- **Entries**: Over 1 million.
- **Attributes**: Includes temperature, humidity, precipitation, and wind speed.

### 3. **Weather Stations**
- **Metadata**: Contains station names, locations (latitude, longitude), and elevation.

## Key Libraries and Tools

- **Programming Language**: Python
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Notebook Environment**: Jupyter

## Results

- Initial model training results are saved for further analysis.
- Insights from feature importance and EDA provide a better understanding of key predictors.

## How to Run

Follow these steps to set up and run the repository:

1. **Clone the Repository**
   Clone the repository to your local machine using the following command:
   ```bash
   git clone <repository_link>
   ```

2. **Navigate to the Project Directory**
   Move into the project directory:
   ```bash
   cd <repository_name>
   ```

3. **Install Required Dependencies**
   Ensure you have Python 3.x installed, then install all required libraries using:
   ```bash
   pip install -r requirements.txt
   ```

4. **Prepare the Dataset**
   - Place the datasets (`processed_weather_stations.csv`, `processed_wildfire_df.csv`, `weather_readings.csv`) in the specified directory or note their paths.
   - Update the file paths in the notebook if your files are stored in a different location.

5. **Run the Jupyter Notebook**
   Open the Jupyter Notebook file for execution:
   ```bash
   jupyter notebook ENG_M_680_Final_Project_Dhyan_Suman.ipynb
   ```

6. **Execute the Notebook**
   - Open the notebook in your browser.
   - Execute all cells sequentially from top to bottom to ensure the workflow completes properly.
   - If the notebook encounters any issues, verify the file paths and dependencies.

7. **Output**
   - Review the final outputs, including predictions, visualizations, and evaluation metrics.
   - Results will be saved in the specified directories as defined in the notebook.

8. **Save Your Work**
   - Save any changes made to the notebook.
   - Export results or visualizations if needed.

### Standard Operating Procedure (SOP) for Running the Model

1. Ensure Python 3.x and Jupyter Notebook are installed on your machine.
2. Verify that all required libraries (listed in `requirements.txt`) are installed.
3. Confirm the datasets are in the correct folder or update the paths in the notebook.
4. Run the notebook cells sequentially without skipping any step.
5. Examine the outputs and verify the results are generated as expected.
6. If needed, rerun specific cells with modified parameters or data for additional analysis.

## Contributions

Contributions to this project are welcome! Feel free to fork the repository and submit a pull request for review.

