# Credit_Risk_Analysis

## Results

> For the Random Oversampling the Balanced Accuracy Score is 0.6620175698580149, as for the high risk performance the precision is 0.01 which is low and recall is 0.72 which is also good. low risk performance assesment for percision is 1.00 (perfect) and reacall is 0.60

### SMOTE

* Balanced Accuracy Score: 0.6620175698580149

high risk performance:

* precision is very low: 0.01

* recall is good: 0.63

Low risk performance:

* precision is perfect: 1.00
* recall is good: 0.69

### Cluster Centroid

Balanced Accuracy Score: 0.6195656115160086

> high risk performance:
precision is 0.01
recall is  0.61

> low risk performance:
 precision is  1.00
 recall is  0.42

### Smoteen

>Balanced Accuracy Score: 0.6400726134353378 

high risk performance:

>precision is low (0.01)
>recall is great (0.70)

low risk performance:
>precision is perfect (1.00)
>recall is fair (0.57?

### Balanced Random Forest Classifier

Balanced Accuracy Score: 0.7877672625306695

>high risk performance:

precision is low (0.04)
recall is good (0.67)

>low risk performance:

precision is perfect (1.00)
recall is great (0.91)

### Easy Ensemble Classifier

Balanced Accuracy Score: 0.925427358175101

>high risk performance:

precision is low (0.09)
recall is great (0.92)

>low risk performance:

precision is perfect (1.00)
recall is great (0.93)

### Summary
> The F1 score can be characterized as a single summary statistic of precision and sensitivity(recall). Given this, the F1 score is a great measurement to gauge model performance. Based on F1 scores the best forming model is the Easy Ensemble Classifier with an average F1 score of 0.97. While the worst performing is Cluster Centroid with an average F1 score of 0.59. Based on performance the Easy Ensemble Classifier model is greatly recommended for assessing credit risk.