# 🚗 Car Detection Project

## 🎯 Overview
This project aims to predict bounding box coordinates for car detection using **Random Forest Regressor** and **K-Nearest Neighbors (KNN)**. We compare the performance of these models to determine the better option for this task. The dataset includes labeled bounding box coordinates for car images.

---

## 📋 Requirements
To run the project, ensure you have the following:
- **Python 3.x**
- Libraries:
  - `pandas`
  - `numpy`
  - `sklearn`
  - `matplotlib`
  - `seaborn`

---

## 📂 Repository Links
You can access the project repository via the following links:
- **[GitHub Repository](https://github.com/Abdullah-Haddad/Car-Detection)**  
- **Git clone URL**:  
  ```
  https://github.com/Abdullah-Haddad/Car-Detection.git
  ```

---

## 📦 Dataset Instructions
- The dataset is included in the repository as a compressed archive (`archive.zip`).
- **Important**: The dataset must be unzipped to access the images and files.
  - **Windows**: Right-click `archive.zip` and select "Extract All."
  - **macOS/Linux**: Use the command `unzip archive.zip` in the terminal.

---

## ⚙️ How to Run the Code

### Step 1: Clone the Repository
Run the following command in your terminal to clone the repository:
```bash
git clone https://github.com/Abdullah-Haddad/Car-Detection.git
```

### Step 2: Navigate to the Project Folder
Move into the repository folder:
```bash
cd Car-Detection
```

### Step 3: Extract the Dataset
Ensure `archive.zip` is unzipped in the same directory as the project files.

### Step 4: Open and Run the Script
Launch the Jupyter Notebook file:
```bash
Car Detection v2_Final.ipynb
```

Run all cells sequentially to train and evaluate the models.

---

## 📊 Results and Outputs
The project generates the following:
- **Performance Metrics**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R-Squared Score (R2)
- **Visualizations**:
  - **Pairplot**: Displays feature distributions.
  - **Heatmap**: Highlights feature correlations.
  - **Bounding Box Predictions**: Compares true and predicted bounding boxes.

---

## 📈 Expected Results
The following comparisons are conducted:
1. **Random Forest Regressor**:
   - Baseline and tuned performance metrics.
   - Key strengths: Handles complex data relationships efficiently.
2. **K-Nearest Neighbors (KNN)**:
   - Performance metrics for comparison.
   - Simpler but effective for small datasets.

---

## 🛠 Future Enhancements
1. **Model Exploration**:
   - Incorporating advanced models like YOLOv5 or Faster R-CNN for object detection.
2. **Dataset Improvements**:
   - Expanding the dataset with additional conditions (e.g., lighting, angles).
3. **Real-Time Integration**:
   - Deploying the model to edge devices for live car detection.

---

## 🤝 Contributions
This project was developed by:
- **Abdullah Haddad**:
  - Implemented models, tuning, and performance analysis.
  - Documentation and repository management.
- **Naman Patel**:
  - Preprocessing, feature engineering, and validation.
- **Bilal Dhillon**:
  - Presentation preparation and report contributions.

---

## 📧 Contact
For questions or feedback, please contact:
- **Abdullah Haddad**: [GitHub](https://github.com/Abdullah-Haddad)

---

This enhanced README structure organizes information into digestible sections, uses emojis for visual appeal, and includes details that highlight the project’s significance. You can copy and paste this template into your README.md file to make it more professional and appealing. Let me know if you'd like additional refinements!
