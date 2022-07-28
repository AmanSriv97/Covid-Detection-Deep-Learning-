# Covid-Detection-Deep-Learning-
This repository contains the Deep Learning CNN code implementation which is used to predict covid using Cough sounds.

The cough sound Data was taken from IISC Coswara dataset.
The sound samples were first pre processed and then padded and filtered to make each sample of equal length .
Then the audio files were converted into spectro grams which look like this. 

spectrogram.jpg
https://www.google.com/url?q=https://github.com/AmanSriv97/Covid-Detection-Deep-Learning-/spectrogram.jpg

This spectrogram is then sent to the CNN model in the input layer and then the CNN classifies it between 0 and 1.
