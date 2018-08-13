# Brest-Cancer-Analysis-using-WEKA-Tool
Data mining is a process of analyzing data from different perspectives and summarizing it into useful information.
This paper illustrates comparative study of different data mining techniques like Apriori, Naïve Bayes classifier, this study helps us to decide the best subset for data analysis. Subsets are generated both in wrapper method and by ranking algorithm. Data set is divided into test and training sets thus comparing the results of both cases. This can be achieved by using WEKA (Waikato Environment for Knowledge Analysis) which is a workbench that contains a collection of visualization tools and algorithms for data analysis and predictive modeling on a data set.


In the project, Weka is used to diagnose cancer Wisconsin dataset. To be consistent , 16 instances with missing values are removed from the dataset to construct a new dataset with 683 instances.
Brief information from the UC Irvine machine learning repository:
Located in breast-cancer-Wisconsin sub-directory, filenames root: breast-cancer-Wisconsin.
1.	Currently contains 699 instances.
2.	2 classes (malignant and benign).
3.	9 integer-valued attributes.



Observation:
On observing the performance measures like F-measure, precision and recall, we can see that for the feature vector containing the best suited attributes for classification give better performance measures than those with random attributes in the feature vector. We can also see that this is the case in both the sets, training and test.

3.	Association Rule Mining (Apriori)
•	Find all frequent item sets: each of these item sets will occur at least as frequently as predetermined minimum support count (Apriori Algorithm).
•	Generate strong association rules from the item sets: The rules must satisfy minimum support and confidence. These rules are called Strong Rules.

On observing the performance measures like F-measure, precision and recall, we can see that for the feature vector containing the best suited attributes for classification give better performance measures than those with random attributes in the feature vector. We can also see that this is the case in both the sets, training and test.


Filter Method
1.	Use an attribute evaluator and a ranker to rank all the features in your dataset
2.	The number of features to be selected from the feature set can always be defined
3.	Omit the feature one at a time that have lower ranks and see the predictive accuracy of the classification algorithm.
4.	Weights put by the ranker algorithms are different than those by the classification algorithm


				
CONCLUSION

On comparing Naives Bayes classification for Ranking and Best Fit, omission of too many lower ranked attributes will result in over fit. Hence, only up to a certain percentage of inconsistency is allowed. The performance measures Precision, F-Measure and Recall of Naives Bayes classification has improved as a result of Feature Selection.

