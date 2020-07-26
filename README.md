# Machine_Learning_Challenge
## Written Analysis

The precision score seeks to answer the question of “What proportion of positive identifications was actually correct?” This questions is answered by dividing the number of true positives by the number of all the positives. The recall score seeks to answer “What proportion of actual positives was identified correctly?” This is answered by dividing the number of true positives by the total of the true positives and the false negatives. 
  
The balanced accuracy score is a way to asses how good the binary classifier is. It is especially useful when sample sets are imbalanced. The equations of balanced accuracy is the number of true positives and the number of false positives added together and then divided by two. It is a good tool for these situations but just like the accuracy score it is not the only metric to focus on.
  
The best performing model was the naive oversampling model. It produced a balanced accuracy score of .65, which was the highest of ll the models. Its average recall rate was 66 which was the highest of all the models which means it is more sensitive to others. All the models had a difficult time with precision when predicting the high risk target. So I would recommend the naive random oversampling as the model that will best suite our needs. 
