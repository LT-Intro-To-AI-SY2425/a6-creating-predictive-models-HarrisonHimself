# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
Commenting this out caused the score to decrease slightly, from 0.88 to 0.71. This is likely because the StandardScaler preprocesses the data to make it more accurate.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The model is more accurate with the StandardScaler than without it. This model is quite accurate, with a score of 0.88, which somewhat close to 1.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
 I noticed that at about 0.79, the model was more likely innacurate. However, overall the model is somewhat accurate

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
She would not.
