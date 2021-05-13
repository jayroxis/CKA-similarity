# CKA-similarity
An PyTorch Implementation of CKA-similarity with CUDA support. 
Inspired by:
https://github.com/yuanli2333/CKA-Centered-Kernel-Alignment

The Centered Kernel Alignment (CKA) method is from paper: 

*Similarity of Neural Network Representations Revisited*. [https://arxiv.org/abs/1905.00414]

## Running time for the example notebook
Numpy: 3min 8s
PyTorch: 15.3s

For large matrices, use PyTorch with CUDA to accelerate.

# Dependencies
```
python3
numpy
gzip
torch
```

Tested environment: *PyTorch v1.7.0*, *Python 3.6.9*

