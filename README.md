# Automating-ML-using-PyCaretaret

PyCaret helps in building end to end machine learning pipelines.

Earlier we used to spend so much time cleaning the data:
- Removing the outliers
- Transforming the catagorical variables

Then we tend to build the model.

Try out different models to solve the same problem.

Then identify which is the best performing model for the given underlying data.

Followed by picking the best model. 

Identify the hyperparameter 

Then tune them in order to identify the best parameters which fit in

Which improves our expected performance of the model. And THEN we finally save it as a pickle file.



##### Most of these tasks that we do it on a regular basis are kind of automated by builtin functions by using this PYCARET LIBRARY.


### Shaply

Shapley (SHAP - SHapley Additive exPlanations) is a method used in machine learning for explaining the predictions made by complex models.

Shapley values are used to quantify the contribution of each feature to a specific prediction by considering all possible combinations of features and their effects on the prediction.

Provisions of SHAP:

1. Local Explanations: SHAP provides individual feature attributions for each prediction, offering insights into why a model made a particular decision for a specific instance.

2. Consistency: SHAP values ensure that the sum of feature attributions for any instance equals the model's output for that instance. This property ensures that the model's prediction is accurately explained by the contributions of its features.

3. Model Agnostic: SHAP is model-agnostic, meaning it can be used to explain the predictions of any black-box model, such as tree-based models, neural networks, support vector machines, etc.

4. Global Insights: Besides local explanations, SHAP can also provide insights into feature importance at a global level, indicating which features have a higher overall impact on the model's predictions.

5. Handling Feature Interactions: SHAP accounts for interactions between features when attributing the model's output to individual features.

SHAP values are particularly useful in understanding complex models and gaining trust in their decision-making process.
