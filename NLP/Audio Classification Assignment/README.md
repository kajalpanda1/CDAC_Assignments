Problem Statement::

Audio classification is the process of listening to and analyzing audio clips. This process is a crucial part in applications like virtual assistants, automatic speech recognition, and text to speech applications. Feature extraction is the basic yet most important step while working with Audio files.

These are some listed features of an audio file:
1. Zero Crossing Rate
2. Spectral Centroid
3. Spectral Rolloff
4. MFCC - Mel-Frequency Cepstral Coefficients
5. Chroma Frequencies

For audio classification, different features of an audio signal can be processed through different Machine Learning Classification Algorithms as well as Deep Neural Networks.
Here, the MFCC features of the audio clips has been extracted. These MFCC features of the audio clips has been recorded in a .csv file. Then the model has been trained using Long-Short Term Memory(LSTM).

Dataset Used::

The dataset used is the famous GTZAN music genre dataset that has 10 categories of music genre like blues, classical, pop etc. 
Each 10 categories have 100 audio files with .wav format.
