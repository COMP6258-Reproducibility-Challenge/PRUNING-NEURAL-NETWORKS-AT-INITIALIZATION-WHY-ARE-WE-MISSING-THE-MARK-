## SynFlow on VGG16 on CIFAR10

In this SynFlow part of reproduction, 
the VGG16 model with BatchNorm is built by ourselves, 
with using the weights initialization part in the code of Tanaka et al. (2020). (https://github.com/ganguli-lab/Synaptic-Flow/blob/master/Models/lottery_vgg.py #Line63)
For the pruning method, the codes from Tanaka et al. (2020) GitHub repo are used with some fixes. 
In the training part, all codes are implemented by us.

GitHub of Tanaka et al. (2020): ganguli-lab/Synaptic-Flow: https://github.com/ganguli-lab/Synaptic-Flow

## Requirements

PyTorch >= 1.4.0

Torchvision >= 0.5.0

Torchbearer

GPU

## Trial

First, run the codes to define VGG16 model and load CIFAR10 dataset. Define dataloaders.

Second, tune sparse_ratio to specify the spasity. Then define the pruning method SynFlow.

Third, tune the booleans of reinitialize, shuffle, invert to specify ablation method during pruning.

Final, run the rest of codes to train pruned model and get results.

## Reference

[1] Frankle, Jonathan, et al. "Pruning neural networks at initialization: Why are we missing the mark?." arXiv preprint arXiv:2009.08576 (2020).

[2] Tanaka, Hidenori, et al. "Pruning neural networks without any data by iteratively conserving synaptic flow." Advances in neural information processing systems 33 (2020): 6377-6389.




