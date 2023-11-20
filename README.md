
# Neural Preset for Color Style Transfer

Neural Preset is a technique that addresses the limitations of existing color style transfer methods, including visual artifacts, memory requirements, and style switching speed. This repository contains the code for implementing Neural Preset for color style transfer using PyTorch.

## Overview

In this project, we present a Neural Preset technique that operates on each pixel consistently via an image-adaptive color mapping matrix, avoiding artifacts and supporting high-resolution inputs with a small memory footprint. Neural Preset uses a two-stage pipeline, dividing the task into color normalization and stylization, which allows efficient style switching by extracting color styles as presets and reusing them on normalized input images.

## Features

- Deterministic Neural Color Mapping (DNCM) for consistent color mapping.
- Two-stage pipeline for color normalization and stylization.
- Self-supervised training strategy for Neural Preset.
- Supports multiple applications without fine-tuning, including low-light image enhancement, underwater image correction, image dehazing, and image harmonization.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- PIL (Python Imaging Library)
- tqdm (optional for progress bars)

## Getting Started

To get started with this project, follow the steps below:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/neural-preset.git
   cd neural-preset
   ```

2. **Installation**

   Install the required dependencies using the provided `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

3. **Running the Notebook**

   Open the Jupyter Notebook containing the code and execute the cells. You can customize the code and dataset loading as needed.

4. **Results**

   After running the code, you can find the results and outputs within the notebook itself.

## Customization

You can customize the following aspects of the code to suit your specific needs:

- Model architecture and hyperparameters.
- Dataset loading and preprocessing.
- Loss functions and training procedures.

## Contributing

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

