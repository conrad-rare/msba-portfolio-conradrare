## Individual Reflection

### What did l personally contribute the most?
I contributed most to the data preparation and model development stages of the project. I was responsible for cleaning and preprocessing the dataset, including handling missing values, encoding categorical variables, and ensuring the data was suitable for modeling. I also played a key role in building and training the XGBoost model, as well as evaluating its performance using appropriate metrics. My contributions ensured that the model was both accurate and reliable.

### What is one decision or approach l personally advocated for and why?
I advocated for using the XGBoost model over simpler models because of its ability to capture complex, nonlinear relationships in the data. I believed that customer churn behavior is influenced by multiple interacting factors and XGBoost’s boosting approach would better capture these patterns.
Additionaly, I applied manual hyperparameter tuning by adjusting key parameters such as learning rate, max depth, number of estimators and subsampling rates to improve model performance. 
While I did not use automated techniques such as GridSearchCV, I selected these values based on model performance and understanding of how XGBoost works. With more time, I would implement systematic hyperparameter tuning to further optimize the model.

### What are the lessons that l learnt from the case competition and what l would add or improve if l had more time?
One key lesson I learned was the importance of thorough data preprocessing, as the quality of the input data significantly impacts model performance. I also learned how critical it is to interpret model results clearly so that insights can be communicated effectively to stakeholders.
If I had more time, I would further strengthen the analysis by improving and fine-tuning the additional models I already implemented such as Random Forest and Logistic Regression, to better compare performance and validate the robustness of our results. I would also enhance the feature engineering process by creating more meaningful variables and refining existing ones. In addition, I would apply cross-validation and more systematic hyperparameter tuning to further improve model accuracy and reliability.




