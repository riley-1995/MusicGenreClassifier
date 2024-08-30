# MusicGenreClassifier

This project builds and compares two machine learning models (Traditional Neural Network and Convolutional Neural Network) for music genre classification.

The dataset used to train the model for this project was created from the GTZAN dataset, which contains 1000 30-second .wav files, each containing a song clip. The song clips are categorized into folders by genre. This GTZAN dataset was pre-processed and exported to a .json file (data.json) in order to be used as input for the machine learning models. The pre-processing step was done in a jupyter notebook called 'Pre-ProcessGTZANforGenreClassification.ipynb'. This pre-processing notebook contains explanatory information about the pre-processing stage as well as information about Mel Frequency Cepstral Coefficients (MFCC's), which will be the primary input for the machine learning model. The model building, training, optimizing, and comparison is done in the jupyter notebook 'MusicGenreClassification copy.ipynb'.

#### Acknowledgements

This project is created by following along with the tutorials from the Youtube series "Deep Learning (for Audio) with Python" by creator Velerio Velardo - The Sound of AI: https://www.youtube.com/playlist?list=PL-wATfeyAMNrtbkCNsLcpoAyBBRJZVlnf

The GTZAN dataset can be found here: https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

Note: Due to an error with file ...Data/genres_original/jazz/jazz.00054.wav in the original GTZAN dataset, during pre-processing of the dataset this file is skipped.
