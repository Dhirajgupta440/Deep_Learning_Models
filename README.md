# 📊 Comparative Study of Deep Learning Models on MNIST Dataset

This repository presents a comparative study of four deep learning architectures — **LeNet**, **ResNet**,**Transformer**, and **VGG16** — applied to the **MNIST** handwritten digit classification task.

##  Models Implemented
- **LeNet** – A classic CNN architecture for digit recognition
- **ResNet** – Deep residual network with skip connections
- **Transformer** – Transformer leverages self-attention mechanisms to process and understand sequential data.
- **VGG16** – Deep CNN with uniform architecture blocks


## Evaluation Metrics
Each model is evaluated using:
- Accuracy
- Precision
- Recall

## Results Summary
| Model      | Accuracy(%) | Precision(%) | Recall(%) | 
|------------|----------|-----------|--------|
| LeNet      | 98.81   | 99.51    | 99.69| 
| ResNet     | 98.89   | 99.71   | 99.91| 
| Transformer      | 97.30  | 99.58   |99.59 |
| VGG16      | 99.37  | 99.80   | 99.70 |

>

## Dataset
- MNIST dataset
- 70,000 grayscale images (28×28 pixels) of handwritten digits (0–9)  
- Training Set: 60,000 images  
- Test Set: 10,000 images  
- Classes: 10 (digits 0 to 9)


## Requirements
- Python 3.8+
- TensorFlow / Keras
- NumPy, Matplotlib, Scikit-learn

## Run the Notebooks
Open in [Google Colab](https://colab.research.google.com/drive/1tvyXBI5-KnvXYq_avEsqyo5KiQFRWQN6#scrollTo=IIThvfT8OnW5) or run locally after setting up the required libraries.

---

**Platform:** Google Colab  
**Submitted by:** Dhiraj Kumar  

