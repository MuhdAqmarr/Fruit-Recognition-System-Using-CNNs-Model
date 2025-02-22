🍓 Fruit Recognition using CNN

🔍 Overview
This project is a deep learning-based fruit recognition system built using Convolutional Neural Networks (CNNs). It utilizes the Fruit-360 dataset, which contains images of different fruit classes. The trained model can classify fruits with high accuracy, making it useful for applications in agriculture, food industry, and automation.

📌 Features
✅ Classifies 10 different fruit types with high accuracy 🍏🍊🍓
✅ CNN architecture with convolution, pooling, and fully connected layers 🧠
✅ Implements Max Pooling to reduce computational complexity ⏳
✅ Real-time fruit recognition via an image upload interface 📷
✅ Accuracy & Loss visualization using Matplotlib 📊

📂 Dataset
The model is trained using the Fruit-360 dataset, which consists of high-quality images of different fruits. The dataset was created by:
📌 Mihai Oltean & Horea Muresan
https://github.com/fruits-360
https://www.kaggle.com/datasets/moltean/fruits

🛠 Technologies Used
- Python 🐍
- TensorFlow/Keras for building CNN models
- OpenCV for image preprocessing
- Matplotlib for accuracy & loss visualization
- Flask (if web-based UI is included)

📖 Model Architecture

The CNN model consists of:

1️⃣ Convolutional Layers – Extract features from images

2️⃣ Max Pooling Layers – Reduce spatial dimensions and computational cost

3️⃣ Fully Connected (Dense) Layers – Perform final classification

4️⃣ Softmax Activation – Outputs class probabilities





💡 The model is trained for 15 epochs with an optimized learning rate for best accuracy.


📊 Results

🔹 Accuracy & Loss Graphs
![accuracy_loss_plot](https://github.com/user-attachments/assets/49edd512-35fe-41ba-83fd-e83cc8a83246)


📜 Classification Report

The model achieves high accuracy on the test dataset.
📌 For detailed performance metrics, check the classification_report.txt file.



🚀 How to Run the Project

1️⃣ Clone this repository

git clone https://github.com/yourusername/fruit-recognition.git

cd fruit-recognition

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the model training

python train_model.py

4️⃣ Test the model on an image

python gui.py


📜 License
This project is licensed under the MIT License, and it acknowledges the Fruit-360 dataset by Mihai Oltean & Horea Muresan.

🔗 MIT License Details https://www.kaggle.com/datasets/moltean/fruits, https://github.com/fruits-360
