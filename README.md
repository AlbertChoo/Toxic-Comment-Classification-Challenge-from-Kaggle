# Toxic-Comment-Classification-Challenge-from-Kaggle
To identify and classify toxic online comments

The datasets are too big to uploaded into this repo, even in `.zip` format, pls find and download it on Kaggle, link: [https://www.kaggle.com/c/nlp-getting-started/data](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data)

To prevent any error, I used old version of tensorflow==2.14.0 and tensorflow_hub==0.15.0.

Basic Steps in .ipynb file:
1. Check Version and Load Data (check for missing data, value counts, etc) and Helper Functions
2. Visualize Data, Split train test datasets
3. Convert texts to numbers (Tokenization)
4. Build Model (Baseline 1 & 2, USE Transfer Learning, Conv1D with Character Embeddings, GRU)
5. Save Model
6. Making Predictions on Test dataset

I did not submit predictions.csv to Kaggle due to some reason, you may follow the submission format based on Kaggle, I stop at GRU since my computer capability is not that good, and it spend me quite long time. It can be improved of course, try LSTM, BiLSTM, CNN, Transformer Models such as BERT or RoBERTa, and any hybrid models (e.g. CNN-LSTM, Transformer-based models with CNN or RNN Layers). and lastly ensemble models.
