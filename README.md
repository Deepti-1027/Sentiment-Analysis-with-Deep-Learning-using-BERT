# Sentiment Analysis with Deep Learning using BERT
**Task 1:** Exploratory Data Analysis and Preprocessing

**Task 2:** Training/Validation Split

**Task 3:** Loading Tokenizer and Encoding our Data

**Task 4:** Setting up BERT Pretrained Model

**Task 5:** Creating Data Loaders

**Task 6:** Setting Up Optimizer and Scheduler

**Task 7:** Defining our Performance Metrics

**Task 8:** Creating our Training Loop

**Task 9:** Loading and Evaluating our Model

Sentiment Analysis with Deep Learning of Twitter Smile emotion dataset, using BERT, HuggingFace, PyTorch, to classify tweets emotions as variant smileys, and evaluated model via F-1 score metrics.

### Objective:

**Perform Sentiment Analysis, to classify the emotion of tweets, using pretrained BERT model.**

## What is BERT?

BERT is a highly used Machine Learning model in NLP(Natural Language Processing) subspace. It is a large scale model that has transformers inside it. It's an advancement of RNN (Recurrent Neural Network) i.e., It's able to parallelize processing and training at inference (similar to CNN, where, input size is fixed). As earlier in RNN, we might have to process each word independently and now, we can do things in parallel. And, that's the real goal. BERT is trained on unsupervised data, i.e., data with no labels, from a huge corpus of data present over Intenet.

BERT Scope and Problems:

BERT can be adapted to do question-answering, multiple choice, sentence completion and predicting missing words.

**Problems are:**

1.) It's Speed. BERT can be slow for production.

2.) It might have biases, as data it's trained on is from Internet i.e., Internet data might more provide data that represnts wealthier countries more than the poorer ones. e.g., data might be more available from countries like- U.S., U.K. compared to South Africa or Zimbabwe.
