# Handwritten_Digit_Recognition
# 🖊️ Handwritten Digit Recognition using Scikit-learn

This project is a machine learning-based system that recognizes handwritten digits (0–9) from 8x8 grayscale images using Scikit-learn’s `load_digits` dataset. The model is deployed using Gradio to create a user-friendly web interface for real-time predictions.

## Features

- Trained using Logistic Regression on the `load_digits` dataset
- Achieves over 95% accuracy on test data
- Gradio-powered interface to upload or draw digit images
- Visualizations: Confusion matrix, label distribution, and pixel correlation
- Flagging system to capture incorrect predictions for future improvement

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Pillow (for image processing)
- Gradio (for UI deployment)

## 📊 Screenshots

<p float="left">
  <img src="images/sample_digits.png" width="45%" />
  <img src="images/gradio_ui.png" width="45%" />
</p>

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/handwritten-digit-recognition.git
   cd handwritten-digit-recognition
