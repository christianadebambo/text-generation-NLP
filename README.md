# Text Generation with Markov Chains

This repository contains code for generating text using Markov Chains. The idea behind Markov Chains is to predict the next possible word based on the N previous words. By analyzing a given text corpus, the code generates new text that resembles the style and patterns of the original text.

Dataset taken from [Project Gutenberg](https://www.gutenberg.org/ebooks/1184)

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- random
- re
- collections
- nltk

## Code Explanation

The code performs the following steps:

- Imports the necessary libraries for randomization, regular expressions, counting, and natural language processing.
- Defines functions for reading a text file, collecting word pairs from the corpus, and generating text using Markov Chains.
- Reads the text corpus from a file and performs text cleaning operations.
- Collects word pairs from the text corpus to create a Markov chain dictionary.
- Generates text using the Markov chain dictionary.
- Prints the generated text.
- Provides options for higher-order Markov Chains and backoff.

## Results

The code generates text based on the provided text corpus and the selected Markov chain approach. It prints the generated text, which resembles the style and patterns of the original text.

## Instructions

To run the project code, follow these steps:

- Download the dataset.
- Install the required dependencies mentioned in the Prerequisites section.
- Run the code in a Python environment that supports Jupyter notebooks or execute the code in a Python script.

Note: Adjustments may be required in the code paths to ensure proper loading of the dataset.
