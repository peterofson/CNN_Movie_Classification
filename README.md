# Multi Label Image Classification to Identify Movie Genres
## Abstract
This study will look at images of movie posters to classify them according to genres.
Images and subsequent movie genres were taken from IMDB. Each movie can be assigned to at
most three genres. Performances of deep convolutional neural networks (CNN) are compared to
that of a smaller CNNs that implements random k label sets (RAKEL) for the classification
stage. The two algorithms had similar results with RAKEL being less accurate but required
drastically less time to train and was far easier to develop

## Introduction
Most people can infer the genre of a movie by glancing at the poster and observing the
colors, people, and landscape. The experiment in question is to construct an algorithm to analyze
movie posters and infer the genres they belong too. According to the drawn dataset, each movie
can belong to a series of genres and or just one, with a movie having a maximum of three genres.
Thus, making it a multilabel classification problem. A multilabel classification problem differs
from a multiclass problem as the latter is mutually exclusive. In other words, each sample is
assigned to one and only one class. Looking at the images, a movie may be assigned to Action,
Adventure and Fantasy all at the same time. Practical applications of determining genre labels
based on images is not promising, but perhaps a picture is worth a thousand words. If there is any
merit to that cliche, then this experiment will conclude that training a model on images versus
movie plots will produce a more robust and accurate model. 
