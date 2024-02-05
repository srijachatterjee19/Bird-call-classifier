# Bird-call-classifier

In recent times, there has been significant interest in the classification of bird sounds, primarily due to its diverse applications in fields such as ornithology, biodiversity monitoring, and soundscape analysis. A study was conducted to examine the application of deep learning models for the automated classification of bird sounds utilizes deep learning architectures, including Convolutional Neural Networks (CNNs) and Long Term Short Term Memory (LSTM). For training and evaluating the models, audio recordings from 10 commonly found bird species in Britain were employed, sourced from the Xeno-Canto dataset. Mel-Frequency Cepstral Coefficients (MFCCs) were utilized as the feature extraction technique for the models. The best-performing model achieved an impressive accuracy of 99%.


Steps involved:
1)Pre-processing 2)Feature extraction 3)Model training 4)Evaluating model. 

The bird song dataset initially consisted of 88 bird classes but it was sampled down to 10 as the first step. Subsequently, features were extracted from the audio signals and then used for training the CNN and LSTM models.CNN model achieved a accuracy of 99% , outperforming the LSTM model, which attained an accuracy of 50%.
