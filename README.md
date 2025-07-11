# English-To-Persian-LSTM
A simple sequence-to-sequence LSTM model for English-to-Persian translation, trained on a subset of the Global Voices En–Fa parallel corpus using word embeddings like Word2Vec.

##  Project Overview

1. **Tokenization & Embedding**:
   Tokenize English and Persian sentences using tools like `sentencepiece` and convert them to vectors using Word2Vec.

2. **Vocabulary Construction**:
   Build separate vocabularies for English and Persian, including special tokens (`<pad>`, `<eos>`, etc.).

3. **Data Preparation**:
   Preprocess and organize the dataset into tokenized, indexed, and padded tensors ready for training.

4. **Model Architecture**:
   Implement a Seq2Seq translation model using LSTM layers to translate English sentences into Persian.

5. **Training**:
   Train the model using cross-entropy loss and evaluate its performance on test data.

