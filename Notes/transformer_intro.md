# Transformer intro

## Transformer
A DNN arch. introduced in Attention is all you need (2017.)  
GPT arch. is heavily based on this.  
Originally for machine translation from English to German.  

## Simplified arch.
1. Input text is obtained
2. Preprocessing - tokenization (breaking the sentence into tokens and assigning an id to each.)
3. Encoder - Token ids converted into vector embeddings to capture semantic information.
4. Decoder - partial output text + embeddings to decode one word at a time. 

## Self-attention
A key part of transformers which allows model to weigh the relative importance of different words / tokens.  
Enables capturing of long range dependencies.

## BERT - Bidirectional Encoder Representations from Transformers
* Predicts hidden words in a sentence.
* Better for sentiment analysis.
* Contains only encoder.

## GPT
* Generates new word.
* Contains only decoder.

Not all transformers are LLMs - Vistion Tranformer (ViT)  
Not all LLMs are transformers; LLMs can be RNNs or LSTMs as well."