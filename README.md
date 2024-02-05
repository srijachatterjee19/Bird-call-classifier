# Bird-call-classifier

In recent times, there has been significant interest in the classification of bird sounds, primarily due to its diverse applications in fields such as ornithology, biodiversity monitoring, and soundscape analysis. A study was conducted to examine the application of deep learning models for the automated classification of bird sounds utilizes deep learning architectures, including Convolutional Neural Networks (CNNs) and Long Term Short Term Memory (LSTM). For training and evaluating the models, audio recordings from 10 commonly found bird species in Britain were used. Mel-Frequency Cepstral Coefficients (MFCCs) were utilized as the feature extraction technique for the models. The best-performing model achieved an impressive accuracy of 99%.


## Steps-involved:

1)Pre-processing 
2)Feature extraction 
3)Model training 
4)Evaluating model. 

The bird song dataset initially consisted of 88 bird classes but it was sampled down to 10 sourced from the Xeno-Canto datasetaset as the first step. Subsequently, features were extracted from the audio signals and then used for training the CNN and LSTM models.CNN model achieved a accuracy of 99% , outperforming the LSTM model, which attained an accuracy of 50%.

  <img src="https://github.com/srijachatterjee19/Bird-call-classifier/assets/84346422/a6224e33-26ff-456f-bba6-413688be9718" title="Steps" alt="Steps" width="476" height="541"/>&nbsp;

## Results for CNN Model:


The loss and accuracy curves were in close proximity,indicating there was no over-fitting phenomenon and revealing the good fitting degree of the network.The model evaluation results with metrics precision, recall,F1-scores for each 10 bird classes .It was observed that both models achieved different classification performances for distinct bird classes.The confusion matrices were plotted has been shown below for the CNN model.The x-axis of the matrix represents the Predicted bird class labels and the y-axis represents the actual bird class labels.The findings obtained from the CNN model demonstrate a strong alignment along the diagonal of the matrix,indicating a high degree of accurate identification for the majority of bird classes. This suggests that the CNN model is likely to produce precise results when tested on unseen data. Only a few samples were confused with other classes;1 Barn Swallow sample was confused with Common Chaffinch,1 Barn Swallow sample with Garden Warbler and 1 Garden Warbler with Eurasian skylark.

  
  <img src="https://github.com/srijachatterjee19/Bird-call-classifier/assets/84346422/96ebfddd-c4d8-48fc-9d48-272fe2f33db8" title="result-CNN" alt="result-CNN" width="588" height="486"/>&nbsp;


