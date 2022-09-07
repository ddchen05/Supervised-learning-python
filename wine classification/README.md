# Wine quality classification using different supervised learning algorithms
This repository demonstrates the implemention and optimization of several supervised learning algorithms towards the wine dataset to classify wine quality. Five supervised learning algorithms, including decision trees, neural networks, boosting, support vector machines, and K-nearest neighbors have been implemented. The  performance of different algorithms are compared. 
## Data introduction
The wine dataset used for this analysis includes the first 2200 instances of the data downloaded from https://www.openml.org/d/1185. This data uses chemical analysis of wines grown in the same region to classify three types of wines. The dataset has 13 attributes.  A sample of the dataset is shown below.
|index|class|Alcohol|Malic\_acid|Ash|Alcalinity\_of_ash|Magnesium|Total\_phenols|Flavanoids|Nonflavanoid\_phenols|Proanthocyanins|Color\_intensity|Hue|OD280%2FOD315\_of_diluted_wines|Proline|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|1276|1|12\.102024|1\.978243|2\.206944|16\.830709|90\.91818|3\.175905|3\.286019|0\.313303|1\.742839|8\.531437|1\.053424|2\.776765|1195\.569148|
|1446|3|13\.57233|2\.542908|2\.696846|23\.484424|99\.259132|1\.674558|2\.595252|0\.421765|1\.12974|8\.589199|0\.887106|2\.344734|549\.436133|
|335|1|14\.340415|1\.924594|2\.524905|14\.91331|120\.34598|3\.247975|2\.851522|0\.265849|1\.259319|10\.056588|0\.893063|2\.10183|1207\.292428|
|1458|3|13\.157149|1\.59526|1\.956307|20\.726283|90\.66267|2\.675248|1\.513338|0\.598651|3\.084097|4\.978823|0\.982451|1\.355483|625\.185784|
|2038|1|13\.014567|1\.771221|1\.87766|14\.545069|93\.27238|2\.288577|0\.558747|0\.350538|1\.958462|4\.528011|1\.019395|3\.077627|1208\.63177|
|1314|3|12\.331843|3\.215488|2\.72125|24\.354064|108\.370083|2\.960632|0\.571487|0\.565|1\.59368|10\.216497|0\.623675|2\.429772|881\.61993|
|389|1|14\.142197|2\.039219|2\.236748|17\.509961|103\.760235|2\.825525|3\.912876|0\.298394|1\.832097|5\.950905|1\.047704|2\.097227|1079\.104998|
|1639|3|12\.425975|2\.294901|2\.924798|20\.858693|100\.67721|1\.81499|2\.762398|0\.306179|1\.143092|9\.920537|0\.597982|2\.141342|838\.086048|
|2004|3|12\.74562|4\.072534|2\.415821|21\.417589|100\.328676|1\.861831|4\.243816|0\.317223|2\.608496|8\.036917|0\.614371|1\.561459|563\.890107|
|403|3|14\.12093|2\.972|1\.974538|22\.460124|99\.29783|1\.482434|0\.499428|0\.619503|1\.283445|9\.515219|0\.629635|1\.438051|509\.489705|

## Methodology
The dataset is divided into two subsets. 60% of the original dataset is training data and the rest is testing data. The split is completed by using train_test_split() from the scikit-learn(Sklearn) library. The Sklearn library is then used to implement the 5 algorithms on the training data. The model performance against individual hyperparameters is evaluated via 5-fold cross-validation. Hyperparameters are then tuned by grid search and cross-validation to optimize the model architecture 
and increase the model performance.

## Summary
The best accuracy of the 5 classifiers were compared in table below. The 5 algorithms all have good accuracy for the wine dataset.kNN has the best performance, with the highest accuracy and shortest training time.

![2](https://user-images.githubusercontent.com/50339450/167273452-d3ff42f9-70d3-4d47-9e4a-3b43da9886cf.png)


