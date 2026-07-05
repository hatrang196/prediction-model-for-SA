# prediction-model-for-SA

**Survival Analysis**, also known as time-to-event data analysis, is a branch of statistics and data science that focuses on modeling the time elapsed from a defined starting point until the occurrence of an event of interest. A defining characteristic of this type of data is the presence of censoring, which prevents traditional regression methods from being applied directly.

This thesis focuses on studying and evaluating three widely used predictive models: the semi-parametric Cox Proportional Hazards (Cox PH) model, the parametric Accelerated Failure Time (AFT) model, and the non-parametric machine learning-based Random Survival Forest (RSF) model. Each model reflects a different approach to the underlying data assumptions, ranging from the interpretability of hazard coefficients to the ability to capture complex non-linear relationships.

In addition to the theoretical foundations, this thesis develops a complete survival data analysis pipeline based on empirical datasets, consisting of the following steps:

- Data preprocessing: Handling missing values and standardizing feature variables.
- Descriptive statistical analysis: Using the Kaplan-Meier estimator to estimate the overall survival function.
- Model training: Applying the Cox PH, AFT, and RSF models to the dataset.
- Evaluation and comparison: Using the Concordance Index (C-index) and testing the proportional hazards assumption to assess the predictive performance of each method.
  
The experimental results provide an objective view of the strengths and limitations of each model under real-world data conditions, thereby offering a basis for selecting appropriate methods for time-to-event data analysis problems.
