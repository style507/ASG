# ASG


We test the deep learning aspect by implementing a four-layer DNN network, here we mainly implement the four-layer DNN training and prediction function.
We predict the data set by T public samples and R*B request samples, and then we get the result labels of the recorded predicted samples, so that the samples themselves can be compared with the predicted results by the main function to do a sample read and comparison functions. 
In order to determine the values of R and B, we test the two values and determine the final data to be used by testB.py. 
In the use data section we randomly sample the three datasets to request samples and open samples to determine the final number of samples to use.
We implement two different model extraction methods to steal the parameters of the trained model through extract1 and extract2 respectively, and then test whether the defense methods are effective.
