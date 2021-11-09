Brief Review


Count or Frequency Encoding: <br>
In count encoding we replace the categories by the count of the observations that show that category in the dataset by the frequency -or percentage- of observations in the dataset. These techniques capture the representation of each label in a dataset, but the encoding may not necessarily be predictive of the outcome. The assumption of this technique is that the number observations shown by each variable is somewhat informative of the predictive power of the category.

Engineering Rare Categories: <br>
Rare values are categories within a categorical variable that are present only in a small percentage of the observations. There is no rule of thumb to determine how small is a small percentage, but typically, any value below 5 % can be considered rare.

Integer Encoding: <br>
The numbers are assigned arbitrarily. This encoding method allows for quick benchmarking of machine learning models

One Hot Encoding: <br>
One hot encoding consists of encoding each categorical variable with different boolean variables -- dummies, which take values 0 or 1, indicating if a category is present in an observation.

One Hot Encoding of Frequent Categories: <br>
OHE of frequent or top categories is equivalent to grouping all the remaining categories under a new category.

Target Guided Encodings (TGE): <br>
guided by the target,
creates a monotonic relationship between the variable and the target.

Mean Encoding or Target Encoding: <br>
Mean encoding implies replacing the category with the average target value for that category.

Probability Ratio Encoding: <br>
This encoding is suitable for classification problems only, where the target is binary.
For each category, calculate the mean of target=1, that is the probability of the target being 1 ( P(1) ), and the probability of the target=0 ( P(0) ). And then, calculate the ratio P(1)/P(0), and replace the categories with that ratio.

Weight of evidence: <br>
Weight of Evidence (WoE) was developed primarily for the credit and financial industries to help build more predictive models to evaluate the risk of loan default. That is, to predict how likely the money lent to a person or institution is to be lost. Thus, the Weight of Evidence is a measure of the "strength” of a grouping technique to separate good and bad risk (default).
