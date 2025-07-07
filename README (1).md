
# 🗑️ Garbage Classification using Deep Learning

This project uses a Convolutional Neural Network (CNN) to classify images of garbage into two categories:
- **Biodegradable**
- **Non-Biodegradable**

## 📁 Dataset Structure

```
dataset/
├── biodegradable/
│   └── (images of biodegradable waste)
├── non_biodegradable/
    └── (images of non-biodegradable waste)
```

## 🚀 Project Workflow

1. Collected and organized image data into two classes
2. Preprocessed images (resize to 64x64, normalize)
3. Built a CNN model using TensorFlow and Keras
4. Trained the model with training and validation split
5. Evaluated accuracy and loss
6. Used the model to predict new waste images

## 🧠 Model Summary

- Input size: 64x64 RGB images
- Layers: Conv2D → MaxPooling → Flatten → Dense → Output
- Activation: ReLU and Sigmoid
- Loss Function: Binary Crossentropy
- Optimizer: Adam

## 📈 Output Screenshot

![Model Output](mock_output_screenshot.png)

## 🛠️ Tools & Technologies Used

- Python 🐍
- TensorFlow & Keras 🧠
- OpenCV 🖼️
- Scikit-learn 📊
- Jupyter Notebook 📓

## 📄 Project Author

Created by **Praful Patil**  
GitHub: [Praful958](https://github.com/Praful958)
