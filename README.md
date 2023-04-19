# Parameter_Optimization_SVM_UCS654
Assignment - 05

## Introduction
Support Vector Machine (SVM) is a popular machine learning algorithm used for classification and regression analysis that aims to find the optimal boundary between different classes or groups in the data. It is particularly useful when dealing with complex datasets that have multiple features, as it can effectively classify data points into different categories based on their features.

SVM has 3 important parameters: Kernel, C, and Gamma, which can be optimized to achieve a higher accuracy.

In this assignment, I have used a Fitness Function for Parameter Optimization

## Dataset
The dataset used for this assignment is the <ins>Dry Bean Dataset</ins> from UCI Library archives.
Link for dataset: [Click Here](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)

It has the following attributes:
1. Area (A): The area of a bean zone and the number of pixels within its boundaries.
2. Perimeter (P): Bean circumference is defined as the length of its border.
3. Major axis length (L): The distance between the ends of the longest line that can be drawn from a bean.
4. Minor axis length (l): The longest line that can be drawn from the bean while standing perpendicular to the main axis.
5. Aspect ratio (K): Defines the relationship between L and l.
6.  Eccentricity (Ec): Eccentricity of the ellipse having the same moments as the region.
7. Convex area (C): Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
8. Equivalent diameter (Ed): The diameter of a circle having the same area as a bean seed area.
9. Extent (Ex): The ratio of the pixels in the bounding box to the bean area.
10. Solidity (S): Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.
11. Roundness (R): Calculated with the following formula: (4piA)/(P^2)
12. Compactness (CO): Measures the roundness of an object: Ed/L
13. ShapeFactor1 (SF1)
14. ShapeFactor2 (SF2)
15. ShapeFactor3 (SF3)
16. ShapeFactor4 (SF4)
17. Class (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz and Sira) ~~TARGET

Number of Instances: 13611

## RESULT
![image](https://user-images.githubusercontent.com/100083614/233175620-a30a8a32-f221-4b3c-8992-d9742b75d1ab.png)
According to the above table, Linear Kernel with Nu=1.00 and Epsilon=4.39 gives the highest accuracy=0.68 for this dataset and given choice of kernels.

Here is a convergence graph corresponding to max accuracy=0.68
![image](https://user-images.githubusercontent.com/100083614/233176105-0262bf97-ffb9-4a16-9218-e36ea8eab320.png)

