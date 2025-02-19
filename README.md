# 🍇 Grape Leaf Disease Detection Using Deep Learning  

This project is a **deep-learning-based image classification model** for identifying grape diseases using transfer learning. It utilizes TensorFlow and Keras with multiple pre-trained architectures such as **DenseNet121, Xception, NASNetLarge, and ResNet50** to classify grape leaves into four categories:  

✅ **Black Rot**  
✅ **ESCA**  
✅ **Healthy**  
✅ **Leaf Blight**  

## 🚀 Features  
- **Transfer Learning**: Pre-trained models (DenseNet121, Xception, NASNetLarge, ResNet50) for high accuracy.  
- **Custom Training**: Train on a dataset of grape leaf images.  
- **Web Interface**: Upload images for real-time disease classification.  
- **Saved Model**: `grape_disease_model.h5` for easy inference.  

## 📂 Project Structure  
```
📂 Grape Disease Detection  
│-- 📄 app.py               # Web application script  
│-- 📄 DenseNet121.py       # Model using DenseNet121  
│-- 📄 grape_disease_model.h5  # Trained model  
│-- 📄 main.py              # Main execution script  
│-- 📄 NASNetLarge_model.py # Model using NASNetLarge  
│-- 📄 pro.py               # Additional utilities  
│-- 📄 ResNet50_model.py    # Model using ResNet50  
│-- 📄 train_model.py       # Training script  
│-- 📄 Xception_model.py    # Model using Xception  
│  
├── 📂 static  
│   ├── 🖼️ uploaded.jpg     # Sample uploaded image  
│  
├── 📂 templates  
│   ├── 📄 index.html       # Web UI  
│  
└── 📂 Final Training Data  # Dataset  
    ├── 📂 Black Rot  
    ├── 📂 ESCA  
    ├── 📂 Healthy  
    ├── 📂 Leaf Blight  
```  

## 🔧 Installation  
1️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/Sandeepmopidevi/Grape-Disease-Detection-Using-Deep-Learning.git
   cd Grape-Disease-Detection-Using-Deep-Learning
   ```  
2️⃣ Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3️⃣ Train the model (optional):  
   ```bash
   python train_model.py
   ```  
4️⃣ Run the web app:  
   ```bash
   python app.py
   ```  
5️⃣ Open `http://localhost:5000` in your browser and upload an image for classification.  

## 📊 Dataset  
The dataset consists of grape leaf images categorized into four classes:  
- **Black Rot**  
- **ESCA**  
- **Healthy**  
- **Leaf Blight**  

## 🛠 Contributing  
Feel free to **fork this repository** and contribute to the project!  

## 📝 License  
This project is licensed under the **MIT License**. See the [`LICENSE`](LICENSE) file for details.  
