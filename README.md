# speechRecognitionCNN
Dataset for this project can be found here :  http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz. It's licensed under the Creative Commons BY 4.0 license. This is a set of one-second .wav audio files, each containing a single spoken English word. These words are from a small set of commands, and are spoken by a variety of different speakers. The audio files are organized into folders based on the word they contain, and this data set is designed to help train simple machine learning models.


In the SRUsingMFCC folder you can find the code for speech recognition using MFCC features. A shallow CNN with 2-3 convolution layers and a fully connected layer is used. Classification has been done using 4 classifiers. 
1. General softmax layer
2. K-nearest Neighbour
3. Random Forest Classifier
4. Support Vector Machine

In the SRUsingSpectrograms folder you can find the code for speech recognition using spectrograms. The data is first converted into spectrograms of size 128X32 and fed into the input layer of a deep CNN. Model was trained for 5 Epochs. Use the necessary lines only, because some lines are not in order. 

# Most of the code in this repo can be found all over the internet, as we were beginners in this domain and were trying to figure out how things work out by manipulating and tuning few variables here and there. 

Due Credits: 
1. https://github.com/cmaroti/speech_recognition
2. https://github.com/shibuiwilliam/Keras_Sklearn

Hit me up if you find something fishy. Peace :)
