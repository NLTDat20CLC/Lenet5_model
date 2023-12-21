# mini-dnn-cpp
**mini-dnn-cpp** is a C++ demo of deep neural networks. It is implemented purely in C++, whose only dependency, Eigen, is header-only. 

## Usage
Download and unzip [fashionMNIST](https://github.com/zalandoresearch/fashion-mnist) dataset in `Lenet5_PP/data/mnist/`.

```shell
#using google colab
%cd Lenet5_PP
!mkdir build
%cd build
!cmake ..
!make
```

Run `./demo`.

Result: 
simple neural network with 3 FC layers can obtain `0.97+` accuracy on MNIST testset.
LeNet-like CNN can obtain `0.98+` accuracy on MNIST testset.
