# IVP – Comparison of CNN Architectures

The project focuses on the comparison of well-known Convolutional Neural Network (CNN) architectures in terms of design and performance.

---

##  Project Overview

We analyze and compare three classic CNN architectures:

-  **LeNet** – a lightweight network for digit recognition
-  **AlexNet** – the ImageNet-winning architecture that introduced ReLU and dropout
-  **VGGNet** – a deeper, modular design using 3x3 convolutions

Each architecture is studied with respect to:
- Number and type of layers
- Filter sizes
- Activation functions
- Total parameters
- Pooling and dropout strategies

---

##  Files

- `ivp_cnns_lenet_alexnet_vgg.ipynb` – Main notebook with architectural analysis, comparison tables, and performance discussion.

---

## Tools Used

- Python
- Jupyter Notebook
- Possibly Keras or PyTorch (if implementations are included)
- Markdown for documentation

---

## 📊 Summary

| Model   | Layers               | Activation | Params | Pooling | Dropout |
|---------|----------------------|------------|--------|---------|---------|
| LeNet   | 2 conv, 2 FC         | Sigmoid    | ~2.6K  | None    | No      |
| AlexNet | 5 conv, 3 FC         | ReLU       | ~60M   | Max     | Yes     |
| VGG     | Many 3x3 conv, 3 FC  | ReLU       | ~133M  | Max     | Yes     |

---
## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ivp_cnns_lenet_alexnet_vgg.git
   cd ivp_cnns_lenet_alexnet_vgg
