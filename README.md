
# Cropland-Classification
Comparing various ML techniques on Sentinel and Landsat data for analyzing cropland over Gujarat.


## Introduction
A comparison between machine learning algorithms on Sentinel-2 and Landsat satellite imagery for cropland extent categorization is made using the example of Gujarat state, India. The following three classifiers: Support Vector Machine (SVM), Classification and Regression Trees (CART), and Random Forest were employed to analyze the precision of the classifications on GEE. For Sentinel-2 data, SVM achieved a good level of overall accuracy of 98.05%, where manager and consumer accuracies are equal to (95.12-96.77)%. CART and Random Forest classifiers also showed high output accuracy of 96.11% and 98.05%, being nearly similar to SVMs about accuracy. Furthermore, for Landsat satellite data, the SVM classifier attained 98.05% overall accuracy with the rest of the classifiers; CART gained 96.11%, and Random Forest achieved 98.05% respectively. These findings demonstrate the superiority of machine learning algorithms in precisely classifying cropland from image satellite imagery, which in turn offers crucial information to the environment monitoring and land management applications in the area.
## Dataset
Sentinel-2 and Landsat-8, satellites, will be used for the classification process in this work, which will be based on cropland extent mapping in the Gujarat region. Satellites with such designated capabilities supply high-resolution imagery with multiple spectral bands, which leads to precise determination of land cover.
To begin, it is necessary to examine the effects of the pairing of bands which will show the difference in the structure of the image. Hence, they can be seen in a mix of the detectors of plant-based, soil, and ocean parameters. One of the significant advantages of remote sensing is that this technique exploits the differences between the types of land cover using a smart combination of sensors, thus giving much better results.

## Methodology

Support Vector Machine (SVM)
Classification and Regression Trees (CART)
Random Forest (RF)

## Results and Conclusion
|           |    SVM   |    CART   |    RF        |
| :-------- | :------- | :-------- | :----------|
| Landsat8  | 97.82 | 97.82 | 95.65 |
| Sentinel2 | 98.05 | 96.11 | 98.05 |

The overall accuracy of the sentinel-2 satellite by SVM classifier is 98.05%. The Producer accuracy of the sentinel-2 satellite by SVM classifier is 95.12% and 96.77%. The Consumer accuracy of the sentinel-2 satellite by SVM classifier is 95.12% and 96.77%. The overall accuracy of the sentinel-2 satellite by Cart classifier is 96.11%. The Producer accuracy of the sentinel-2 satellite by SVM classifier is 97.56% and 98.38%. The Consumer accuracy of the sentinel-2 satellite by SVM classifier is 97.56% and 98.38% The overall accuracy of the sentinel-2 satellite by Random Forest classifier is 98.05%. The Producer accuracy of the sentinel-2 satellite by SVM classifier is 97.56% and 98.38%. The Consumer accuracy of the sentinel-2 satellite by SVM classifier is 97.56% and 98.38%. The overall accuracy of the Landsat satellite by SVM classifier is 98.05%. The Producer accuracy of the Landsat satellite by SVM classifier is 98.60% and 96.42%. The Consumer accuracy of the Landsat satellite by SVM classifier is 94.73% and 95.90%. The overall accuracy of the Landsat satellite by Cart classifier is 96.11%. The Producer accuracy of the Landsat satellite by SVM classifier is 97.22% and 98.21%. The Consumer accuracy of the Landsat satellite by SVM classifier is 97.22% and 98.21%. The overall accuracy of the Landsat satellite by Random Forest classifier is 98.05%. The Producer accuracy of the Landsat satellite by SVM classifier is 94.44% and 96.42%. The Consumer accuracy of the Landsat satellite by SVM classifier is 94.44% and 94.42%.


## Google Earth Engine Codes
[Sentinel2-CART]( https://code.earthengine.google.com/2cc61b0e71cb7e53ded75ccaa3287d0f)

[Sentinel2-RF](https://code.earthengine.google.com/9e4f1443f10fe3f9f01354ee259005d8)

[Sentinel2-SVM](https://code.earthengine.google.com/b5683afcdb0efa19917ba705cfd34ef5)

[Landsat8-CART](https://code.earthengine.google.com/cc21533f7de51f61ee7fb972f2d8709d)

[Landsat8-RF](https://code.earthengine.google.com/2ce50b93aac3ca90a3452cefbe836e97)

[Landsat8-SVM](https://code.earthengine.google.com/11b68cf028ca72ddbd62985bd0a7b377)
