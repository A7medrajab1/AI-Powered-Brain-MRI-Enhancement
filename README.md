# 🧠 ClearMind: AI-Powered Brain MRI Denoising

**ClearMind** is a deep learning project focused on removing noise from Brain MRI scans using denoising autoencoders. It leverages convolutional neural networks (CNNs) to enhance the quality of grayscale medical images, making them clearer for diagnostics and machine interpretation.

---

## 📊 Dataset

This project uses the [Brain Tumor Dataset](https://www.kaggle.com/datasets/a7medragab11/brain-tumor-dataset) from Kaggle, which contains brain MRI images categorized by tumor type.

### 📥 How to Download

1. Visit the dataset link:  
   👉 [Brain Tumor Dataset on Kaggle](https://www.kaggle.com/datasets/a7medragab11/brain-tumor-dataset)

2. Click **"Download"** after logging into your Kaggle account.

3. Extract the contents into a folder like:
   ```
   data/brain_tumor_dataset/
   ```

---

## 🚀 Features

- ✅ Preprocessing and noise injection (Gaussian noise)
- 🧠 Denoising autoencoder using convolutional layers
- 📈 Visual and metric-based evaluation: PSNR, SSIM, MAE, MSE
- 📊 Training history plots for loss, MAE, and MSE
- 💾 Model checkpointing and reproducibility support

---

## 🧪 Metrics Used

| Metric | Description |
|--------|-------------|
| **MSE** | Mean Squared Error between denoised and original image |
| **MAE** | Mean Absolute Error |
| **PSNR** | Peak Signal-to-Noise Ratio (higher is better) |
| **SSIM** | Structural Similarity Index (closer to 1 is better) |

---

## 🖼️ Sample Output

| Noisy Input | Denoised Output | Ground Truth |
|-------------|------------------|--------------|
| ![](examples/noisy.png) | ![](examples/denoised.png) | ![](examples/original.png) |

---

## ⚙️ Project Structure

```
├── deep-learning-denoising-brain-tumors.ipynb        # Main notebook
├── requirements.txt                                  # Project dependencies
└── README.md                                         # This file
```

---

## 📦 Installation

```bash
git clone https://github.com/A7medrajab1/AI-Powered-Brain-MRI-Enhancement.git
cd clearmind-denoising

# Install dependencies
pip install -r requirements.txt
```

---

## 🧠 How to Use

Run the notebook:

```bash
jupyter notebook deep-learning-denoising-brain-tumors.ipynb
```

Or open it in VS Code / Google Colab / Kaggle.

---

## 🙌 Acknowledgements

- Dataset by [Ahmed Ragab on Kaggle](https://www.kaggle.com/datasets/a7medragab11/brain-tumor-dataset)
- TensorFlow/Keras for model building
- Scikit-image for image quality metrics
