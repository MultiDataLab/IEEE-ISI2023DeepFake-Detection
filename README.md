# IEEE-ISI2023DeepFake-Detection
The codes and audio samples of the paper below:
Khanjani, Z., Davis, L., Tuz, A., Nwosu, K., Mallinson, C., Janeja, V. (2023). 
Intelligence and Security Informatics: IEEE International Conference on Intelligence and Security Informatics, ISI 2023,
Charlotte, North Carolina, USA, Oct 2-3, 2023 
##

Audio.txt = Access link to the audio clips of the dataset
##
LFCC_LCNN_baseline.py = python code of the paper's baseline (which is from ASVspoof 2021 challenge applied on our own dataset)
##
MLP Weka.model and lR.model = Weka model using EDLFs to predict fake vs real, Multi-layer Perceptron and Logistic Regression respectively
##
ensemble_model.ipynb =  after exporting the predictions of the pre-trained LFCC-LCNN model and EDLF-LR Weka model, we create and ensemble model, and this file is its codes
##
Audio_samples contains a few samples of our audio clips
