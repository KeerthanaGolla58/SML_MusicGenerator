# SML_MusicGenerator
Statistical Machine Learning - COMP540 project 

Music Generation using LSTMs and Transformers

Step -1 : Download the dataset (either from kaggle or hummdrum.org of kern/midi format

Step -2 : Take the preprocess file and change the path parameters accordingly and run the code to generate one preprocessed file.

Step -3 : Now usign this single preprocessed file lets generate the models - Take LSTM train py file,change required path parameters along with that change the no.of input nodes according to the no.of mapping generated with your particular dataset and run the file , it generates the LSTM model in h5 file.

Step -4 : Similar to LSTM, Take Transfomers py file and Generate Transformer hs file.

Step -5 : Now lets generate the melody using the LSTM h5 path. Take melody generator for LSTM and change the path variable to LSTM h5 path and it generated the midi file.

Step -6 : Similar to LSTM, Take melody generator for Transformer and give Transformer h5 path to generate the melody and save it in midi format.
