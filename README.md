# 🧠 AI Image Inspection Tool

This project uses a Convolutional Neural Network (CNN) with OpenCV and TensorFlow to perform image inspection tasks, specifically identifying damaged or unclear areas in scanned documents. The goal is to demonstrate the use of AI in solving real-world image processing problems.

---

## 📌 Features

- Image classification at the pixel level
- Noise reduction and edge detection using OpenCV
- Deep learning-based inspection using TensorFlow
- High accuracy (95%+) with thorough model validation
- Easily extendable for other image classification tasks

---

## 🛠️ Technologies Used

- Python
- OpenCV
- TensorFlow
- Scikit-learn
- NumPy, Pandas
- Jupyter Notebook / Google Colab

---


---

## ▶️ How to Use

1. Clone the repository or open the notebook in **Google Colab**.
2. Mount your Google Drive (if dataset is stored there).
3. Update the dataset path in the notebook.
4. Run all cells to train the model and test image inspection.

python
from google.colab import drive
drive.mount('/content/drive')
# Set path to your dataset directory
dataset_path = '/content/drive/MyDrive/image_inspection_dataset/'


dataset_access:
  note: "Due to size limitations, the dataset is stored on Google Drive."
  link_text: "Download Dataset"
  link_url: "https://drive.google.com/your-dataset-link"

results:
  - "Model achieved over 95% classification accuracy."
  - "Preprocessing improved edge clarity and reduced noise."
  - "Custom test images were successfully classified."

use_cases:
  - "Document scanner quality control"
  - "Inspection of printed forms or paperwork"
  - "Automated filtering of corrupted image scans"

author:
  name: "Saad Ibrar"
  education: "BSc in Artificial Intelligence"
  github: "https://github.com/MalikSaadi123"


