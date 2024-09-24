# Introduction
Predict if the upcoming value has a postive or negative sign "after a sequence of 9 values"

# Illustration
1) Training: We train a RNN model on +ve and -ve values
2) Input features: 1
3) Output targets: 1
   
# Model & Architecture
1) RNN DL Model
2) input_size = 1  # channels/features of data
3) num_hidden = 16 # breadth of model (number of hidden layers)
4) num_layers = 1  # depth of model   (number of stacks of hidden layers)
5) seqlength  = 9  # num of data points used for learning in each segment
6) batchsize  = 1  # number of batches of selength
7) actfun = 'tanh'
8) bias = True
12) Use of MSELoss
13) Minibatches = 32
14) SGD Optimizer with lr 0.001

# Results
1) Accuracy: Got 100% train & test accuracy
    
# Conclusions:
1) Results are very good for this simple task
