# 🚦 Traffic Sign Recognition
This project implements a Traffic Sign Recognition system using Convolutional Neural Networks (CNNs). The model is trained on the GTSRB (German Traffic Sign Recognition Benchmark) dataset to classify traffic signs into their respective categories.
## 📌 Project Overview
Traffic sign recognition is an essential component in autonomous driving systems. The goal of this project is to detect and classify traffic signs from images, enabling vehicles to make informed driving decisions.
## 🛠 Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
## 📂 Dataset
GTSRB Dataset: [Download Link](https://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)  
Contains 43 classes of traffic signs.  
Images are preprocessed by:
- Resizing to 32x32 pixels
- Normalizing pixel values
- Data augmentation for better generalization
## 🚀 How to Run
Clone this repository:
``bash
git clone https://github.com/ziadsameh1/traffic-sign-recognition.git
cd traffic-sign-recognition

Install dependencies:
bash
pip install -r requirements.txt
`
Run the notebook:
- Open `traffic_sign_recognition.ipynb` in Jupyter Notebook or Google Colab.
- Execute all cells to train and evaluate the model.
## 📊 Model Performance
- Accuracy: ~95% on test data
- Model: Custom CNN with multiple Conv & Pool layers
- Loss Function: SparseCategoricalCrossentropy
- Optimizer: Adam
## 📷 Example Predictions
| Image | Prediction |
|-------|------------|
| ![Stop Sign](assets/stop.png) | Stop |
| ![Speed Limit 50](assets/50.png) | Speed Limit 50 km/h |
| ![Turn Left](assets/left.png) | Turn Left |
## 📜 License
This project is licensed under the MIT License - feel free to use and modify it.
## 👨‍💻 Author
**Ziad Sameh**  
