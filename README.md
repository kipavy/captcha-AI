# hCaptcha Solver

Project to solve hCaptcha challenges using machine learning and computer vision techniques. Work in progress.

## Dataset

The dataset used for training the model can be found in the [`data`](./data). directory. Each subdirectory corresponds to a label for the images. You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/aneeshtickoo/hcaptcha-dataset).

## Installation

Install the required Python packages:

```bash
pip install -e .
```

**Alternative (recommended if you have [uv](https://docs.astral.sh/uv/) installed):**

```bash
uv sync
```

### GPU Acceleration

To leverage GPU acceleration, you need to manually install Pytorch with the appropriate CUDA version (See [official Pytorch installation guide](https://pytorch.org/get-started/locally/)).
