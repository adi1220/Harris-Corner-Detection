# Harris-Corner-Detection
A corner can be located by following these steps:

1. Calculate the gradient for a small window of the image, using sobel-x and sobel-y operators (without applying binary thesholding).
2. Use vector addition to calculate the magnitude and direction of the total gradient from these two values.
                       
![](Images%20Used/vector-addition.png)
:--:
*vector addition*

3. Apply this calculation as you slide the window across the image, calculating the gradient of each window. When a big variation in the direction & magnitude of the gradient has been detected - a corner has been found!


## Function And Parameters : 
for corner detection opencv's (cornerHarris()) feature is used with parameters being [float image , window size , sobel operators size,constant]

## Documentation :
for documnetation you can refer [here](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_features_harris/py_features_harris.html)
