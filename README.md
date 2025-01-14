# Applied Data Science Capstone: SpaceX Launch Prediction and Analysis

This project demonstrates the application of data science techniques using the SpaceX launch dataset. The goal is to predict the success or failure of a SpaceX launch based on historical data, as well as to perform exploratory data analysis (EDA) and build an interactive dashboard to visualize the results.

## Project Overview

The project is structured into the following main components:

1. **Data Collection**: 
   - The SpaceX dataset is collected from various sources and APIs, containing details about the launches, rocket configurations, and success/failure outcomes.
   
2. **Exploratory Data Analysis (EDA)**:
   - Data cleaning and preprocessing are done to handle missing values, outliers, and inconsistencies.
   - Visualizations are created to explore relationships between variables and identify trends, such as launch success rates by rocket type or location.

3. **Predictive Modeling**:
   - Machine learning models, including Logistic Regression and Random Forest, are applied to predict the outcome of a launch.
   - The models are trained using historical data, with features like launch site, rocket type, and weather conditions, to predict the success or failure of future launches.

4. **Dashboard**:
   - An interactive web dashboard is built using Flask/Dash to allow users to interact with the data and visualize launch success predictions.
   - The dashboard includes charts, filters, and real-time predictions for upcoming launches.

## Tools & Technologies

- **Python**: For data manipulation, modeling, and analysis.
- **Jupyter Notebooks**: For performing data exploration, model building, and analysis.
- **Pandas & NumPy**: For data cleaning and manipulation.
- **Scikit-learn**: For machine learning model building.
- **Matplotlib & Seaborn**: For data visualization.
- **Flask/Dash**: For creating the interactive web dashboard.
- **SQL**: For querying structured data when necessary.

## Key Features

- **Data Preprocessing**: Handles missing values, removes duplicates, and standardizes the data for further analysis.
- **Exploratory Data Analysis (EDA)**: Analyzes the launch success/failure rate and the factors that influence the outcome.
- **Machine Learning Models**: Implements algorithms like Logistic Regression and Random Forest for predictive analysis of launch success.
- **Visualization**: Visualizes key metrics like launch success rates, success by rocket type, and other factors influencing launch outcomes.
- **Interactive Dashboard**: A user-friendly web application for visualizing and interacting with the data and predictions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shruthika-s/Applied-Data-Science-Capstone.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Applied-Data-Science-Capstone
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebooks or start the Flask/Dash dashboard:
   ```bash
   jupyter notebook
   ```

## Conclusion

This project is a comprehensive application of data science techniques, showcasing how to handle real-world datasets, perform exploratory data analysis, build machine learning models, and present results through an interactive dashboard. It provides insights into SpaceX launch performance and offers a predictive tool for future launches, reflecting my interest in data science applications in aerospace. The project emphasizes how data science can drive impactful decisions and innovations in the aerospace industry.
