# Realtime Handwritten Digit Recognition using CNN 🧠📝

A real-time handwritten digit recognition app using a Convolutional Neural Network (CNN). Draw a digit on paper, capture it via webcam or upload an image, and get predictions instantly. Deployed using Gradio on Hugging Face Spaces.

## 🔍 Demo

🚀 Try the live app: [Launch on Hugging Face](https://huggingface.co/spaces/GurukiranSM/Handwritten-digit-recognizer)

---

## 📌 Features

- 📝 Draw digit on **paper**, capture or upload image
- 🧠 Predicts digits (0-9) using trained CNN model
- 🧾 Uses MNIST dataset for training (60,000 samples)
- 🖼️ Image preprocessing using OpenCV
- 🧪 Built-in prediction confidence
- ⚡ Fast and lightweight Gradio interface

---

## 🛠️ Tech Stack

- **Model**: Convolutional Neural Network (CNN)
- **Dataset**: MNIST (60,000 training + 10,000 test samples)
- **Libraries**: TensorFlow, NumPy, OpenCV, Pillow, Matplotlib
- **UI**: Gradio (Python)
- **Deployment**: Hugging Face Spaces

---

## ⚙️ How It Works

1. User **draws a digit on paper**.
2. Capture or upload the image.
3. Image is:
   - Converted to grayscale
   - Resized to 28x28
   - Inverted and normalized
4. Image is fed into the **CNN model**.
5. Prediction is displayed with the confidence score.

---

## 📂 Project Structure

├── app.py # Gradio app script
├── model.h5 # Trained CNN model
├── requirements.txt # Dependencies for Hugging Face
└── README.md # Project overview

---

## 🧪 Model Info

- **Architecture**: CNN (2 Conv2D + MaxPooling + Dense)
- **Input shape**: 28x28 grayscale image
- **Training Samples**: 60,000 from MNIST
- **Test Samples**: 10,000 from MNIST
- **Accuracy**: ~98% on test set

---

## 🚀 Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/Gurukiran20/Realtime-handwritten-digit-Recognition-using-CNN.git
   cd Realtime-handwritten-digit-Recognition-using-CNN
2. Install dependencies:
   pip install -r requirements.txt
3. Run the app:
   python app.py
4. 🤝 Contributing
Have ideas or want to improve this app? Contributions are welcome!

Fork the repo
Create a new branch
Submit a pull request

***⭐ Don’t forget to star this repo if you found it useful!***

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
"# Realtime-handwritten-digit-Recognition-using-CNN" 
