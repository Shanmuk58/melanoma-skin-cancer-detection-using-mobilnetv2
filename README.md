🧬 Melanoma Cancer Detection using MobileNetV2 & Enhanced Hybrid V3
This project implements deep learning-based techniques for the early detection of melanoma, a dangerous form of skin cancer. It utilizes both MobileNetV2 (a lightweight pre-trained CNN model) and a custom Enhanced Hybrid V3 architecture to classify dermatoscopic images of skin lesions as benign or malignant.

📁 Project Structure
melanoma cancer detection final.ipynb — Main Jupyter notebook containing all steps: data preprocessing, model training, evaluation, and predictions.

🚀 Key Features
Transfer learning with MobileNetV2

Custom deep learning model: Enhanced Hybrid V3

Image augmentation for better generalization

Performance visualization (accuracy/loss graphs, confusion matrix)

Binary classification: benign vs. malignant

🧠 Technologies Used
Python

TensorFlow / Keras

OpenCV

NumPy, Pandas

Matplotlib, Seaborn

Scikit-learn

📊 Dataset
The dataset consists of labeled dermatoscopic images of skin lesions. A common source is the ISIC Archive, though your dataset may differ.

✅ Update this section with a description or link to your actual dataset, if different.

🛠️ Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/melanoma-cancer-detection.git
cd melanoma-cancer-detection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:

bash
Copy
Edit
jupyter notebook
📈 Model Results


Training-97%
Validation-95%

🧪 How to Use
Load the notebook and run all cells.

Upload an image via the provided interface or path.

The model predicts whether the lesion is benign or malignant.

