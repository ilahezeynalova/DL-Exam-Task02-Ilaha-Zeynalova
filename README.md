# Task 2: Fashion

**Student:** Ilaha Zeynalova  
**ID:** S302  
**Seed:** 20240302  

## Presentation
https://docs.google.com/presentation/d/1aisyknYyAXmzq59MZcAn57zLehBUjD5S/edit?usp=sharing&ouid=100410766461951068132&rtpof=true&sd=true

## Dataset
- **Name:** Fashion-MNIST (28×28 grayscale clothing images)
- **Classes:** 10
- **Training samples:** 60,000
- **Test samples:** 10,000

## Model Architecture
- **Type:** CNN
- **Convolutional layers:** 2
- **Fully connected layers:** 2
- **Activation:** ReLU
- **Pooling:** MaxPooling
- **Total parameters:** ~421,000

## Training Comparison

### Version 1
- **Learning rate:** 0.001
- **Batch size:** 64
- **Optimizer:** Adam
- **Dropout:** 0.5
- **Test accuracy:** 87.23%

### Version 2
- **Learning rate:** 0.001
- **Batch size:** 64
- **Optimizer:** Adam
- **Dropout:** 0.3
- **Test accuracy:** 88.50%

### Best Result
- **Best version:** Version 2
- **Final test accuracy:** 88.50%
- **Target accuracy:** ≥88%
- **Status:** ✓ Achieved

## Analysis
- **Best performing class:** Sandal
- **Worst performing class:** Shirt
- **Key observations:**  
  The model performs best on visually distinct classes such as sandals.  
  Confusion mainly occurs between similar clothing items like shirts and T-shirts.  
  Reducing dropout helped the model retain more useful features and improved generalization.

## Files
- `notebook.ipynb`: Complete implementation with both training runs
- `results/training_comparison.png`: Comparison of Version 1 vs Version 2
- `results/confusion_matrix.png`: Confusion matrix from best model
- `results/predictions.png`: Sample predictions


## Files
- `notebook.ipynb`: Complete implementation with both training runs
- `results/training_comparison.png`: Comparison of Version 1 vs Version 2
- `results/confusion_matrix.png`: Confusion matrix from best model
- `results/predictions.png`: Sample predictions
