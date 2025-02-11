Plant Disease Detection System for Sustainable Agriculture
This project is a Plant Disease Detection System built using Streamlit and TensorFlow. The system predicts potato diseases (Early Blight, Late Blight, or Healthy) using a deep-learning model.

# Features
1. User-friendly Interface: Built with Streamlit for easy interaction.
2. Deep Learning Model: Utilizes a trained Keras model for disease classification.
3. Image Upload & Prediction: Users can upload an image of a potato leaf, and the model predicts its disease status.
4. Sustainable Agriculture: Helps farmers detect diseases early for better crop management.

# Installation
1.Clone the repository
git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName
2.Install dependencies
pip install -r requirements.txt
3.Run the application
streamlit run web.py

# How to Use
Run the Streamlit app using streamlit run web.py.
Choose "Disease Recognition" from the sidebar.
Upload an image of a potato leaf.
Click "Predict" to get the classification result.
The model predicts one of the following classes:
A. Potato___Early_blight
B. Potato___Late_blight
C. Potato___Healthy

#Requirements
Ensure to install:

Python 3.7+
TensorFlow
Streamlit
NumPy

# Model Training
The model is trained using TensorFlow Keras on a dataset of potato leaf images. The training process is documented in Train_potato_disease.ipynb.

# Future Improvements
Support for more plant diseases.
Deploying the model on the cloud for real-time predictions.

#Contribution
Feel free to contribute! Fork the repository, make your changes, and submit a pull request.
