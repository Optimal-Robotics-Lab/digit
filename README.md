# Digit DRL:

## 🚧 Warning 🚧
This repository is a work in progress, will be broken, and most likely significantly change. I would not recommend relying on this repository.

# Installation

Follow these steps to set up your environment.

### System Dependencies

First, ensure you have a recent version of Python3 (recommended Python3.12 or Python3.13) and the development headers installed, which are required by some packages.

For Debian/Ubuntu:
```bash
    sudo apt update
    sudo apt install python3.12-dev
```

### Virtual Environment

Create and activate a Python virtual environment to isolate the project's dependencies.

```bash
# Create and activate the environment
python3.12 -m venv env
source env/bin/activate
```

### Python Packages

A list of the required depenencies are as follows: (These are also provided in the requirements.txt)
```
jax[cuda12]
mujoco
mujoco-mjx
flax
optax
brax
distrax
orbax-checkpoint
wandb
```

To install the dependencies:
```bash
# First, upgrade pip
pip install --upgrade pip

# Then, install dependencies from the requirements file
pip install -r requirements.txt
```