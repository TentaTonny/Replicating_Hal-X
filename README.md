# Reproducing Hierarchical Agglomerative Learning (HAL)
Package for performing clustering for high-dimensional data. This packages uses heavily scikit-learn and FFT accelerated t-SNE.


# Running The Tests 

```
conda create -n reckless python=3.8
conda activate reckless

pip install python-dateutil importlib-metadata scikit-learn pandas numba pynndescent fdc umap-learn fitsne cython scipy numpy matplotlib jupyter

sudo apt-get install libfftw3-dev
pip install -c conda-forge fit-sne

conda config --add channels conda-forge
conda install cython numpy fftw scipy

```
