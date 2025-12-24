# Clickbait_NeuralNetwork
This repository contains the code for a project focused on classifying clickbait and non-clickbait titles using neural networks (MLP, RNN, Transformer).

## General Information
The use of clickbait headlines generates misinformation and undermines the credibility of news media, making it necessary to develop automated systems to identify them. This study classified headlines as clickbait or non-clickbait using three neural network models: an MLP with Bag of Words, an RNN with embeddings learned from scratch, and a pre-trained BERT transformer. A dataset of 32,000 headlines was used; the data were tokenized, vectorized, and split into training, validation, and test sets. All three models achieved high accuracy levels (95%–97%), with the RNN performing best due to its strong results and lower complexity. Additionally, LIME analysis showed that sensationalist words contribute decisively to the classification. The results confirm that even simple architectures can efficiently identify linguistic patterns characteristic of clickbait, as it is not a particularly complex task.

## Data
The dataset consists of 32,000 English-language news headlines, evenly split between clickbait and non-clickbait (16,000 each). Clickbait headlines come from outlets such as BuzzFeed, Upworthy, and ViralStories, while non-clickbait headlines originate from sources like The New York Times, The Guardian, and The Hindu.

The dataset was introduced by Abhijnan Chakraborty, Bhargavi Paranjape, Sourya Kakarla, and Niloy Ganguly. (2016) in “Stop Clickbait: Detecting and Preventing Clickbaits in Online News Media” (ASONAM 2016) and is available at: https://github.com/bhargaviparanjape/clickbait/tree/master/dataset
