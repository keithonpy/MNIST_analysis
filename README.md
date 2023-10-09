# Handwritten digits analysis
In this repository, we trained the models on the classification of handwritten digits with MNIST dataset and compared their errors

**Data:**
* `Dataset/`: contain the MNIST data for the model training


**Machine learning models:**
* `ML_models/linear_regression.py`: Linear regression model
* `ML_models/svm.py`: Support Vector Machine
* `ML_models/softmax.py`: Softmax regression model
* `ML_models/feature.py`: Principal Component Analysis and cubic feature
* `ML_models/kernel.py`: Polynomial kernel and RBF kernel

**Neural Network:**
* `ML_nn/neural_nets.py`: self-developed fully-connected neural network
* `PyTorch_nn/nnet_fc.py`: Fully-connected neural network using PyTorch
* `PyTorch_nn/nnet_cnn.py`: Convolution neural network using PyTorch

**Two digits image Analysis**
* `twodigit_analysis/sample_images`: Sample images that have two digits
* `twodigit_analysis/mlp.py`: Fully-connected neural network using PyTorch
* `twodigit_analysis/conv.py`: Convolution neural network using PyTorch
