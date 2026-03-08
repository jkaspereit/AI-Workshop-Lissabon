# 🔢 Digit Recognition Workshop

Welcome to the Handwritten Digit Recognition Workshop! This workshop will guide you through building, training, and evaluating a neural network to recognize handwritten digits from the MNIST dataset.

## 📋 Prerequisites

- Basic Python programming knowledge
- Understanding of basic mathematics (no deep expertise required!)
- Python 3.8 or higher installed on your system

## 🚀 Getting Started

### 1. Clone or Download This Repository

```bash
git clone <repository-url>
cd AI-Workshop-Lissabon
```

### 2. Create a Virtual Environment (Recommended)

**On macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

**On Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

All required packages are listed in `requirements.txt`. Install them with:

```bash
pip install -r requirements.txt
```

This will install:
- TensorFlow & Keras (Deep Learning framework)
- NumPy (Numerical computing)
- Pandas (Data manipulation)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine learning utilities)
- Jupyter (Notebook environment)

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

This will open Jupyter in your browser. Navigate to `digit_recognition_workshop.ipynb` and open it.

### 5. Follow Along!

The notebook is structured in 12 clear steps with detailed explanations. Simply run each cell in order and read the markdown explanations to understand what's happening.

## 📚 Workshop Structure

The workshop covers:

1. **Introduction** - Understanding the problem and dataset
2. **Data Loading** - Loading the MNIST dataset
3. **Data Visualization** - Exploring handwritten digits
4. **Data Preprocessing** - Preparing data for training
5. **Model Building** - Creating a neural network
6. **Model Compilation** - Configuring the training process
7. **Training** - Teaching the model to recognize digits
8. **Evaluation** - Testing model performance
9. **Training History** - Visualizing learning progress
10. **Predictions** - Making predictions on new data
11. **Error Analysis** - Understanding model mistakes
12. **Model Saving** - Saving and loading trained models

## 🎯 Learning Outcomes

After completing this workshop, you will be able to:

- ✅ Load and preprocess image datasets
- ✅ Build neural networks using Keras/TensorFlow
- ✅ Train deep learning models
- ✅ Evaluate model performance
- ✅ Visualize and interpret results
- ✅ Save and deploy trained models

## 📊 Expected Results

With the default architecture, you should achieve:
- **Training Accuracy**: ~98-99%
- **Test Accuracy**: ~97-98%
- **Training Time**: ~2-3 minutes on a modern CPU

## 🆘 Troubleshooting

### Issue: Package Installation Fails

**Solution**: Make sure you're using Python 3.8+
```bash
python --version
```

If you have an older version, download the latest from [python.org](https://www.python.org/downloads/).

### Issue: Out of Memory Errors

**Solution**: Reduce the batch size in the training step:
```python
model.fit(..., batch_size=64, ...)  # Instead of 128
```

### Issue: Jupyter Notebook Won't Start

**Solution**: Make sure Jupyter is installed:
```bash
pip install jupyter
```

### Issue: TensorFlow Installation Problems

**Solution**: Try installing specific versions:
```bash
pip install tensorflow==2.15.0 keras==2.15.0
```

For Apple Silicon Macs, use:
```bash
pip install tensorflow-macos tensorflow-metal
```

## 🔧 Requirements

### Hardware
- **Minimum**: Any modern computer with 4GB RAM
- **Recommended**: 8GB+ RAM for faster training
- **GPU**: Not required, but can speed up training

### Software
- Python 3.8+
- pip (Python package manager)
- 500MB free disk space

## 📝 Files in This Repository

```
AI-Workshop-Lissabon/
├── README.md                              # This file
├── requirements.txt                       # Python dependencies
├── digit_recognition_workshop.ipynb       # Main workshop notebook
└── (generated during workshop)
    ├── digit_recognition_model.keras      # Saved model (Keras format)
    ├── digit_recognition_model.h5         # Saved model (H5 format)
    └── digit_recognition_savedmodel/      # Saved model (SavedModel format)
```

## 🎓 Additional Resources

- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Keras Documentation](https://keras.io/)
- [MNIST Dataset Information](http://yann.lecun.com/exdb/mnist/)
- [Deep Learning Basics](https://www.deeplearningbook.org/)

## 🤝 Contributing

Found an issue or have suggestions for improvement? Feel free to:
- Open an issue
- Submit a pull request
- Share your feedback

## 📜 License

This workshop material is provided for educational purposes.

## 🙏 Acknowledgments

- MNIST Dataset: Yann LeCun, Corinna Cortes, and Christopher J.C. Burges
- Built with TensorFlow and Keras
- Inspired by the machine learning community

---

**Happy Learning! 🎉**

If you enjoy this workshop, please ⭐ star this repository!
