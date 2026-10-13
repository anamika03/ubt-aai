# Shared course data

All exercises and solutions use this single repository-level data directory.
Do not create separate `data` folders inside individual exercise directories.

The small CSV, pickle, and text datasets are stored directly here. Datasets managed by `torchvision` keep the directory layout expected by the library:

- `MNIST/` contains the shared, extracted MNIST files used by Exercises 6 and 9.
- `cifar-10-batches-py/` contains the shared, extracted CIFAR-10 files used by Exercise 7.

Downloaded archives are removed after successful extraction to avoid storing the same dataset twice.
`torchvision` validates the extracted files directly and therefore does not download them again.

The notebooks search upward from their current working directory until they find this directory.
They therefore work when Jupyter is started either in the repository root or in an individual exercise directory.
