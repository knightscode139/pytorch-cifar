# CIFAR-10 CNN Classifier

CNN for classifying CIFAR-10 images into 10 categories.

## Results
- **Test Accuracy:** 67%
- **Architecture:** 2 convolutional blocks (3→32→64 channels)
- **Training:** 20 epochs with Adam optimizer

## Classes
airplane, car, bird, cat, deer, dog, frog, horse, ship, truck

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook cifar10_cnn.ipynb
```

## Architecture
- Conv2d(3→32) + ELU + MaxPool
- Conv2d(32→64) + ELU + MaxPool  
- Flatten + Linear(4096→10)
