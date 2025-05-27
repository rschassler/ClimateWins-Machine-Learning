Introduction and Background:
Cimate Wins is interested in using machine learning to help predict the consequences of climate change around Europe and, potentially, the world. However, it’s hard to grasp how everything is changing in the world at once, so ClimateWins utilizes machine learning towards this end. It is concerning that there has been an increase in extreme weather events in mainland Europe--especially in the past 10 to 20 years—but with historical data on weather patterns, machine learning can be used to predict and plan  for adverse weather. 

Data: 
Data was collected by the European Climate Assessment & Data Set Project by compiling yearly  weather observations  from weather stations across mainland Europe. 
Dates in the total dataset  range from the 1800s up to 2022, with daily observations from 1960  to 2022.
Weather observation variables from each station includes temperature, wind speed,  precipitation, humidity, snowfall, and global radiation. 

Hypotheses:
1. Machine learning algorithms can be utilized to accurately predict weather conditions across mainland Europe.
2. Accuracy of predictions will vary between geographic locations, due to   climatological variables outside the scope of this analysis.
3. Machine learning results  can  support correlative factors in climate change, such as temperatures rising leading to greater  adverse weather conditions
   
Bias and Accuracy:
There is potential for temporal bias; data from earlier years  may be less accurate due to outdated collection methodology.
There is a potential for historical bias; with the large range in years collected, recent or more  acute changes may be overlooked in the algorithm.
There is a potential for selection bias;  data is collected from weather stations spread across a wide geographic range and may be over representative of  high population regions. 

Optimization:
First the dataset was scaled to diminish the effects of outlying data 
Gradient Descent function was used to optimize the data
Specifically, gradient descent method adjusts parameters  by testing  them towards converging on 0. The adjusting of the parameters allows for a more accurate  model because it reduces the loss function  over consecutive iterations
![image](https://github.com/user-attachments/assets/c0955165-5818-48fa-84e1-f14cdcb752d9)

Supervised Learning Algorithms used:
KNN--Makes predictions by calculating the distance between new data points and all other data points in the training set. Nearby data points are grouped based on the number of neighbors in each group.
Decision Tree--Makes predictions by answering a series of questions about the features of the data. The tree consists of nodes and branches in which new data points follow the flow of the tree based on its best fit.
ANN--Mimics the way the human brain processes information.  It consists of layers of interconnected "neurons" that learn patterns from data through training

Results:
The KNN model at 80% accuracy, performed the best in predicting days with pleasant vs. unpleasant weather. 
The ANN models were achieving around 50% and the decision tree model was around the same (about 47%). 
The controls of the ANN model should be further tested to train the accuracy to at least  90%. 






