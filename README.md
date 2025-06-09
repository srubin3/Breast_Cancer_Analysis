# Breast Cancer Analysis
This project analyzes the **Breast Cancer Wisconsin Diagnostic Dataset** to predict whether a tumor is *benign* or *malignant* using numerical features. 

The primary goal is to determine whether numerical features, such as mean radius, texture, and concavity, could effectively distinguish between benign and malignant tumors. Through a structured analytical approach, this project emphasizes **data cleaning**, **exploratory data analysis (EDA)**, and **visualizations** while building a logical narrative around the data. The analysis culminates in **predictive modeling** to test the hypothesis. 

Additionally, this project serves as an opportunity to expand the skills learned during my Fullstack Academy training by exploring advanced techniques such as **Principal Component Analysis (PCA)** and **machine learning** to derive meaningful insights. 

### Project Objectives
- **Develop a Logical Narrative**: Focus on writing clean, well-documented code and creating compelling visualizations to tell a coherant story about the data.
- **Refine Core Skills**: Practice and improve proficiency in data cleaning, EDA, and visualization techniques using Python libraries like Pandas, Matplotlib, Plotly, and Seaborn.
- **Explore Advanced Techniques**: Gain experience with PCA for dimensionality reduction and the machine learning test-train-split process to build predictive models.
- **Independent Learning**: Tackle a real-world dataset independently, from data preprocessing to model evaluation, to build confidence and problem-solving skills.

### Key Features
- **Data Cleaning**: Renamed columns for clarity, removed irrelevant features, converted diagnosis labels to binary (0 = Benign, 1 = Malignant), and addressed missing or duplicated data.
- **Exploratory Data Analysis**: Conducted analysis to understand feature distributions, correlations, and relationships with diagnosis, revealing key predictors like Mean Radius and Worst Concave Points.
- **Visualizations**: Created a variety of visualizations, including
  - Bar plots and histograms to show class distribution and feature ranges.
  - Box plots and violin plots to compare feature distributions by diagnosis.
  - Scatter plots and pair plots to explore feature interactions.
  - Correlation heatmaps to identify highly correlated features.
  - Interactive Plotly visualizations for dynamic exploration.
 - **Advanced Analysis**:
   -   Applied **PCA** to reduce 30 features to 2D and 3D representations, visualizing class separation and explained variance.
   -   Trained a **Logistic Regression Model** using a Test-Train-Split approach to predict tumor diagnosis.
-  **Model Performance**: Evaluated the model using metrics like accuracy, precision, recall, F1-score, and visualized results with a confusion matrix, ROC curve, and prediction probability distributions.

### Key Findings
- **Feature Importance**: Features like Mean Radius, Mean Area, and Worst Concave Points showed significant differences between benigns and malignant tumors, supporting their predictive power.
- **Class Separation**: PCA visualizations demonstrated clear clustering of benign and malignant samples, reinforcing the hypothesis that numerical features can distinguish tumor types.
- **Model Performance**: The Logistic Regression Model achieved high accuracy, but the small dataset size (n=569) led to *overfitting*, where the model learned noise rather than generalizable patterns. This highlights the need for larger datasets in future work.
- **Visualization Insights**: Visualizations, such as scatter plots and correlation heatmaps, provided intuitive insights into feature relationships, making complex data more accessible. 

### Challenges & Lesson Learned
- **Overfitting**: The small dataset size caused the model to overfit, emphasizing the importance of dataset size and model regularization techniques.
- **PCA Interpretation**: Learning to interpret principal components and their explained variance was a valuable introduction to dimensionality reduction.
- **Visualization Design**: Crafting clear and informative visualizations required balancing aesthetics with functionality, improving my ability to communicate data insights.
- **Independent Problem Solving**: Working indepdently pushed me to troubleshoot errors, research new techniques, and iterate on my approach.

### Future Improvements
- **Address Overfitting**: Experiment with techniques like cross-validations (such as L1/L2), or ensemble methods (such as Random Forest) to improve model generalization.
- **Expand Feature Engineering**: Explore additional feature transformations or interactions to enhance predictive power.
- **Larger Datasets**: Incorporate larger datasets to improve model robustness.
- **Interactive Dashboards**: Use Tableau or PowerBI to make visualizations more accessible to non-technical users.

### Work Cited: 
- Wolberg, William, et al. "Breast Cancer Wisconsin (Diagnostic)." UCI Machine Learning Repository, 1993, https://doi.org/10.24432/C5DW2B.
