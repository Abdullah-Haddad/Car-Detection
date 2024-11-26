# Car Detection Project

## Overview
This project focuses on predicting bounding box coordinates for car detection using Random Forest Regressor and K-Nearest Neighbors (KNN). The results are compared to determine the better model for this task.

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

## Repository
The project repository is available at the following links:
- [GitHub Repository](https://github.com/Abdullah-Haddad/Car-Detection)
- Git clone link: `https://github.com/Abdullah-Haddad/Car-Detection.git`

## Dataset Instructions
- The dataset is provided in an archived file (`archive.zip`) within the repository.
- **Important**: You must unzip the `archive.zip` file to access the images and data.
  - On Windows: Right-click the file and select "Extract All."
  - On macOS/Linux: Use `unzip archive.zip` in the terminal.

## Running the Code
1. **Clone the repository**:
   ```
   git clone https://github.com/Abdullah-Haddad/Car-Detection.git
   ```
2. **Navigate to the project folder**:
   ```
   cd Car-Detection
   ```
3. **Unzip the dataset**:
   - Ensure `archive.zip` is unzipped in the same directory as the code files.

4. **Run the main script**:
   ```
   Car Detection v2_Final.ipynb
   ```

## Outputs
- Model performance metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R-Squared Score (R2)
- Visualizations:
  - Pairplot for feature distributions.
  - Heatmap for feature correlations.
  - Bounding box predictions (true vs predicted).

## Expected Results
- Comparison between the Random Forest Regressor and K-Nearest Neighbors (KNN) models.
- Final metrics will be displayed in the console.
