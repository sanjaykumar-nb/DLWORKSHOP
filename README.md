# 🧠 Census Income Classification using PyTorch

This project builds a **binary classification model** to predict whether an individual earns more than **$50,000** annually using the **Census Income Dataset**.  
It demonstrates end-to-end machine learning workflow — from preprocessing and encoding to model training, evaluation, and user prediction.


---

## 🚀 Features

- Handles both **categorical** and **continuous** data  
- Encodes categorical columns using `LabelEncoder`  
- Normalizes numerical features with `StandardScaler`  
- Implements a **PyTorch neural network** with one hidden layer  
- Uses **CrossEntropyLoss** and **Adam optimizer** for training  
- Evaluates the model on test data  
- Includes a **user prediction function** to classify new entries  

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```
   git clone https://github.com/yourusername/DLWORKSHOP.git
   cd DLWORKSHOP
   ```
2. **Install Dependencies:**
```
pip install -r requirements.txt
```

📈 Evaluation Metrics

After training, the model is evaluated using:

Test Loss

Test Accuracy (%)

🧾 Example Results
Test Loss: 0.42
Test Accuracy: 86.7%

