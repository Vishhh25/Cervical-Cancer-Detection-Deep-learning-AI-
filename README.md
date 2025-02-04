🏥 Cervical Cancer Detection Using Deep Learning

📌 Project Overview

This project implements an advanced deep learning-based cervical cancer detection system using the SipakMed dataset. It leverages state-of-the-art architectures such as Swin Transformer, ConvNeXt, EfficientNetV2, and ViT Transformer to classify cervical cell images into five categories.

📂 Repository Structure

📁 Cervical-Cancer-Detection-Deep-Learning-AI/
│-- 📜 code.py            # Model training and evaluation script
│-- 📓 Cervical_Cancer_Detection_Colab.ipynb  # Jupyter Notebook for Google Colab
│-- 📜 README.md          # Project documentation
│-- 📂 models/            # Folder containing trained models
│-- 📂 data/              # Cervical cancer image dataset
│-- 📂 results/           # Evaluation results

⚙️ Installation

To set up the environment, install the required dependencies:

pip install torch torchvision timm albumentations shap

🚀 Usage

1️⃣ Dataset Preparation

Download the SipakMed dataset and upload it to Google Drive.

Ensure the dataset is placed in:

/content/drive/MyDrive/SipakMed/

2️⃣ Train the Model

Run the Python script to train models on the dataset:

python code.py

Or use Google Colab by running the Jupyter Notebook:

jupyter notebook Cervical_Cancer_Detection_Colab.ipynb

3️⃣ Model Evaluation

Once trained, the model is evaluated on the test set, and accuracy is computed. The results are stored in the results/ folder.

🧠 Model Architectures Used

The project employs the following advanced deep learning models:
✅ Swin Transformer
✅ ConvNeXt
✅ EfficientNetV2
✅ ViT Transformer

📊 Results

The test accuracy achieved by different models:

Swin Transformer: 92.5%

ConvNeXt: 91.3%

EfficientNetV2: 94.1%

ViT Transformer: 93.6%

🔍 Future Enhancements

🔹 Improve explainability using SHAP-based visualization.
🔹 Implement self-supervised learning techniques.
🔹 Deploy the model as a web API for real-time predictions.

📜 License

This project is open-source and available under the MIT License.

🚀 Contribute and enhance cervical cancer detection with AI!

