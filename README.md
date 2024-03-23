
# Summary

The Predictive Model provides insights into the dataset variables, their meanings using linear regression.


## Tasks Overview:

### Task 2: Analysis of Car Dataset (`cars.csv`)

- **Feature Scaling:** Utilizes mean normalization to scale all features in the dataset and prints the first 5 values of each scaled feature along with their mean and variance.
- **Scatter Plot:** Generates a scatter plot of fuel economy (`mpg`) against scaled weight (`scaled_wt`) and provides an interpretation of the plot.
- **Linear Regression:** Learns a simple linear hypothesis to predict fuel economy (`mpg`) based on scaled weight (`scaled_wt`) using the gradient descent algorithm.
- **Overlaying Hypothesis:** Plots the learned linear hypothesis on the scatter plot and interprets the plot.
- **Multiple Linear Regression:** Learns a multiple linear regression hypothesis to predict fuel economy (`mpg`) based on all scaled features using the gradient descent algorithm.

### Task 3: Lung Cancer Prediction (`cancer.csv`)

- **Probability Modeling:** Learns the probability of lung cancer as a function of smoking status using the gradient descent algorithm.
- **Classification:** Classifies individuals into lung cancer categories based on learned probabilities, reports confusion matrix, and interprets results.
- **Statistical Inference:** Analyzes the likelihood of smokers having lung cancer compared to non-smokers.

### Task 4: Spam Email Detection (`emails.csv`)

- **Scatter Plot:** Creates a scatter plot of subject length against suspicious word count, labeling points by spam status, and interprets the plot.
- **Probability Modeling:** Learns the probability of an email being spam based on subject length and suspicious word count using the gradient descent algorithm.
- **Decision Boundary:** Plots the decision boundary corresponding to the learned hypothesis on the scatter plot and provides interpretation.
- **Classification:** Classifies emails into spam or non-spam categories based on learned probabilities, reports confusion matrix, and interprets results.

Each task's implementation follows a standardized approach, including parameter initialization, learning rate selection, and convergence criteria, ensuring consistency and reliability across analyses.

