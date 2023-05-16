# PRUNING-NEURAL-NETWORKS-AT-INITIALIZATION-WHY-ARE-WE-MISSING-THE-MARK

## Members

- Tunchanok Ngamsaowaros   tn1u22@soton.ac.uk

- Pooja Vijayakumar        pv1n21@soton.ac.uk

- Juran Guo                jg4n22@soton.ac.uk

## Overview

In this work, works of <a href="https://arxiv.org/abs/2205.09328" target="_blank">Pruning Neural Networks at Initialization: Why are We Missing the Mark?</a> are reproduced. Three pruning methods on VGG16 and VGG19 respectively on CIFAR10 (GraSP: , SNIP: , SynFlow: `trials/synflow`) are implemented. The results are the same as the original paper.

## How to Run

### Requirements

PyTorch >= 1.4.0

Torchvision >= 0.5.0

Torchbearer

GPU (if available, suggest)

### Run each trial

Simply access to `/GraSP` or `/SNIP` or `/synflow` in `trials/`, then follow the instructions. All codes are inside.

## Reference

[1] Frankle, Jonathan, et al. "Pruning neural networks at initialization: Why are we missing the mark?." arXiv preprint arXiv:2009.08576 (2020). https://doi.org/10.48550/arXiv.2009.08576

[2] Tanaka, Hidenori, et al. "Pruning neural networks without any data by iteratively conserving synaptic flow." Advances in neural information processing systems 33 (2020): 6377-6389. https://doi.org/10.48550/arXiv.2006.05467

## Link

[1] ganguli-lab/Synaptic-Flow: https://github.com/ganguli-lab/Synaptic-Flow



