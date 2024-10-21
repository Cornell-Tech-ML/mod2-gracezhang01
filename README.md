[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

## Training Results

### Simple Dataset
- **Hyperparameters**:
  - Points: 50
  - Hidden Layers: 2
  - Learning Rate: 0.1
  - Epochs: 500
  - Time Per Epoch: 0.032s
![Simple Dataset Training Loss](images/lloss.png)
![Simple Dataset Training Result](images/ltrainhist.png)
![Simple Dataset Training Log 1](images/llog3.png)
![Simple Dataset Training Log 2](images/llog2.png)
![Simple Dataset Training Log 3](images/llog1.png)

### Diag Dataset
- **Hyperparameters**:
  - Points: 50
  - Hidden Layers: 2
  - Learning Rate: 0.1
  - Epoches: 500
  - Time Per Epoch: 0.032s
![Diag Dataset Training Loss](images/dloss.png)
![Diag Dataset Training Result](images/dtrainhist.png)
![Diag Dataset Training Log 1](images/dlog3.png)
![Diag Dataset Training Log 2](images/dlog2.png)
![Diag Dataset Training Log 3](images/dlog1.png)

### Split Dataset
- **Hyperparameters**:
  - Points: 50
  - Hidden Layers: 6
  - Learning Rate: 0.1
  - Epoches: 1000
  - Time Per Epoch: 0.105s
![Split Dataset Training Loss](images/sploss.png)
![Split Dataset Training Result](images/splittrainhi.png)
![Split Dataset Training Log 1](images/splog1.png)
![Split Dataset Training Log 2](images/splog2.png)

### XOR Dataset
- **Hyperparameters**:
  - Points: 50
  - Hidden Layers: 9
  - Learning Rate: 0.1
  - Epoches: 1500
  - Time Per Epoch: 0.105s
![XOR Dataset Training Loss](images/xloss.png)
![XOR Dataset Training Result](images/xlosshist.png)
![XOR Dataset Training Log 1](images/xlog1.png)
![XOR Dataset Training Log 2](images/xlog2.png)
![XOR Dataset Training Log 3](images/xlog3.png)