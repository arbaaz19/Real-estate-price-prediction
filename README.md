# **Housing Market Analytics Workflow**

## **Project Overview**
This project focuses on analyzing and predicting housing prices in King County, Washington, using a real-world dataset sourced from Kaggle. The workflow includes data preprocessing, exploratory data analysis (EDA), data visualization, and predictive modeling. By uncovering key insights and trends, this project provides a robust foundation for understanding the factors that influence real estate prices and offers a predictive model to assist stakeholders in making informed decisions.

---

## **Dataset**
**Source:** [Kaggle - House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)  
The dataset contains detailed information on housing attributes, such as the number of bedrooms, bathrooms, square footage, and price.

---

## **Key Features**
### 1. **Data Preprocessing**
   - Handled missing values and duplicates.
   - Addressed outliers and inconsistencies (e.g., extreme bedroom counts, invalid property details).
   - Created new features for enhanced analysis:
     - **Age**: Indicates property age.
     - **Renovated**: Binary indicator for renovated houses.
     - **Formatted Price**: Easier-to-interpret price display.

### 2. **Exploratory Data Analysis (EDA)**
   - Analyzed relationships between features (e.g., square footage, bedrooms) and price.
   - Identified correlations between attributes using heatmaps.
   - Insights:
     - Strong positive correlation between square footage and price.
     - Right-skewed price distribution indicating a few high-value homes.

### 3. **Data Visualization**
   - Line plots, histograms, and scatter plots were used to:
     - Show price trends by property age.
     - Display price distributions across various attributes (e.g., bedrooms, square footage).
     - Highlight correlations and outliers.

### 4. **Predictive Modeling**
   - Implemented a Linear Regression model:
     - Achieved **70.02% R-squared accuracy** on the test set.
   - Performance evaluation using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
   - Feature optimization attempts to enhance accuracy.

---

## **Visualizations**
### Key Examples:
1. **Average House Price by Age**  
   - Younger homes (<40 years) tend to have higher prices, averaging ~$530,000.
2. **Price vs. Square Footage**  
   - Positive relationship: Larger homes tend to cost more.
3. **Price Distribution**  
   - Most homes are valued between $200,000 and $600,000.

---

## **Project Workflow**
### 1. **Data Selection**
- Selected King County housing dataset from Kaggle.
- Dataset offers comprehensive details for effective analysis.

### 2. **Problem Statement**
- Goal: Predict house prices using features like bedrooms, bathrooms, square footage, and more.
- Objective: Develop a regression model for forecasting prices and identifying influential factors.

### 3. **Preprocessing Steps**
- Removed duplicates and invalid entries.
- Addressed missing values and outliers.
- Created derived features for deeper insights.

### 4. **Exploratory Data Analysis**
- Conducted correlation analysis.
- Uncovered patterns and trends impacting housing prices.

### 5. **Data Visualization**
- Used Seaborn and Matplotlib to create meaningful charts.
- Focused on price distributions, trends, and feature relationships.

### 6. **Predictive Modeling**
- Developed a linear regression model with 70% accuracy.
- Experimented with feature selection for optimization.

---

## **Results**
- **Key Influencing Factors**:  
  Square footage, house age, and number of bedrooms significantly affect prices.
- **Model Insights**:  
  Baseline Linear Regression Model: 70% accuracy. Further improvements possible with advanced machine learning models.

---

## **Technologies Used**
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Tools**: Jupyter Notebook, GitHub  

---

## **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/king-county-price-predictor.git
   cd king-county-price-predictor

pip install -r requirements.txt

jupyter notebook Housing_Market_Analytics_Workflow.ipynb


## **Future Work**
Explore advanced models (e.g., Random Forest, Gradient Boosting) to improve accuracy.
Incorporate additional features like neighborhood quality or proximity to amenities.
Deploy the model as a web application for real-time predictions.
