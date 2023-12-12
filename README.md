# SETUP

```bash
conda create -n jax python=3.11
pip install -U "jax[cuda12_pip]" -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html
conda install jupyter
pip install tensorflow[and-cuda]
pip install tensorflow_datasets
pip install -r requirements.txt
conda install -c "nvidia/label/cuda-11.8.0" cuda-nvcc
```
