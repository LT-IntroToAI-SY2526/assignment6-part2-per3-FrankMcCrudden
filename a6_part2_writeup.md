# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Bedrooms
2. Bathrooms
3. Age
4. Least Important: SquareFeet

**Explanation:**
The most important has the highest coefficient and each decreasingly important has a lesser and lesser coefficient.



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each Squarefoot increases the price by $121.11.

**Feature 2:**
Each year of age drecreses the price by $950.35.

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My model's R2 score is 0.9936, with it being so close to 1, that meake me know that my model is very accurate at predicting house prices. There is n=some room for improvement, but a very small room for improvement.



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Number of floors.

**Why it would help:**
It would give more value to the height of the house.

**Feature 2:**
Kitchens

**Why it would help:**
It would give more value to the amount of appliences like a stovetop or oven to the price of the house.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
Most likely, the only issue with it's ability to predict is because there is no example close to 3000 SquareFeet, additionally no example uses 6 bedroom. Yet everything else would be good, so i would still trust the model to accuretly predict the price for the house.