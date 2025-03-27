my cnn project
# Potato Disease Classification using CNN

## Project Overview
This project implements a Convolutional Neural Network (CNN) to classify potato leaf diseases using deep learning. The model is trained on an image dataset containing healthy and diseased potato leaves, aiming to assist farmers and agricultural experts in early disease detection.

## Dataset
The dataset consists of images categorized into the following classes:
- Healthy
- Early Blight
- Late Blight

Images are preprocessed and augmented to improve model robustness.

## Tech Stack & Libraries
- Python
- TensorFlow/Keras for CNN model
- OpenCV/PIL for image preprocessing
- Pandas & NumPy for data handling

## Model Architecture
The CNN consists of multiple convolutional layers, batch normalization, max pooling, and fully connected layers, trained using categorical cross-entropy loss 


## Results
The model achieved **97.66% accuracy** on the test dataset. The confusion matrix and sample predictions are provided

## Future Improvements
- Implement real-time disease detection with a mobile app
- Fine-tune with transfer learning for better accuracy
- Deploy as a web service using Flask or FastAPI

## References
- Dataset: [Kaggle/PlantVilage](#https://www.kaggle.com/datasets/arjuntejaswi/plant-village?select=PlantVillage)


## Author
**Aneesha** | Remote Sensing & Machine Learning Enthusiast