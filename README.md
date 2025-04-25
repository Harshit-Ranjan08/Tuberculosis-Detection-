# 🧠 Tuberculosis Detection using CNNs (LeNet, DenseNet, WideResNet, AlexNet)

Drug-resistant Tuberculosis (TB) poses a critical challenge to global health. In this project, we leverage deep learning techniques to detect TB from chest X-ray (CXR) images using multiple Convolutional Neural Network (CNN) architectures — **LeNet**, **DenseNet**, **WideResNet**, and **AlexNet**.

Our approach combines radiological features from CXR images with powerful CNN models to improve diagnostic accuracy.

---

## 🚀 Highlights

- 📊 **Dataset**: TB Chest X-ray dataset from [TB Portals](https://tbportals.niaid.nih.gov/)
- 🖼️ **Image Augmentation**: Applied to address dataset imbalance between normal and TB-positive samples
- 🧬 **Focus**: Detection of **drug-resistant TB** from radiological data
- 🔍 **Models Used**:
  - ✅ LeNet
  - ✅ DenseNet
  - ✅ WideResNet
  - ✅ AlexNet

---

## 📈 Results

| Model       | Accuracy |
|-------------|----------|
| DenseNet    | 🟢 **99.50%** |
| LeNet       | 🟢 97.50%  |
| WideResNet  | 🟡 96.83%  |
| AlexNet     | 🔵 91.83%  |

> ✅ **DenseNet** emerged as the best-performing model with the highest classification accuracy.

---

## 🛠️ Tech Stack

- Python 🐍
- PyTorch / TensorFlow
- NumPy / Pandas / Matplotlib
- scikit-learn
- CNN Architectures (LeNet, AlexNet, DenseNet, WideResNet)

---

## 🧪 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/tb-cnn-detection.git
cd tb-cnn-detection

# Install dependencies
pip install -r requirements.txt

# Run training
python train.py --model densenet

# Run evaluation
python evaluate.py --model densenet

├── data/                # Dataset directory
├── models/              # CNN model definitions
├── notebooks/           # Jupyter notebooks for EDA & experiments
├── outputs/             # Trained weights, logs, visualizations
├── train.py             # Training script
├── evaluate.py          # Evaluation script
└── README.md

🤝 Contributors
Harshit Ranjan💻
Sharit Vaishnav
