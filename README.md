# tensor_flow_multiple_GPU

Multi-GPU Support
Keras makes it easy to use more than one GPU for neural network training or scoring. This tutorial shows how to train a model for the Cats vs Dogs dataset. Not all models will necessarily benefit from multiple GPUs. Generally larger batch sizes and more complex neural networks benefit from multiple GPUs.

The technique presented in this notebook can train with between 1 and 8 GPUs on a single host. It is also possable to train larger numbers of GPUs on multiple hosts; however, a slightly different approach is needed.

First, we will list what GPUs are available on the system.
