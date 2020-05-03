This is my first deep learning basic linear model developed.

Tools used:

1. Jupyter Note Book

2. Python 3




First, I am generating a random data set from -10 to 10 and there are two inputs of dimensions 1000x1.

Then, I am setting a target function with reference to which the output y will be estimated.

After that, the weights are generated (also)randomly between -1 and 1 and taking the size as 2x1 as there are two inputs to the model. The bias is found with the size 1x1 according to convention.

Taking an arbitrary learning rate, I went on to update the weights and biases and achieve the least possible values for both, with the help of Gradient Descent optimization algorithm and the L-2 Norm loss function(since it is regression type problem), calculated per observation or the average(which indicates how close are the estimated output and the target output). We will stop when the iterating values will approximately stop to decrease further,i.e, the target and estimated outputs will come to a constant difference approximately. By the iteration, we are training our model according to our target function.

Then by plotting a target output vs estimated output graph, we can indicate how close are the two values to each other or in other words, the accuracy of the model. A line approximately inclined to 45 degrees indicates more accurate model.
