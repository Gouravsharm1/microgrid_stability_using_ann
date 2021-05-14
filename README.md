# 
We made the Artificial Neural Network and tried some different architectures to arrive at best results.
As we have to predict stability, where the output is binary ('0' for 'unstable', '1' for 'stable'), we chose 'sigmoid' as activation for the output layer.
 
We used the ‘accuracy’ as assessment for fitting of the neural network. KFold is the cross-validation engine selected, and 10 different validation sets were utilized to fit the model.


