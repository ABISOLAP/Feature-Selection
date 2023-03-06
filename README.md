# Feature-Selection
Multi-colinearity: When two features project the same effect on the outcome variable i.e. avoiding duplicating of effect.  When you have two features in your data, they will have two different weight, where as misleading the model, that is the reason why we need to drop one. It is a situation in which two features impact the same influence on the outcome variable.
Feature selection is important to avoid two  features doing the same thing in the data e.g Promotion and doubling salary. To avoid dummy features i.e. features that are not contributing to prediction. To ensure a certain feature is not being disfunctional, constituting noise in the data.

N:B When regressing two features and the score is 0.8 or greater, that means their effect is identical then we drop one of them. Regressing a feature against itself is 1.

Select K best is a function that identifies n number of features in terms of ranking from highest to lowest(in terms of their importance to outcome variable). e.g. Select the best 4 features for me that predict my outcome i.e.  n=4.

Chi square is a scoring function. It is a computation of the test of significance of interaction between the two variables..

UNF (Univariate Feature Selection) : Take a feature at a time, take the outcome variable, measure relationship between feature and outcome, and put a score on it.
