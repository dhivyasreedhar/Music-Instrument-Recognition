# Music-Instrument-Recognition


Abstract: Music Instrument Recognition is one of the main tasks of Music Information Retrieval. Identification of instruments present in an audio track provides information about the composition of music. Music instrument recognition in polyphonic music is a challenging task. Existing approaches use temporal, spectral, and perceptual feature extraction techniques to perform Music Instrument Recognition. In the proposed work a convolutional neural network and k nearest neighbour classifier framework are implemented to identify the musical instrument present in a monophonic audio file and the performance of the two models are compared. The model is trained on London Philharmonic dataset which consists of 6 different classes of musical instruments. Mel spectrogram representation is used to extract features for the Convolutional Neural Network model. For k-nearest neighbors, the Mel-frequency cepstral coefficients feature vectors are calculated to perform classification. This approach only works for monophonic music and cannot be used for polyphonic music. The model helps to label the unlabeled audio files so that manual annotation can be avoided. The model performed well with excellent result of 99.17% accuracy for the Convolutional Neural Network and 97% accuracy for the k-nearest neighbor architecture.



Paper submitted for publication.
