Date: 1/28/2026
Author: Tom Crookes



The following project utilizes image classification datasets (MNIST, CIFAR-10, CIFAR-100).

The model consists of 2D convolution layer (conv2d) followed by layers of depth-wise convolution to reduce train time, reduce parameters and improve efficiency. In total, the model has approx. 257,000 parameters and has obtained results of 98% accuracy of the MNIST dataset, 81% accuracy of the Cifar10 dataset. Train\Test\Validation split has been 60/10/30.

Image Classification Tasks (Epochs):   5|       10|         15| 
    
    Dataset:                            |         |         - |
    MNIST Datset                    ~98%|       -%|         -%|
    Cifar10 Dataset                 ~62%|     ~65%|       ~81%|             **Reduce overfitting and increase broad convolution to improve accuracy
    Cifar100 Dataset              50:|                                      + 2* FC (5000, 1000)
    HAGRID Dataset                    -%|       -%|         -%|

    