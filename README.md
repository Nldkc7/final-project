# final-project
Graph1 ![BMIgraph](https://user-images.githubusercontent.com/92611961/165203316-789b8345-fdf9-4212-8fea-0b685dd0ba8c.png)
The above graph compares the occurences of different types of diabetes with average BMI and standard deviation. 0=no diabetes, 1= diabetes 1, and 2=diabetes 2
Graph2 ![HighBloodPressure](https://user-images.githubusercontent.com/92611961/165203479-b14096dc-3b11-48e6-b445-81b8b7f67484.png)
This graph correlates the types of diabetes with the occurences of High blood pressure. a score of 1 is 100% and a score of .7 is 70% occurence.
Graph3 ![Highcholoesterol](https://user-images.githubusercontent.com/92611961/165203491-cd35b045-0e2c-4b1f-8958-dd20aa92b1fd.png)
This graph correlates the type of diabetes with the occurences of High cholesterol. A score of 1 is 100% and a score of .7 is 70% occurence.
dataset [diabetes_012_health_indicators_BRFSS2015.csv](https://github.com/Nldkc7/final-project/files/8559088/diabetes_012_health_indicators_BRFSS2015.csv)
The type of diabetes has many strong indicators in lifestyle and physiology that can be collectively used to predict whether or not someone likely has diabetes. 
This info could be used to inform doctors on whether or not to screen for the illness.
So far High Blood Pressure and High Cholesterol occurence is much higher in diabetics than in those without diabetes.
Additionally both forms of Diabetes is associated with higher average BMI when compared with non diabetic people.
Part2
![image](https://user-images.githubusercontent.com/92611961/166848076-2628aa83-6370-4573-afd3-c142eabd10ed.png)
The distribution is heavily skewed towards those without diabetes and skewed against those with pre diabetes (diabetes_012 score of 1). 
Some other notable statistics are the fact that diabetes 1&2 have higher BMIs, less education, less income, higher age on average.
decision tree accuracy= 0.7811415957111322
linear regression accuracy= 0.15346014611882208
decision tree accuracy vs %train:

![image](https://user-images.githubusercontent.com/92611961/166849040-7bc5b4c7-3a3a-456c-a989-5fe7a2a289dd.png)

This graph consistently showed decrease accuracy as % train goes up

linear regression accuracy vs %train:

![image](https://user-images.githubusercontent.com/92611961/166849094-bc3fba21-f422-4ec5-bf7b-da47b3674fbc.png)

This plot had high variability in its accuracy with train%

residules library regression:

![image](https://user-images.githubusercontent.com/92611961/166849215-c056e6be-022d-4feb-9472-2acf56104390.png)

This plot shows that the majority of the distribution of the regression plot fell at or above 0 whith a minority distribution well below 0. The minority may be the diabetic diagnosed people. And the majority the non diabetics.

![image](https://user-images.githubusercontent.com/92611961/166849516-75b6aa62-fc90-490c-bf0b-04113ef817cd.png)

This is plot_tree of a small portion of the columns in the data set, the reason for this choice is difficulties finding a plot that would fit the decision tree classifier fit I was using. It was simply too big to include all the columns or even most of the columns. I tried another method of visualization but it wasnt much better. I searched for a couple of hours and had a hard time finding alternatives to decision tree classification visualization.

In regards to whether or not linear regression or decision tree classifier would be better for this data set. I think it is clear not only from the substantially increased accuracy of the decision tree classifier, but also the fact that decision tree classifiers are designed more for classification data sets when compared to regression
