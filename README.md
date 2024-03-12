# BERT embeddings generator
Repo for embed and classify texts 🫶

To make the classification on this data set, we use as a features the 768 entires of the embbedings vectors on BERT (CLS tokens) that has the Sentence-level Representation. The [CLS] token is specifically pre-trained to capture the overall meaning of a sentence. Its embedding often serves as a good general-purpose representation of the input text. 

This features try to predict the class of each category that they are labelled using a neuronal network with two hidden layers using pytorch framework

#### Notebooks

* [MMLU dataset attemp](https://github.com/DLesmes/bert_embeddings_generator/blob/main/bert_embedding_generator.ipynb)
* [yahoo answers dataset attemp](https://github.com/DLesmes/bert_embeddings_generator/blob/main/bert_embedding_generator_yahoo_answers.ipynb)

## Other links

* [BERT: Pre-training of Deep Bidirectional Transformers for
Language Understanding](https://arxiv.org/pdf/1810.04805.pdf)
