# Lazy Adam optimizer (PyTorch)

Merges the sparse and dense Adam optimizers from the PyTorch framework. The resulting functionality is similar to tensorflow — it automatically chooses the right algorithm based on the sprasity of the updated weight. 

As a result, you no longer have to keep track of two different optimizers that are updating distinct subsets of the parameters. It's a drop-in replacement of the existing optimizers :ok_hand:
