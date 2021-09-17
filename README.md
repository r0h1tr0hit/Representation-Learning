# Representation-Learning

### Aim of this work is to learn different types of embeddings such as Word2vec, GloVe and fastText and compare their performance on the sentence classification task.  To learn which embeddings the network prefers for a given problem by predicting a weight for each embedding type.

## **Dynamic Meta-Embeddings for Improved Sentence Representations**

Dynamic meta-embeddings, a simple yet effective method for the supervised learning of embedding ensembles. The method is to giving networks access to multiple types of embeddings, allowing a network to learn which embeddings it prefers by predicting a weight for each embedding type, optionally depending on the context.

## Reference

Kiela et. al., Dynamic Meta-Embeddings for Improved Sentence Representations, EMNLP, 2018.

## **A C-LSTM Neural Network for Text Classification**

Convolutional neural network (CNN)
and recurrent neural network (RNN) are two
mainstream architectures for such modeling
tasks, which adopt totally different ways of
understanding natural languages. 

In this work,
we combine the strengths of both architectures
and propose a novel and unified model called
C-LSTM for sentence representation and text
classification. 

C-LSTM utilizes CNN to extract a sequence of higher-level phrase representations, and are fed into a long short-term
memory recurrent neural network (LSTM) to
obtain the sentence representation. 

C-LSTM
is able to capture both local features of phrases
as well as global and temporal sentence semantics. We evaluate the proposed architecture on sentiment classification task.

## Reference

Zhou et al, A C-LSTM Neural Network for Text Classification, arXiv:1511.08630 [cs.CL]
