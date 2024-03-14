# deep-learning-challenge
The purpose of this analysis is to evaluate the performance of a deep learning model created for Alphabet Soup, focusing on predicting the success of investment using various organizational data.

Results:

Data Preprocessing:

- Target Variable: "IS_SUCCESSFUL" indicates investment success.
- Feature Variables: All columns except "IS_SUCCESSFUL" are features for the model.
- Variables Removed: "EIN" and "NAME" columns were removed as they didn't influence success.

Compiling, Training, and Evaluating the Model:

- Neurons, Layers, and Activation Functions: The model used 80 neurons across three layers with 'relu' activation for rapid learning and effective handling of binary results.
- Target Model Performance: The highest accuracy achieved was 74%, slightly below the 75% target.
- Steps to Increase Model Performance:
- Adjusted layers and neurons.
- Tweaked epochs, settling on 350 for the final model.
- Lowered the cutoff value for classification.
- Experimented with various activation functions, with 'relu' showing the most success.
Summary:

The deep learning model showed promising results but fell short of the target accuracy. To potentially improve performance, a different model such as a gradient boosting classifier could be considered. Gradient boosting models often perform well with tabular data and can handle categorical variables effectively. Additionally, ensemble methods like random forests could be explored for their robustness and interpretability, providing valuable insights into the factors influencing investment success.
