# DSCI-6004-03-NLP-Project
NLP Final Group Project on News Category Classification using NLP

Project Summary:
This project focuses on multi-label document classification of online news articles into one or more of 10 categories including politics, business, sports and technology. We leverage deep neural networks including CNNs, RNNs and pretrained transformer networks like BERT and RoBERTa for natural language understanding. The models are trained in TensorFlow on a 216,000 article dataset to predict relevant tags for unseen news data. 

The latest state-of-the-art RoBERTa model achieves 90% accuracy, significantly higher performance than baseline RNNs, demonstrating the power of transfer learning from large-scale language modeling. Analysis also revealed strengths and weaknesses of each architecture in capturing semantics, relationships and context within textual data for improved inference.

Usage Instructions:
1. Install Python 3.6+, Tensorflow 2.2+, datasets, transformers and other libraries
2. Download preprocessed news data and category labels from this Kaggle repository - https://www.kaggle.com/datasets/rmisra/news-category-dataset
3. Import data, tokenize using subword tokenization and pad sequences to fixed length
4. Construct/import the RNN (LSTM/BiLSTM/GRU) and transformer (BERT/RoBERTa) model architectures 
5. Train models for 15+ epochs monitoring loss metrics 
6. Evaluate accuracy, precision, recall on held-out test data
7. Perform error analysis by inspecting confusion matrix and classification reports
8. Visualize model performance plots and activation outputs
9. Tune hyperparameters like learning rate, optimizers and batch size for improved performance
10. Ensemble and blend models to improve robustness  

This project offers a guided deep NLP research template from dataset to deployment - facilitating reproducibility for students and scientists new to advanced neural text classification techniques leveraging transfomer networks and transfer learning. Detailed documentation is provided on data prep, model architectures, training methodology, evaluation metrics and inferences for each experiment.
