# Datasets for "Physics-informed State-space Neural Networks for Transport Phenomena"

This repository contains the datasets used in the paper "Physics-informed State-space Neural Networks for Transport Phenomena".
The data is provided in the form of `.npz` files, which are compressed archives containing multiple arrays in the NumPy `.npy` format.

## Contents

- `tr_ch`: Training dataset for the heated channel.
- `te_ch`: Test dataset for the heated channel.
- `tr_loop`: Training dataset for the heated & cooled loop.
- `te_loop`: Test dataset for the heated & cooled loop.
- `inspect_datasets.ipynb`: A Jupyter notebook demonstrating how to load the data.

Note that the training/test split may differ from published.

## Usage

To use these datasets, you will need the following versions of Python and libraries installed on your system:

- Python 3.10.4
- NumPy 1.22.4
- Matplotlib 3.3.1 (needed for notebook plots)


## Citation

If you use these datasets in your research, please cite the following paper:

```
A. J. Dave, R. B. Vilim, "Physics-informed State-space Neural Networks for Transport Phenomena", accepted to Engineering Applications of Artificial Intelligence (2024), preprint: https://doi.org/10.48550/arXiv.2309.12211.
```

## License

This dataset is released under the CC0 policy.
Please see the LICENSE.md for full license details. 
