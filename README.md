# Cats vs Dogs Classifier 🐱🐶

A Convolutional Neural Network (CNN) based classifier built in Python to distinguish between cat and dog images using the **Microsoft Cats vs Dogs Dataset**.

---

## 📌 Dataset

This project uses the **Microsoft Cats vs Dogs Dataset** from Kaggle:

🔗 https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset

The dataset contains thousands of labeled images of cats and dogs, perfect for training and evaluating an image classification model.

---

## 📁 Project Structure

```
Cats-vs-Dogs-Classifier/
│
├── data/                      # Dataset directory (images split)
├── notebooks/
│   └── Cats_vs_Dogs.ipynb     # Main notebook with model code
├── models/                    # Saved trained models
├── README.md
├── requirements.txt
├── utils.py                   # Helper functions (optional)
└── .gitignore
```

---

## 🧠 Model Overview

This project implements a Convolutional Neural Network (CNN) for image classification using TensorFlow/Keras. The model learns to distinguish dogs and cats from image pixels.

Typical architecture may include:

- Convolutional Layers
- Max Pooling Layers
- Dropout for regularization
- Fully Connected (Dense) Layers
- Softmax/Sigmoid output for binary classification

---

## ⚙️ Features

✔ Image preprocessing and resizing  
✔ Training/validation split  
✔ GPU support (if available)  
✔ Model training & evaluation  
✔ Accuracy & Loss visualization  
✔ Model saving and inference

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Cats-vs-Dogs-Classifier.git
cd Cats-vs-Dogs-Classifier
```

Create a virtual environment:

```bash
python -m venv env
source env/bin/activate      # macOS/Linux
env\Scripts\activate         # Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🧪 How to Run

1. Place the dataset under the `data/` directory  
2. Open the notebook:

```bash
jupyter notebook
```

3. Run `Cats_vs_Dogs.ipynb` from top to bottom

---

## 📊 Evaluation

You will see:

- Training & validation accuracy curves  
- Training & validation loss curves  
- Final test accuracy  

Example metrics may include:

| Metric       | Score |
|--------------|-------|
| Accuracy     | ~80–95% (varies by model) |
| Precision    | N/A |
| Recall       | N/A |

---

## 🛠 Future Improvements

- Data augmentation  
- Transfer learning (e.g., MobileNet/VGG16)  
- Hyperparameter tuning  
- Model deployment with Flask/FastAPI  
- Export to TF Lite / ONNX

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 📌 References

- Cats vs Dogs Dataset — Kaggle  
- TensorFlow & Keras documentation  
