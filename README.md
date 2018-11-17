 # Papers
A collection of useful articles and research papers about data science.

## Table of Contents
1. [A Machine Learning Framework to Identify Students at Risk of Adverse Academic Outcomes](#1-a-machine-learning-framework-to-identify-students-at-risk-of-adverse-academic-outcomes)
2. [Discovering Types for Entity Disambiguation](#2-discovering-types-for-entity-disambiguation)
3. [Applied Machine Learning at Facebook: A Datacenter Infrastructure Perspective](#3-applied-machine-learning-at-facebook-a-datacenter-infrastructure-perspective)
4. [Aequitas: An Open Source Bias Audit Toolkit for Machine Learning Developers](#4-aequitas-an-open-source-bias-audit-toolkit-for-machine-learning-developers)
5. [Exploratory data analysis and visualization of song lyrics](#5-exploratory-data-analysis-and-visualization-of-song-lyrics)
6. [What does your smartphone know about you?](#6-what-does-your-smartphone-know-about-you)
7. [LSTM: Long short-term memory](#7-lstm-long-short-term-memory)
8. [Some Like It Bot](#8-some-like-it-bot)
9. [Estimating an Optimal Learning Rate For a Deep Neural Network](#9-estimating-an-optimal-learning-rate-for-a-deep-neural-network)
10. [What do machine learning practitioners actually do?](#10-what-do-machine-learning-practitioners-actually-do)
11. [Practical guide to hyperparameters search for deep learning models](#11-practical-guide-to-hyperparameters-search-for-deep-learning-models)
12. [Deploy a Keras model using TensorFlow Serving and Flask](#12-deploy-a-keras-model-using-tensorflow-serving-and-flask)
13. [Twitter turing test: Identifying social machines](#13-twitter-turing-test-identifying-social-machines)
  
## How to Read a Paper
[A paper](papers/How-to-Read-a-Paper.pdf) explaining the **three-pass approach**: a way for reading academic papers efficiently.

> The *first pass* gives you a general idea about the paper.  
The *second pass* lets you grasp the paper’s content, but not its details.  
The *third pass* helps you understand the paper in depth.

### 1. [A Machine Learning Framework to Identify Students at Risk of Adverse Academic Outcomes](papers/A-Machine-Learning-Framework-to-Identify-Students-at-Risk-of-Adverse-Academic-Outcomes.pdf)
  * Comparison of multiple algorithms (logistic regression, random forests, SVMs and others)
  * Evaluation of said algorithms using ROC curves, precision/recall, empirical risk
  * Finding similarities between outputs using Jaccard similarity metric
  * Identifying mistake patterns (e.g. high GPA/high absence rate or low GPA/low absence rate)
### 2. [Discovering Types for Entity Disambiguation](https://blog.openai.com/discovering-types-for-entity-disambiguation/)
  * Training a neural network to understand the context of a word (e.g. "Jaguar" > the car? the animal?)
  * Understanding the context of *X* word based on surroundings of original text + Wikipedia's categories and links
  * Interesting data-gathering schema, using Wikidata's knowledge graphs
### 3. [Applied Machine Learning at Facebook: A Datacenter Infrastructure Perspective](papers/Applied-Machine-Learning-at-Facebook_-A-Datacenter-Infrastructure-Perspective.pdf)
  * An approach to deploying machine learning and deep learning models in real-time
  * Insightful descriptions of Facebook's workflow: data > training algorithms > deployment / research
  * Very interesting details about Facebook's algorithms (Lumos, Facer, News Feed...)
### 4. [Aequitas: An Open Source Bias Audit Toolkit for Machine Learning Developers](http://dsapp.uchicago.edu/aequitas/)
  * Aimed mainly at social-good data applications (i.e. AI that affects people in some way).
  * Machine learning algorithms have bias—yes, all of them. 
  * This tool helps developers evaluate and visualize bias in their algorithms.
### 5. [Exploratory data analysis and visualization of song lyrics](https://blancas.io/song-lyrics/)
  * Extensive in-depth analysis and natural language processing techniques
  * Features language detection, sentiment analysis, chloropeth maps and more graphs
  * Answers interesting questions like how lyric topics changed over time  
### 6. [What does your smartphone know about you?](https://www.kaggle.com/morrisb/what-does-your-smartphone-know-about-you)
  * A controlled experiment where 30 participants performed daily activities holding a smartphone
  * Thorough exploratory data analysis
  * Interesting results with code
### 7. [LSTM: Long short-term memory](https://skymind.ai/wiki/lstm)
  * A not-so-long article explaning the importance of LSTMs in Recurrent Neural Networks
  * Comprehensible every-day-life analogies 
  * Also explains LSTM Cells for solving the [*vanishing gradient problem*](https://en.wikipedia.org/wiki/Vanishing_gradient_problem)
  * Strong focus on text generation and NLP
### 8. [Some Like It Bot](https://fivethirtyeight.com/features/some-like-it-bot/)
  * An article exploring the role of AI in entertainment
  * Portrays the AI-human relationship
  * An inspiration for [ghostwriter](https://github.com/Juanets/ghostwriter) and [textgenrnn's interactive mode](https://github.com/minimaxir/textgenrnn/pull/52)
### 9. [Estimating an Optimal Learning Rate For a Deep Neural Network](https://towardsdatascience.com/estimating-optimal-learning-rate-for-a-deep-neural-network-ce32f2556ce0)
  * Explains a bit about the importance of the learning rate parameter
  * Lists different ways of tuning learning rate, and proposes a "smarter way"
  * Provides Python implementation with plots (learning rate vs. loss)
### 10. [What do machine learning practitioners actually do?](http://www.fast.ai/2018/07/12/auto-ml-1/)
  * A wide perspective of working in the machine learning industry
  * Lists complications when building data products
  * Common machine-learning-practitioner activities
### 11. [Practical guide to hyperparameters search for deep learning models](https://blog.floydhub.com/guide-to-hyperparameters-search-for-deep-learning-models/)
  * Explains limitations of hyperparameter optimization
  * Breaks down different hyperparameter search techniques
  * The power of stopping earlier
  * Promises a good, potential future with Google's AutoML
### 12. [Deploy a Keras model using TensorFlow Serving and Flask](https://towardsdatascience.com/deploying-keras-models-using-tensorflow-serving-and-flask-508ba00f1037)
  * Explains how to use and implement a TF Serving server
  * Code to transform a Keras model (`.hdf5`) into a TensorFlow model (`.pb`)
  * Setup of a Flask server to consume the Serving server through an API (probably doable in Django)
  * Handling of Cross-Origin requests (author uses Angular as an example)
### 13. [Twitter turing test: Identifying social machines](/papers/Twitter-turing-test_-Identifying-social-machines.pdf)
  * A supervised machine learning approach for twitter bot detection
  * Explains how they built the corpus and feature extraction
  * Demonstrates proposed classifiers and evaluates their performance
  * Applies gained knowledge to create a browser extension that detects potential spam in real-time
