# CV Internship Portfolio

This repository showcases my hands-on work in PyTorch, fastai, transfer learning, and ResNet reproduction
---
## Folder Structure

### 1. `pytorch-basics/`
Contains tutorial notebooks covering core PyTorch concepts and workflows:

Each subfolder includes a `README.md` summarizing the key lesson and pointing to its notebook.

---

### 2. `fastai_mini_cv/`
Hands-on experiments following fastai book chapters 5, 13, and 14:
- **ch5_ImageClassification/**  
  DataBlock API experiments, presizing vs. on-the-fly resizing, batch-size comparisons.  
- **ch13_CNN/**  
  Manual convolution implementation, stride/padding tests, visualization of activation maps.  
- **ch14_ResNets/**  
  Building and fine-tuning basic ResNet blocks on the Imagenette sample dataset.  

Each chapter folder contains notebooks (`.ipynb`) with code, results (CSV/plots), and a `README.md` that highlights the chapter’s core concepts.

---

### 3. `transfer-learning/`
A complete PyTorch script for fine-tuning an ImageNet-pretrained ResNet34 on a custom dataset:
- **train.py**: model setup, train/validation loop, metrics logging  
- **config.yaml**: hyperparameter definitions (learning rate, batch size, epochs)  
- **val_results.json**: recorded validation accuracies per epoch  
- **README.md**: dataset description, training configuration, and performance graphs  

Demonstrates adapting pretrained features to new tasks and producing reproducible results.

---

### 4. `paper-replica-resnet/`
Reproduction of “Deep Residual Learning for Image Recognition” (He et al., 2015):
- **src/blocks.py**: implementation of the ResNet BasicBlock and Bottleneck modules  
- **src/model.py**: assembly of the full ResNet architecture matching the paper’s specification  
- **train_resnet.py**: training script on CIFAR-10 with command-line arguments  
- **logs/train_log.csv**: epoch-wise loss and accuracy records  
- **results/curve.png**: training and validation curves  
- **results/confusion_matrix.png**: final evaluation on test set  
- **README.md**: mapping of paper equations to code, environment details, and final reproduced accuracy  

---

### 5. `CS231n/`
Archived lecture notes and personal summaries from Stanford’s CS231n “Convolutional Neural Networks for Visual Recognition” course, for reference and deeper theoretical background.

