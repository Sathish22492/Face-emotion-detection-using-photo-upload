# Face-emotion-detection-using-photo-upload

#Objective:
  To develop comprehensive system that enables users to upload an image through a Streamlit
application and accurately detect and classify the emotion present in the image using Convolutional
Neural Networks (CNNs). This project aims to develop and design, implement, and optimize a complete
solution that integrates machine learning, computer vision, and user interface design.

#Project Scope:
  • End-to-End Development: You will be responsible for all aspects of the project, from
setting up the image upload interface to training the CNN model and delivering a polished, user-friendly
application.
  • Real-World Relevance: The project should address potential applications in areas such
as healthcare, education, and customer service, where emotion detection is valuable.

#Key Components:
  1. User Interface Development:
  • Design a Streamlit application that allows users to easily upload images. Do not allow
user to upload any other file except image. (Check format, size)
  • Focus on creating an intuitive, responsive interface with clear instructions for the user.
  2. Facial Detection Implementation:
  • Resize the image: Implement facial detection in the uploaded images using pre trained
models and your own model.
  • Explore options to enhance detection accuracy, precision,recall and F1 score, such as
refining detection thresholds or combining methods.
  3. Facial Feature Extraction:
  • Use tools like Dlib or Mediapipe to extract key facial landmarks.
  • Analyze how the accuracy of landmark detection impacts the emotion classification
process.
  4. Emotion Classification:
  • Train and fine-tune a CNN model using datasets such as FER-2013 available in the
Kaggle.
  #Dataset used:
I have utilized the FER 2013 dataset provided on Kaggle.
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

#Dependencies:
  Install these libraries before running the colab notebook.

1. numpy
2. streamlit
3. tensorflow-cpu
4. opencv-python-headless
5. streamlit-webrtc
