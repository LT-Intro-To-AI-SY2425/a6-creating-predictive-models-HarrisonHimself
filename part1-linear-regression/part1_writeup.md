# Part 1 - Linear Regression Writeup

After completing `a6_part1.py` answer the following questions

## Questions to answer

1. What is the r squared value?  What does this say about this linear regression model?
The r-squared value is the correlation between the independent and dependent variable. If the model's r-squared value is closer to 1, the correlation between the variables is more closely related. If the value is closer to 0, there is less correlation between the variables.

2. According to your model, what is the predicted systolic blood pressure for a person who is 42 years old?
The predicted blood pressure for a 42 year old person is  136.5204 mmHg.

3. How accurate do you think this model's predictions are?  Do you think this model is accurate enough to reliably predict someone's blood pressure based on their age?  Why or why not?  And if not, what could improve the model?
I don't think this model is accurate, as it's r-squared value is only 0.626, meaning that the correlation between the data points is not very high. This model might be able to better predict someones blood pressure based on age if there was a very large data pool of data, that has little to no outlying data points that might skew the relationship between the two variables.