# mini-dnn-cpp
**mini-dnn-cpp** is a C++ demo of deep neural networks. It is implemented purely in C++, whose only dependency, Eigen, is header-only. 

## Usage

Linux
```shell
git clone https://github.com/ntp-shin/Cuda-Lenet5
cd Cuda-Lenet5
make setup
make run
```

Google Colab:
```shell
!git clone https://github.com/ntp-shin/Cuda-Lenet5
!cd Cuda-Lenet5 && make setup
!cd Cuda-Lenet5 && make run
```
Download: mode/*


Result: 
simple neural network with 3 FC layers can obtain `0.97+` accuracy on MNIST testset.
LeNet-like CNN can obtain `0.98+` accuracy on MNIST testset.
