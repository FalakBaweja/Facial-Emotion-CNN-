# Facial Emotion Recognition using a Custom CNN

👉 **[Read the Full Project Report Here](FER_Report.pdf)**

An end-to-end Deep Learning project built using PyTorch to classify human facial expressions into 7 distinct emotional states (Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise) using the FER-2013 dataset.

## 🚀 Key Highlights
- **Custom Architecture:** Built entirely from scratch using PyTorch convolutional layers—no pre-trained weights or high-level wrappers.
- **Data Imbalance Resolution:** Applied a 10x oversampling strategy to handle the severely under-represented 'Disgust' class, boosting its accuracy to 65.5%.
- **Overfitting Prevention:** Integrated data augmentation techniques including random rotations, horizontal flips, and color jittering.

## 📊 Final Performance Results
- **Overall Testing Accuracy:** 64.47%
- **Best-Performing Class:** Happy (87.8% accuracy)

### Per-Class Accuracy:
- Happy: 87.8%
- Disgust: 65.5%
- Angry: 56.2%
- Neutral: 48.0%
- Sad: 41.2%
- Surprise: 71.9%
- Fear: 37.1%

## 🛠️ How to Setup
1. Clone this repository.
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open `notebook.ipynb` in Jupyter Notebook or Google Colab to view the complete pipeline and training execution.
