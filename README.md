# Age-and-Gender-Detection
An interesting Data science project which can be used to predict age and gender of any person in an image or video
![image](https://user-images.githubusercontent.com/129524929/234006946-932b26e4-a60b-4b03-887b-79bc827b9c29.png)

This project is a Python-based implementation of a model that can predict the age and gender of a person from an image or video. The model uses pre-trained deep learning models to detect and classify faces and predict age and gender.

The project contains below mentioned files:

#age_and_gender_Detection.ipynb: This file contains the code for the age and gender detection model. It uses OpenCV for face detection and pre-trained models for age and gender classification. The script can accept both image and video inputs and produces outputs with age and gender predictions.

#people.jpg: This file is a sample input file to test the model on image inputs

#people.mp4: This file is a sample input file to test the model on video inputs

->Model files

You can download the below mentioned files via this link -https://drive.google.com/uc?id=1T8Srjo1g82qrRC6A0IxhmZsm8kcWiEhq&export=download

#gender_net.caffemodel: Pre-trained model weights for gender detection.

#gender_deploy.prototxt: Model architecture for the gender detection model.

#age_net.caffemodel:Pre-trained model weights for age detection.

#age_deploy.prototxt:Model architecture for the age detection model.

#opencv_face_detector_uint8.pb: Pre-trained model weights for face detection.

#opencv_face_detector.pbtxt: Model architecture for the face detection model.

The age_gender_detector.ipynb script is designed to be modular and can be used as a starting point for building more complex age and gender detection systems. The script is well-commented and provides clear explanations of the functions and methods used in the code.

To run the code, users need to have Python 3 installed along with the required packages: OpenCV, numpy, and matplotlib along with the pre-trained models for age and gender detection which can be downloaded using the included link above

The output of the scripts will be saved in a new file with the age and gender predictions overlaid on the original input which is saved as output.avi(I converted the avi into mp4 and included it in the repository)

In the README file for the GitHub repository, users can find detailed instructions on how to install and run the code along with information about the model and the input and output formats. The README file should also include information on how to cite the repository if users plan to use the code for academic or research purposes.
