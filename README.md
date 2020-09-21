# tensorflow-hello

## Setup environment

### Install anaconda

```zsh
pyenv install anaconda3-2020.02
```

### Create Virtual Environment

```zsh
conda create -n py37_tensorflow python=3.7
```

### Install libraries

```zsh
conda install tensorflow=2.0 python=3.7
conda install tensorflow_datasets
pip install matplotlib
pip install numpy
pip install h5py pyyaml
pip install pillow

conda install -c conda-forge jupyterlab
```

### Jupyter Lab

```zsh
jupyter lab
```

## References

- [TensorFlow 2.3 のインストール](https://www.kkaneko.jp/tools/ubuntu/ubuntu_tensorflow2.html)
- [JupyterLabのすゝめ](https://qiita.com/kirikei/items/a1639954ce5ccaf7ac3c)
