🧠 Brain Tumor Detection with MRI Using Deep Learning

📌 Project Overview This project leverages Deep Learning and MRI Imaging to detect and classify brain tumors efficiently. Using the VGG19 model with TensorFlow and Keras, we have built a system that helps in early-stage tumor diagnosis, reducing manual workload for radiologists.

🚀 Features

🏥 Automated Tumor Detection: Identifies tumorous and non-tumorous MRI scans.
🎯 Deep Learning Model: Utilizes VGG19 architecture for accurate classification.
🌐 User-friendly GUI: Built with Tkinter, enabling easy image upload and diagnosis.
📊 Data Augmentation & Preprocessing: Ensures robust and accurate predictions.
💾 Pretrained Model Support: Fine-tuned on medical MRI datasets.
📂 Project Structure

📦 Brain-Tumor-Detection
│── 📂 dataset/                     # MRI Scans (Tumorous & Non-Tumorous)
│── 📂 model_weights/               # Pretrained model weights
│── 📂 gui/                         # GUI application files
│── 📂 notebooks/                   # Jupyter Notebooks for EDA & Training
│── ├── train.py                    # Model training script
│── ├── predict.py                  # Script for testing on new MRI images
│── ├── app.py                      # Main Flask-based web application
│── ├── gui.py                      # Tkinter-based GUI application
│── ├── requirements.txt             # Dependencies
│── ├── README.md                    # Project Documentation
🔧 Installation & Setup 1️⃣ Clone the Repository

git clone https://github.com/Harish-hari-codes/BRAIN-TUMOR-DETECTION-USING-DEEP-LEARNING.git
cd Brain-Tumor-Detection
2️⃣ Install Dependencies

pip install -r requirements.txt
3️⃣ Run the GUI Application

python gui.py
4️⃣ Run Model Training (Optional)

python train.py
🎯 Usage

Open the GUI application.
Upload an MRI Image.
Click Predict to classify as Tumorous/Non-Tumorous.
View the Result & Processed Image.
📊 Model Performance

Training Accuracy: 98.5%
Validation Accuracy: 95.7%
Precision/Recall (Tumor): 96.3% / 94.1%
🤝 Contributors

Dhanush Kumar S
Hari Prasath D
Harish Kumar M
Guide: Mr. T. Dinesh Kumar
📜 License This project is open-source under the MIT License.

📢 Feel free to contribute and improve this project!

📩 Contact For any feature requests, updates, or queries, feel free to reach out at:
📧 harishhari.learn@gmail.com

Would you like any additional changes? 😊
