# Progressive Neural Networks for Quantum Architecture Search

Credit for original Progressive Neural Network code to [pnn](https://github.com/hengdashi/pnn).

## Setup

This code is tested under `python 3.7.7`, dependencies can be installed with:

```bash
pip install -r requirements.txt
```

`src/common/params.py` is the parameter setting file that documents all hyper-parameters used in the code.

Run the program with `python src/main.py` to begin the training process.

The default configuration utilizes ***16*** processes to accelerate the training process. No GPU is currently configured in the code. You could possibly move the PyTorch Tensors to GPU for training, but since the environments are rendered on CPU, this might not result in a better performance due to the CPU-GPU communication overhead.

