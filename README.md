# audio_recognition_dnn
a baseline MLP model to classify given audio input into digits (0-9) , kind of audio mnist

dataset to be downloaded : 

https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data


literature reading:

what is spectogram ??
https://wikidelia.net/wiki/Spectrograms#Logarithmic_frequency_axis

References for implementing a model:

https://towardsdatascience.com/speech-classification-using-neural-networks-the-basics-e5b08d6928b7
https://www.kaggle.com/davids1992/speech-representation-and-data-exploration

TODO in the order of priority :

1) normalize signal and dimension reduction
2) grid search/ try the border pair method to find out number of layers needed for minimal MLP architecture 
3) change input/ validation/ data section for modularity ( use generator)
4) save checkpoints and train for longer epochs
5) compare other architectures.

