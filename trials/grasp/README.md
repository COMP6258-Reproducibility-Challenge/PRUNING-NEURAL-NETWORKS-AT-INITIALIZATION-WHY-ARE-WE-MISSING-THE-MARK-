## Instruction

This trial is about GraSP pruning method on VGG16 on CIFAR10. Please tune the parameters: `sparse_ratio`, `random_shuffling`, `reint` (for reinitialization), `prune_type` (for inversion) to explore how the pruned models perform.

The GraSP pruning function is implemented by following the pseudocode and hyperparameters provided by Wang et al. (2020) and its GitHub repo alecwangcq/GraSP: https://github.com/alecwangcq/GraSP.

## Reference

[1] Wang, Chaoqi, Guodong Zhang, and Roger Grosse. "Picking winning tickets before training by preserving gradient flow." arXiv preprint arXiv:2002.07376 (2020).
