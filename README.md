## Installing PyTorch, TensorFlow, and JAX on Apple Silicon

Create a virtual environment and update pip:

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
```

### Install Torch:

```sh
pip install torch torchvision torchaudio
```

### Install TensorFlow:

```sh
pip install tensorflow tensorflow-macos tensorflow-metal
```

### Install JAX:

```sh
pip install jax-metal ml_dtypes==0.2.0 jax==0.4.26 jaxlib==0.4.26
```