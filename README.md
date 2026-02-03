# discount-calculator-python
python function that calculates discount and final price 

Overview
The apply_discount function calculates the final price of an item after applying a percentage discount.
It includes input validation to ensure the price and discount values are valid before performing the calculation.

🧠 How It Works
The function:
Checks that price is a number (int or float)
Ensures price is greater than 0
Checks that discount is a number (int or float)
Ensures discount is between 0 and 100
Calculates and returns the final discounted price
If any validation fails, an appropriate error message is returned instead of a number.

Example Usage
print(apply_discount(74.5, 20.0))

Output
59.6


Possible Error Messages
Condition Returned Message 
Price is not a number "The price should be a number"
Price ≤ 0 " The price should be greater than 0" 
Discount is not a number"The discount should be a number"
Discount < 0 or > 100 "The discount should be between 0 and 100"

