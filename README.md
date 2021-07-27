# python-chat-bot

### How to run
Install Jupyter or Jupyter notebook.
Install ```nltk, tflearn, numpy, tensorflow```
Open ```chat.ipynb``` with Jupyter and start running.

### What I learned:
Deep Neural Network is used interchangably with Multi Layer Perceptron (in tflearn)
Data wrangling techniques: tokenizing, POS labeling, chunking.
Labeling tokens based on POS labels
Categorizing training data
NLP techniques: stemming, lemmatizing


### What I don't understand:
Why do datasets require a dictionary having all ```True``` values?

## What's the most important thing?
Thoughts of correctness and statistical techniques are more important than blindly writing code. Jupyter helps a lot.

### Techniques
```I completed the job with flying colors!```
- Tokenizing: splitting strings into phrases or keywords. E.g. I, completed, the, job, with flying colors
- Phrase tokenizing: with flying colors (it's an idiom)
- POS labeling: I (subject), completed (verb), job (noun)...
- Stemming: completed -> complete (the original word)
- Lemming: completion -> completion, completed -> complete (one is a noun, one is a verb, also consider other factors)
