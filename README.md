# DeSMOG: Climate Change Stance Classification in News Media
Final Project for W266 Natural Language Processing, Spring 2022

### Data Cleaning and EDA
EDA of the DeSMOG dataset and preparation for 5-fold cross validation training. 

### Baseline
Baseline implementation of BERT using pooled output for classification and parameters from DeSMOG paper.

### Weighted BERT
Extension of baseline BERT leveraging predicted class weights to customize loss function. 

### BERT-CNN
Weighted BERT leveraging two versions of CNN to fine-tune BERT outputs leveraging the sequential output and hidden layers. 

### CNN-LSTM
Exploration of static-embedding approach to classify DeSMOG dataset using word2vec embeddings. (WIP, not referenced in final project writeup.) 

### Model Performance EDA
Analysis of fine-tuned BERT model failure modes. 