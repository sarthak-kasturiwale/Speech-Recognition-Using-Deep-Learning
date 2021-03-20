# Speech-Recognition-Using-Deep-Learning
- Speech recognition is an interdisciplinary subfield of computer science and computational linguistics that develops methodologies and technologies that enable the recognition and translation of spoken language into text by computers.  
- It is also known as automatic speech recognition (ASR), computer speech recognition or speech to text (STT). It incorporates knowledge and research in the computer science, linguistics and computer engineering fields.
- In this project we have to predict which word was pronounced by using Machine Learing.

# Dataset Description
- The dataset was downloaded from https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data?select=test.7z
    train.7z.
- Contains a few informational files and a folder of audio files. The audio folder contains subfolders with 1 second clips of voice commands, with the folder name being the label of the audio clip.
- This is a set of one-second .wav audio files, each containing a single spoken English word. These words are from a small set of commands, and are spoken by a variety of different speakers.
- The audio files are organized into folders based on the word they contain, and this data set is designed to help train simple machine learning models.
- There are more labels that should be predicted. The labels you will need to predict in Test are yes, no, up, down, left, right, on, off, stop, go. Everything else should be considered either unknown or silence. The folder background_noise contains longer clips of "silence" that you can break up and use as training input.

# For this Project
- For this Project due to limited resources we have considered only 9 classes out of all the sample voices from the training set.

# End Results
- We have successfully trained the speech recognition model using CNN.
- We got accuracy of about 90.97% on training data while 89.78 on validation data. This shows that our model is not over fitting & predicting the exact class to which it belongs.
- For Recording voice at Runtime & Predicting it using the model please use "Voice Recording & Recognition" file.




