🧠 Brain Cancer Classification Using Deep Learning

📌 Project Overview

This project uses Deep Learning to classify brain MRI images into three categories: Glioma, Meningioma, and Brain Tumor.

Three different deep learning architectures are developed and compared to evaluate their classification performance.

🎯 Objective
- Classify brain MRI images into three categories.
- Build CNN and CNN + LSTM models.
- Compare model performance.
- Predict brain cancer categories from MRI images.

📂 Dataset Description
- Total Images: 600
- Image Size: 224 × 224
- Image Channels: RGB (3)
- Number of Classes: 3
Classes:
1. Brain Glioma
2. Brain Meningioma
3. Brain Tumor

🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- TensorFlow
- Keras
- Scikit-learn
- Google Colab

⚙️ Project Workflow
1. Import required libraries.
2. Load MRI image dataset.
3. Perform data exploration and visualization.
4. Encode class labels.
5. Split the dataset into training, validation, and testing sets.
6. Normalize image data.
7. Build deep learning models.
8. Train and evaluate the models.
9. Compare model performance.
10. Save the trained model.

🔍 Data Preprocessing
- Image resizing to 224 × 224.
- RGB image processing.
- Label encoding.
- Dataset splitting.
Dataset	Percentage
Training	70%
Validation	15%
Testing	15%

🤖 Deep Learning Models

1. CNN Model
- Three convolutional layers.
- Max Pooling.
- Flatten layer.
- Dense layer.
- Dropout.
- Softmax output.

2. Simplified CNN Model
- Two convolutional layers.
- Max Pooling.
- Flatten layer.
- Dense layer.
- Dropout.
- Softmax output.

3. CNN + LSTM Model
- CNN for feature extraction.
- Reshape layer.
- LSTM for sequence learning.
- Dense layer.
- Softmax output.

📊 Model Comparison
Model	Test Accuracy
CNN Model	75.56%
Simplified CNN	77.78%
CNN + LSTM	68.89%

Best Model: Simplified CNN with 77.78% test accuracy.
📈 Model Evaluation
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

💾 Model Saving
The trained model and class names are saved using:
- brain_cancer_model.keras
- class_names.npy

🚀 How to Run the Project
1. Download or clone the repository.
2. Open the Jupyter Notebook in Google Colab.
3. Upload the required dataset files.
4. Install the required libraries.
5. Run all notebook cells.
6. Train and evaluate the models.
7. Test predictions using MRI images.

🔮 Future Improvements
- Increase dataset size.
- Apply data augmentation.
- Implement transfer learning.
- Improve model accuracy.
- Develop a web application for image prediction.
- Evaluate using independent datasets.

⚠️ Disclaimer
This project is developed for educational purposes only. It is not a clinically validated medical diagnostic system and should not be used for medical decisions.

👨‍💻 Conclusion
This project demonstrates how deep learning techniques can be applied to brain MRI image classification. Three architectures were compared, and the Simplified CNN achieved the highest recorded test accuracy of 77.78%.