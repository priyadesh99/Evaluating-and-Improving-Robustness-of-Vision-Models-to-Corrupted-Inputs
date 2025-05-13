# Evaluating and Improving Robustness of Vision Models to Corrupted Inputs

## Overview

This repository explores methods for measuring and enhancing the robustness of pretrained vision models (e.g., ResNet-18) when faced with common input corruptions. We leverage the CIFAR-10-C dataset to evaluate model performance across different corruption types and severities, and implement strategies such as mixed clean/noise fine-tuning, selective layer adaptation, and trasnfer learning.

## Notebooks Included 

* **Severity-Level Experiments**
  Notebook Titled: Training_Across_Sev_levels.ipynb
* **Noise-Type Experiments**
  Notebook Titled: Training_Across_Noise_Types.ipynb
  
* **Trasnfer Learning Experiments**
  Notebook Titled: transfer_learning.ipynb

## Steps to reproduce

Download notebook and run cells sequentially for all experiments. 

### Transfer learning notes

There are some comments in the notebook about loading and running models.

The models can be found at

https://drive.google.com/drive/folders/1qQbyTtch0jj42U7zDyNuLHkzQAgz-5p_

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
