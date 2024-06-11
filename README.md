# Online Shoppers Purchasing Intention Analysis

## Overview
This project aims to analyze the Online Shoppers Purchasing Intention Dataset from the UCI Machine Learning Repository. The analysis involves data preprocessing, feature engineering, model selection, evaluation, and visualization to predict online shopper purchasing intentions.

## Methodology

### Data Collection and Preprocessing
1. **Data Collection**: The dataset was collected from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset).
2. **Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables.
   - Scaling numerical features.

### Feature Engineering
- Selected features: `Administrative`, `BounceRates`, `Weekend`, etc.
- Used `VectorAssembler` to assemble features into a single vector for input into the models.

### Model Selection
- Four classification algorithms were chosen:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - Support Vector Machine (SVM)
- Each model was initialized with appropriate parameters and settings.

### Evaluation Metrics
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- Mean Absolute Error (MAE)

### Experimental Setup

#### Data Splitting
- The dataset was split into training and testing sets, typically using an 80-20 split.

#### Model Training
- The selected algorithms were trained on the training data.

#### Model Evaluation
- The trained models were evaluated on the testing data using the specified evaluation metrics.

### Results and Discussion
- The performance of each algorithm was assessed based on the evaluation metrics.
- Results were compared, and the strengths and weaknesses of each algorithm were discussed.
- Factors influencing the performance of the models were analyzed.

### Conclusion
- The study provided insights into the effectiveness of different classification algorithms in predicting online purchase intentions.
- Conclusions were drawn regarding the best-performing algorithm and its implications for e-commerce businesses.

### Future Work
- Potential areas for future research were identified, such as exploring additional features or experimenting with different algorithms.
- Addressing any limitations encountered in the study and proposing strategies for overcoming them in future research were discussed.

### Social, Ethical, Legal, and Professional Considerations
- Ethical considerations related to data privacy, fairness, and transparency in model predictions were discussed.
- Legal and regulatory frameworks governing the use of machine learning algorithms in decision-making processes were considered.
- The importance of adhering to professional standards and guidelines in conducting research and using machine learning technologies was emphasized.

## Tools and Technologies
- **PySpark**: Used for data preprocessing and feature engineering, offering scalability and efficiency for big data tasks.
- **scikit-learn**: Utilized for implementing and evaluating various classification algorithms.
- **Tableau**: Employed to create interactive and informative visualizations, aiding in understanding patterns, trends, and correlations within the dataset.

## How to Run the Project
1. Clone the repository.
2. Install the required dependencies.
3. Follow the steps outlined in the Jupyter Notebook or Python scripts to preprocess the data, train the models, and evaluate the results.

## Acknowledgements
- UCI Machine Learning Repository for providing the dataset.
- PySpark, scikit-learn, and Tableau communities for their invaluable tools and resources.

## License
This project is licensed under the MIT License.

---

Feel free to reach out for any questions or contributions!


