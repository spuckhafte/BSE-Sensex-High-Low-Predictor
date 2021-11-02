# Sensex Predictor
1. You need to provide Opening Value in the function for further prediction
2. Predict High, Low and Closing values with accuracy*
3. Get graphs for comparison between the actual and predicted values

# Working
`high_low_close(___open, ___true_high=None, ___true_low=None, ___true_close=None, ___graph=False, ___dpi=1000)`\n
_\_\_\_open = Opening Value_

__Examples:__
1. `high_low_close(60000)`: __returns an array__ = _\[high_value, low_value, closing_value]_\n
2. `high_low_close(60000, 61200, 34444, 55555)`: __returns an array__ = _\[high_value, low_value, closing_value, error%]_\n
3. `high_low_close(60000, ___graph=True)`: __returns an array__ = _\[high_value, low_value, closing_value] and __Displays graph form of the predicted values and saves it on your working folder___\n
4. `high_low_close(60000, 61200, 34444, 55555, True)`: __returns an array__ = _\[high_value, low_value, closing_value, error%] and __Displays graph form of the predicted and actual values (comparing the 2) and saves it on your working folder___\n
 
 ___You can also change the \_\_\_dpi value for a high or low quality image respectively___

# Note
This project is entirely intended for research purposes! I’m just a student learning about Machine learning. Please don’t trust an algorithm as naïve as this!
