# Emotion-detection-using-CNN-on-fer-2013-dataset
This project detects human emotions from facial expressions using a Convolutional Neural Network (CNN). It is trained on the FER-2013 dataset. This project uses the [FER-2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013) for training and testing.
Download the dataset and place it in the `data/` folder before running the training script.


## 📂 Project Structure  
- 📁 **haarcascade/** → Contains Haar cascade XML file for face detection  
- 📁 **models/** → Stores trained CNN models  
- 📁 **src/** → Python scripts for inference and training  
- 📄 **Emotion_prediction.ipynb** → Jupyter notebook for model training/testing  
- 📄 **requirements.txt** → List of dependencies  

## 🔧 Installation
1. Clone this repository:  
git clone https://github.com/Ayush-kgp/Emotion-detection-using-CNN-on-fer-2013-dataset.git

2. Install dependencies:  
pip install -r requirements.txt


##  Usage
Run the emotion detection script:  
python src/emotion_app.py

