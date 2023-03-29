# Classifying EEG Data using Neural Network Architectures (ECE ENGR 247)
In recent years, machine-learning techniques have been applied to electroencephalographic (EEG) datasets to extract features and apply models to various health settings. With recent advances in deep learning techniques, we want to see explore various neural network models to optimize the classification accuracy of the EEG data. Preprocessing and models such as CNNs, and RNNs were implemented over all subject and class data. A modest CNN model performed the highest accuracy of 84.7\%, with an improvement from 58.7\% after preprocessing and data generation using a variation autoencoder (VAE). 


# Data 
* note that EEG data is too large to house in the repository 
  * Original Data: https://www.bbci.de/competition/iv/
  * Data Description: https://www.bbci.de/competition/iv/desc_2a.pdf
* data was altered from the raw .gdf files for the class project

# Model Accuracies

Model | Classification Accuracy
--- | ---
CNN | **84.7\%**
Deep CNN | 81.4\%
Shallow CNN | 80.6\%
RNN - LSTM | 78.8\% 
RNN - GRU | 79.9\%
ConvLSTM | 82.4\%
ConvTRU | 82.7\%
