# Image-Classification Using Pre-trained CNN and Denoising-autoencoders

Major Steps & Theory Involved--


1. I have Downloaded UCMerced_LandUse dataset from github & split the folders for training & valiidation in ratio 0.8 & 0.2(customizable).
2. I have used Alex-net as pretrained model for feature extraction from UCMerced_LandUse dataset. 
3  Autoencoder architecture has been prepared according to use case.
4. Then Denoising ayutoencoders have been used to introduce noise in dataset so that auto encoders can do training along with noise to make    model robust. 
5. Adam as optimiser and training & validation accuracy as performace metric has been used.
6. In 20 epochs accuracy for validation is around 90% which further increase till 95% on increasing number of epochs.


