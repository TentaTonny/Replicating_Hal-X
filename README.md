# Reproducing Hierarchical Agglomerative Learning (HAL)


# Setup

```
conda create -n reckless python=3.8
conda activate reckless

pip install python-dateutil importlib-metadata scikit-learn pandas numba pynndescent fdc umap-learn fitsne cython scipy numpy matplotlib jupyter

sudo apt-get install libfftw3-dev
pip install -c conda-forge fit-sne

conda config --add channels conda-forge
conda install cython numpy fftw scipy

```

# Benchmarking

benchmarking code is provided in the designated benchmarking_hal-x.ipynb notebook
