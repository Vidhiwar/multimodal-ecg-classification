# multimodal-ecg-classification

RESEARCH-PAPER = {Title: "Multi-module Recurrent Convolutional Neural Network with Transformer Encoder for ECG Arrhythmia Classification",

                           Link:  "https://ieeexplore.ieee.org/abstract/document/9508527",                                
                                   Authors: ["Duc Le",
                                                   "Vidhiwar Singh Rathour",
                                                          "Sang Truong", 
                                                                  "Quan Mai^, 
                                                                          Patel Brijesh; 
                                                                                  Ngan Le"]}  
                                                                                    
DIRECTORY-TREE = {multimodal-ecg-classification: "Root Directory"[

                                utils: "Directory: Utility based files",
                                examples: "Directory: github/awni/ecg/":[
                                          Cardiologist-level arrhythmia detection and classification in ambulatory electrocardiograms using a deep neural network"],
                                          
                                models: "Directory: DNN Models"[
                                       resnet_cnn.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, CNN, Word2Vec",
                                       resnet_lstm_phy2017.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, LSTM, CNN",
                                       resnet_lstm.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, LSTM, CNN",
                                       resnet_w2v.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, LSTM, CNN, Word2Vec",
                                       resnet_lstm_mitbih.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, LSTM, CNN, Word2Vec, Attention AYN",],
                                       
                                ecg_cnn.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, CNN, Resnet",
                                ecg_w2v.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, Word2Vec, Resnet",
                                ecg_lstm.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, LSTM, CNN, LSTM",
                                ecg_phy2017.py:"Python: Pytorch implememntation of Multimodal-ecg-classification, LSTM, CNN",
                                ecg_mitbih.py: "Python: Pytorch implememntation of Multimodal-ecg-classification, LSTM, CNN, Word2Vec, Attention AYN",
                                transform_data.ipynb: "Jupyter Notebook: Python implementation for Data Generation, and Preprocessing"]}
                                       
HOW-TO-USE = {Installation-Train-Val:[

                               Uno: "Make sure the required libraries (Torch, Panda, Tqdm, ... etc.,. are installed",
                               Dos: : "Use the examples directory to download and preprocess data.",
                               Tres: "Follow transform_data.ipyn to get data ready for training.",
                               cuatro: "Run python ecg_###.py to train on training data, and validate on validation data",
                               cinco: "By default results are saved in checkpoints directory"]}
                               
                               <img width="1007" alt="Screen Shot 2021-09-19 at 5 11 52 AM" src="https://user-images.githubusercontent.com/40514310/133923704-efda0f98-1a4a-4487-965e-a3d87b7f8ea2.png">

                               <img width="923" alt="Screen Shot 2021-09-19 at 5 14 02 AM" src="https://user-images.githubusercontent.com/40514310/133923729-d3792910-0809-4c4a-8971-8b93d3e3cfcc.png">

             
#  EOF
                     
                    
