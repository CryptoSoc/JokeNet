# JokeNet: A CryptoSoc Attempt at OpenAI's [Requests for Research](https://openai.com/requests-for-research/#funnybot)

Why JokeNet?

It sounds cool.

# Background

Getting into artificial intelligence and machine learning can be daunting. With the myriad of online resources to choose from, it sometimes takes a little push to really get things going. This project aims to do so in a fun way.

The research question is as follows:

> Train a character-level language model on a corpus of jokes.

> To do so, use this 200k English jokes dataset or build your own (the larger the better; if you do so, please submit a pull request and we'll link to your dataset), implement a character-level LSTM (or use an existing implementation), train it on this dataset, and draw samples from it. If successful, the output from the LSTM should be actually funny.

As a subjective topic, jokes provide a fun way to get involved in crafting a machine learning model and coming up with novel ideas. It leads to thinking of what makes humans think like we do, how a ML model mimics that and what mistakes it can make.

# CryptoSoc Involvement

This project aims to include people as a team and thus it is being hosted by the UCT CryptoSoc. We want people to get involved - so clone this out, look through it and submit your pull requests!!

If anything doesn't make sense, create an issue right here on this very page so that we can help you (and anyone in the future with the same problem) out.

# Getting Started

Clone this repo locally to work on it:

```
git clone [THIS_REPO]
```

We have created some starting models to launch off of but they aren't necessarily the final thing. You are more than welcome to edit them or start fresh.

The paper that our RNN implementation comes from is here:
https://arxiv.org/pdf/1409.2329.pdf




# What you can do

There are many opportunities to improve this project. It really depends what piques your interest. I'll suggest a few ideas in different categories:

Algorithm:
* Add regularisation into the model
* Add dropout to improve robustness
* Allow words to be entered to prompt the algorithm for an output
* Decrease the learning rate over time

Data:
* Collect more data
* Determine what (as far as possible) makes a joke funny
* Create a test set (or model) that can verify the "funniness"

Visualisation
* Visualise training process

Other
* Make a UI to interact with the algorithm, or add your own jokes to the corpus
* Use a different ML framework like Keras
* Reimplement this in your favourite language

Philosophical
The philosophical and ethical debate surrounding AI is heating up - add to it with your own thoughts of how AI could aid in preventing discrimination or further it.
* An exploration of the positive and negative implications of the current dataset
* Biases in the data



# Computer Running Hot??

If your computer is struggling to train the models by itself and code optimization isn't your thing, don't worry, there's a cool way to get access to free GPU power!

I heard you like GPUs...

Google's version of Jupyter Notebook, [Colaboratory](https://colab.research.google.com), allows you to train models on fairly powerful GPUs.

Now instead of fluffing with code optimizations (which are indeed important and necessary) you can try your hand at GPU training and add that to your CV as well.

[Start Here.](https://colab.research.google.com)



# Fun With RNNs

https://youtu.be/3p10knivMRg?t=4m36s
