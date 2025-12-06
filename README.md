# CIFAR-10 Image Classification

CNN and transfer learning for CIFAR-10 image classification.

## Projects

### 1. Custom CNN (`cifar10_cnn.ipynb`)
- Built from scratch with 2 convolutional blocks
- **Accuracy:** 67%
- Architecture: 3→32→64 channels

### 2. Transfer Learning (`cifar10_transfer_learning.ipynb`)
- Pretrained ResNet18 with fine-tuning
- **Accuracy:** 80%
- Includes data augmentation experiments

## Results Comparison
| Approach | Accuracy |
|----------|----------|
| Custom CNN | 67% |
| ResNet18 Transfer Learning | 80% |

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```

## Classes
airplane, car, bird, cat, deer, dog, frog, horse, ship, truck
