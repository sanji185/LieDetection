# LieDetection
# GOAL : True/Lie Detection Using Sequences from Video
Create Lie Detection Model using Deep Learning RNN (Final Yr USJP Research Project)

Steps:

01. Extract Keypoints from video using mediapipe fashmesh
02. Train an RNN LSTM DL Model
03. Make real time predictions using sequences



# How it Works
  01. Extract Keypoints from mediapipe fashmesh 
  2. Train a deep neural network with LSTM layers for sequences
  3. Perform real time True/ Lie Detection using OpenCV


# Contents of our notebook:

    01. Import and Install Dependencies
    02. Using Mediapipe (Google's open-source framework)
        - Given the original image and obtaining the values through the model.
        - Storing the keypoints values in the mediapipe into a variable.
        - Calculating blink rate (Euclidean distance).
    03. Extract Position Landmarks (Keypoints Values)
    04. Setup Folder for Collection
    05. Collect Keypoints Values for Training and Testing
    06. Preprocess Data and Create Labels and Features
    07. Build and Train LSTM Neural Network
    08. Make Predictions
    09. Save Weights
    10. Evaluation using Confusion Matrix and Accuracy
    11. Test in Real Time

# Full code details of the video:
[![IMAGE ALT TEXT HERE](https://user-images.githubusercontent.com/59352357/179909684-359e768a-1343-4e92-a507-d023e894616f.png)](https://www.youtube.com/watch?v=PSu1qiPmiRw)
