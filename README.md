# This Model Was Created for My Deep Learning Unit 2nd Assignment
The assignment was created as a Kaggle competition. For this assignment, students were required me to perform a multi-label classificaion task.
10,000 images and caption data were provided to train and test our model. To complete this objective, BERT model was used to classify 
the text data and ResNet was used classify the image data.

Two different methods were explored to combine the output of BERT and ResNet. For the first method I combined the two output by simply
taking the weighted average from both models. For my second method, I tried to create an end-to-end model by concatenating the output form BERT and ResNet.
Pytorch was used for in experiments.

Based on my experiments, I concluded that training BERT together with ResNet resulted in a very deep and complex model. Infact, the model was 
very difficult to train and I failed to get a satisfactory result within a resasonable training time. Simply taking the weighted average 
of both BERT and ResNet models actually provided me with a significantly better result.

Overall, I was able to achieved 0.87 F1 score in the final Kaggle leaderboard. I was ranked 7th out of 215 participants.
<br><b>**Please note that only the model with the best result was provided in this Repo</b>.</br>
