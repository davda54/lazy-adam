# Lazy Adam optimizer (PyTorch)

The lazy Adam optimizer merges the [sparse](https://pytorch.org/docs/stable/optim.html?highlight=adam#torch.optim.SparseAdam) and [dense](https://pytorch.org/docs/stable/optim.html?highlight=adam#torch.optim.Adam) Adam optimizers from the PyTorch framework. The resulting functionality is similar to [tensorflow](https://www.tensorflow.org/addons/api_docs/python/tfa/optimizers/LazyAdam) — it **automatically chooses the right algorithm based on the sparsity** of the updated weight. 

As a result, you no longer have to keep track of two different optimizers that are updating distinct subsets of the parameters. It's a drop-in replacement of the existing optimizers :ok_hand:
