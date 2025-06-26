# 🧠 Image Classification Using CNN in Keras

## 📌 About the Project
This project demonstrates how to build a **Convolutional Neural Network (CNN)** using **Keras** for classifying images. The input data is provided in CSV format, where each image is represented as a flat array of pixel values with its corresponding label.

## 🛠️ Technologies Used
- Python
- TensorFlow & Keras
- NumPy, Pandas
- Matplotlib for visualization

## 📁 Dataset

The dataset is uploaded in drive.

👉 [Click here to download the dataset](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbFZ2cFNRSVdZblpfeEVEMFo5WEZNVXQ1Z0o1Z3xBQ3Jtc0ttQy1OdEVTalJqR0NsU3Znc29PQm01NzZnZ1RSdHRIdjNyU000YVN0clUyeVJyRTNsODVVNFdOY0lRUy1aZ1RkUHVUQlBlSENfVnRpYi10MjRLQ1BYeDR2MXNjRFF4RGZwc193cF9RVW9XcTBIUTVJVQ&q=https%3A%2F%2Fbit.ly%2FImgClsKeras&v=J1jhfAw5Uvo)

## 🧮 Model Architecture
- **Input Layer**: Reshaped image input
- **Conv2D + ReLU Activation**  
- **MaxPooling2D**  
- (Repeated layers as needed)
- **Flatten**
- **Dense Layers**
- **Output Layer**: Softmax for multi-class classification
## 📈 Results
- Model classifies images into categories such as **Dog** or **Cat**
- Evaluation based on classification accuracy and confusion matrix
- Example predictions:  
  - Input: 🐶 → Predicted: **Dog**  
  - Input: 🐱 → Predicted: **Cat**
- Final classification accuracy: **[97.9%]**

## 🚀 How to Run
1. Clone this repo  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
