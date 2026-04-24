# Computer Vision Laboratory Labs

This repository contains a collection of Jupyter Notebooks for the Computer Vision laboratory. The labs cover a wide range of topics, from basic image processing and data manipulation with PyTorch to advanced deep learning architectures for vision tasks.

## Overview

The labs are designed to provide hands-on experience with:
- **Basic Image Processing**: Thresholding, histograms, linear stretching, and Otsu's method.
- **Data Manipulation**: In-depth look at PyTorch tensors, indexing, and operations.
- **Convolutional Neural Networks**: Implementation of custom convolutions, transpose convolutions, and residual blocks.
- **Advanced Architectures**: VGG, Transformers, and Vision Transformers (ViT).
- **Computer Vision Operations**: Region of Interest (ROI) Pooling.
- **Datasets**: Training and evaluating models on datasets like MNIST.

## Requirements

- Python 3.12
- Conda (recommended for environment management)

## Setup

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Create the Conda environment**:
   The `torch.yml` file contains all the necessary dependencies.
   ```bash
   conda env create -f torch.yml
   ```

3. **Activate the environment**:
   ```bash
   conda activate torch
   ```

## Notebooks and Scripts

| Notebook | Description |
| --- | --- |
| `NN_MNIST.ipynb` | Neural Network implementation for MNIST digit classification. |
| `Transformer.ipynb` | Implementation of the Transformer architecture. |
| `VGG.ipynb` | Implementation and testing of the VGG network. |
| `lab_2dtransconv.ipynb` | Exploration of 2D Transpose Convolution logic and implementation. |
| `lab_ROI.ipynb` | Implementation of the ROI Pooling operator. |
| `lab_attention_ViT.ipynb` | Attention mechanisms and Vision Transformer (ViT) implementation. |
| `lab_conv.ipynb` | Fundamentals of data manipulation and convolution operations in PyTorch. |
| `lab_resblock.ipynb` | Implementation of Residual Blocks (ResBlocks). |
| `lab_thresh_hist.ipynb` | Image processing basics: Thresholding (Binary, Otsu), Linear Stretching, and Histograms. |

## Data

- `mnist_train.csv` & `mnist_test.csv`: MNIST dataset files.
- `lenna.jpg`: Standard test image for computer vision tasks.

## Project Structure

```text
.
├── NN_MNIST.ipynb
├── Transformer.ipynb
├── VGG.ipynb
├── lab_2dtransconv.ipynb
├── lab_ROI.ipynb
├── lab_attention_ViT.ipynb
├── lab_conv.ipynb
├── lab_resblock.ipynb
├── lab_thresh_hist.ipynb
├── lenna.jpg
├── mnist_test.csv
├── mnist_train.csv
└── torch.yml
```

## Environment Variables

No specific environment variables are required for these labs.

## Tests

There are no separate test scripts. Validation and testing are performed directly within each Jupyter Notebook through assertions, plots, and printed outputs.

## License

TODO: Add license information.
