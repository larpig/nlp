# NLP

NLP is a repository of my personal NLP toolkit.

<a name="toc"/></a>
## Table of Contents  
<!--ts-->  
   1. [About the Project](#about)  
   2. [Word Embeddings](#wordEmbeddings)  
        2.1. [Static Word Embedding Models](#staticEmbeddings)  c
   * [References](#references)
<!--te-->  

<a name="about"/></a>
## 1. About the Project
[Back to ToC](#toc)


<a name="wordEmbeddings"/></a>
## 2. Word Embeddings
[Back to ToC](#toc)

A word embedding model is a type of natural language processing model that maps words or phrases from a vocabulary to a high-dimensional vector space.

They are typically used as input to other models, such as neural networks, to perform tasks such as language translation, text classification, and question answering.

<a name="staticEmbeddings"/></a>
###  2.1. Static Word Embedding Models

This class of word embedding models encompasses those models with the limitation that their embeddings do not capture the meaning of words in context, which is important for many NLP tasks. That is, the embedding of a word is fixed.

Examples of static word embedding models include word2vec (Mikolov at al., 2013), GloVe (Pennington at al., 2014), and fastText (Bojanowski at al., 2016).

Click here to access the notebook with explanations and implementation of the selected methods.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/larpig/nlp/blob/main/static_word_embedding_models.ipynb?usp=sharing)

<a name="references"/></a>
## References
[Back to ToC](#toc)


Although, in each notebook it is possible to find a vast amount of resources that served as a reference for the content created, in what follows, I share the original papers of the mentioned methods.

**Papers**:

* Mikolov, Tomas and Chen, Kai and Corrado, Greg and Dean, Jeffrey. 2013. Efficient Estimation of Word Representations in Vector Space, arXiv, <https://arxiv.org/abs/1301.3781.pdf>

* Pennington, Jeffrey and Socher, Richard and Manning, Christopher. 2014. GloVe: Global Vectors for Word Representation. In Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP), pages 1532–1543, Doha, Qatar. Association for Computational Linguistics. <https://aclanthology.org/D14-1162/>

* Bojanowski, Piotr and Grave, Edouard and Joulin, Armand and Mikolov, Tomas. 2016. Enriching Word Vectors with Subword Information, arXiv, <https://arxiv.org/abs/1607.04606>
