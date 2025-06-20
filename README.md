📦 E-Waste Image Classification Using EfficientNetV2B0 (AICTE Edunet Internship - Week 1)

🔍 Problem Statement
Electronic waste (e-waste) is a growing concern. Manual sorting is inefficient and error-prone. This project uses **EfficientNetV2B0 with Transfer Learning** to automatically classify 10 types of e-waste based on image data, helping automate the sorting process.

🎯 Project Objective
Build a lightweight, efficient, and accurate image classification model that:
- Uses transfer learning (EfficientNetV2B0)
- Classifies images into 10 e-waste categories
- Deploys a live demo using **Gradio**


📁 Dataset Used
- **Source**: [Kaggle E-Waste Image Dataset](https://www.kaggle.com/datasets/akshat103/e-waste-image-dataset)
- **Classes**: PCB, Player, Battery, Microwave, Mobile, Mouse, Printer, Television, Washing Machine, Keyboard
- **Structure**:
dataset
  ├── train
  ├── validation
  └── test

🛠️ Tools & Libraries
- Python
- TensorFlow + Keras
- EfficientNetV2B0 (Transfer Learning)
- Matplotlib
- Gradio (for live prediction demo)


🔧 Week 1 Work Done
- Implemented EfficientNetV2B0 model
- Resized images to `128x128` for lightweight training
- Added `Dropout` and `EarlyStopping` to prevent overfitting
- Froze first 100 layers for efficient transfer learning
- Created a Gradio interface for live testing

📈 Results
- Achieved high test accuracy (~96%)
- Model generalizes well across all 10 classes
- Ready for deployment & extension in Week 2

🚀 Run the Notebook
1. Clone or download the repo
2. Open `week1_EWaste_Classification.ipynb` in Jupyter Notebook
3. Ensure you have the dataset in `dataset/train`, `dataset/validation`, `dataset/test`
4. Run all cells to train and evaluate the model
5. Test your model with the Gradio app




