# Real_time_Sign_Language_Detection
This project is written in Python and designed to detect sign language 
gestures in real-time through a webcam video stream. It uses a pre-trained 
keras model to identify three gestures: "hello", "I love you", and "thanks"... . 
The detected gestures are displayed on the screen, allowing the user to build 
sentences with them.

## Packages
The program uses the following packages:

* **OpenCV**: OpenCV is a popular computer vision library that is used for real-time computer vision applications. It is used in this project for webcam feed and information display.

* **MediaPipe**: MediaPipe is an open-source framework that provides cross-platform, customizable ML solutions for live and streaming media. It is used in this project for gesture keypoints detection.

* **Keras**: Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It is used in this project for machine learning.

## Usage
There are four main scripts in the program:

* `make_predictions.py`: Predicts the trained gestures and builds sentences.
* `folder_setup.py`: Builds the folder structure.
* `training_testing.py`: Trains the model with the "MP_Data" Keypoints and evaluates it.
* `setup_training_testing_keypoints.py`: Starts a training program where the user can input the gestures for the actions. The keypoints are then saved and can be used for training and evaluation.

## References
MediaPipe: https://mediapipe.dev/ <br>
Keras: https://keras.io/ <br>
OpenCV: https://opencv.org/ <br>

## Acknowledgements
