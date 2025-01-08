# 🖐️ American Sign Language (ASL) Recognition 🌟


## 🎯 Project Goal
This project aims to bridge communication gaps by recognizing **American Sign Language (ASL)** gestures using **deep learning**. Whether it's the alphabet or special symbols like "Space" and "Nothing," our model predicts them all with precision!


![image](https://github.com/user-attachments/assets/f8be6f7e-b26a-4790-b057-345749528f7d)



## ✨ Key Features
- 🧠 **AI-Powered Gesture Recognition**: A robust CNN model for accurate predictions.
- 📊 **Performance Tracking**: Detailed accuracy and loss curves for training insights.
- 🎨 **GUI Interface**: User-friendly image upload and prediction using Tkinter.

## 🗂️ Dataset Overview
The dataset includes images for all ASL letters and additional symbols:

- **28 Classes**: A-Z, Space, Nothing.
- **Preprocessing**: Images resized to 64x64 pixels for optimal model performance.



## 🧬 Model Architecture
Our CNN architecture is designed for performance and reliability:

- **Convolutional Layers**: Extract unique gesture features.
- **Pooling Layers**: Reduce dimensions without losing critical information.
- **Dropout**: Prevent overfitting.
- **Dense Layers**: Classify gestures accurately.

🔧 Technical Details

- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy
- **Input Shape**: `(64, 64, 3)`



## 🚀 Results

📈 **Performance Metrics**

- **Training Accuracy**: Achieved high accuracy on training data.
- **Test Accuracy**: Strong generalization on unseen gestures.
- 
🖼️ **Visualizations**

Here’s how the model performed:

**Training and Validation Accuracy**:

![image](https://github.com/user-attachments/assets/a05b6daf-43da-4094-ac4e-fcf5e9b8f152)


**Training and Validation Loss**:


![image](https://github.com/user-attachments/assets/a21ee04a-f205-4662-beaa-42adcaa197a3)


## 🎨 Interactive GUI Application
The model is deployed using a Tkinter-based GUI, allowing users to:

1. **Upload an ASL gesture image**.
2. **View the predicted gesture in real-time**.


💻 **How It Works**:
1. Select an image of a hand gesture using the **Upload Button**.
2. Our trained model processes the image and predicts the class.
3. The result is displayed directly on the application interface!


![image](https://github.com/user-attachments/assets/98ea319e-21ff-413b-a745-8c274d9eaca1)




