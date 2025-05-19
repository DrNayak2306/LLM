# How does GPT-3 work?

## Zero shot learning
Model prediction only based on natural language description, and no assistance.

## One shot learning
Natural desc. + 1 example

## Few shot learning
Natural desc. + n examples

GPT-3 is a few shot learner.  
GPT-4 performs very well at few shot learning, but can handle zero shot.

Cost of pretraining GPT-3 is around $4.6M, and has 96 transformer layers, 175B params.  
GPT-3 dataset

__Token__ - A unit of text which the model reads.

LLaMA (open source) is almost as good as GPT-4 (closed source)

## Self-supervised learning through autoregressive model
The next word in the sentence is the label

## Emergent behavior
Ability of a model to perform tasks which it wasn't trained to perform.  
Recommended area of research.