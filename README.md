# Dog Breed Identification Using Transfer Learning

## 📌 Project Overview
This project implements a deep learning–based system to identify the breed of a dog from an input image.  
It uses **Transfer Learning** with a pre-trained Convolutional Neural Network (CNN) to achieve high accuracy while reducing training time and computational cost.

---

## 🧠 Model Information
The project uses **pre-trained CNN models** fine-tuned on a dog breed dataset.

### Included Model Files:
- `dog_breed_model.h5`  
- `dog_breed_model.keras`  

These models are trained using transfer learning techniques and can be directly loaded for prediction without retraining.

---

## 📁 Dataset
The dataset consists of labeled dog images representing multiple breeds.

### Dataset Details:
- Images categorized by dog breed  
- Data preprocessed (resizing, normalization)  
- Used for training and validation  

The dataset is provided in compressed format:
- `data.zip`

*(Dataset size and number of breeds depend on training configuration.)*

---

## ⚙️ Requirements
To run this project, the following software requirements are needed:

### Software Requirements:
- Python 3.x  
- TensorFlow  
- Keras  
- NumPy  
- OpenCV  
- Pillow  
- Matplotlib  

Install dependencies using:
```bash
pip install tensorflow keras numpy opencv-python pillow matplotlib

