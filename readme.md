Readme
======

!["I want AI to do my laundry and dishes so that I can do art and writing, not for AI to do my art and writing so that I can do my laundry and dishes". Author and videogame enthusiast Joanna Maciejewska nails it (although bathroom cleaning goes ahead of laundry and dishes)](images/I_want_AI_to_do_my_laundry_and_dishes.webp)

Contents of the course
----------------------

1. General introduction
   1. Large Language Models like ChatGPT are the talk of the town
   2. Algorithms vs artificial intelligence = instructions vs learning
2. Neuron and Perceptron
   1. Link between brains (neuron) and AI (perceptron) - McCulloch & Pitts (1943)
   2. Supervised learning, lineair classifier, delta rule
   3. Show OR, AND & XOR (doesn't work) - Minsky & Papert (1969)
     [Jupyter Notebook](week-2-single-perceptron-or.ipynb)
     [Google Colab](https://colab.research.google.com/github/reimf/keuzevak-hoe-werkt-ai/blob/main/week-2-single-perceptron-or.ipynb)
   4. Not much till 1980
3. Multilayered perceptrons
   1. Show XOR with preset weights
      [Jupyter Notebook](week-3a-preset-multilayered-perceptron-xor.ipynb)
      [Google Colab](https://colab.research.google.com/github/reimf/keuzevak-hoe-werkt-ai/blob/main/week-3a-preset-multilayered-perceptron-xor.ipynb)
   2. No training algorithm for multilayered perceptrons with the heaviside step-function exists
   3. Sigmoid, backpropagation, gradient descent
   4. XOR with MLP
      [Jupyter Notebook](week-3b-trainable-multilayered-perceptron-xor.ipynb)
      [Google Colab](https://colab.research.google.com/github/reimf/keuzevak-hoe-werkt-ai/blob/main/week-3b-trainable-multilayered-perceptron-xor.ipynb)
4. Optical Character Recognition with ANN
   1. MNIST digits
   2. Preprocessing the data, postprocessing the prediction
   3. Training set, test set, validation set, local minima, generalization
5. Language model?
   1. Style of Shakespeare?
6. The truth is in the data
   1. Different models (Artificial Neural Networks, Recurrent Neural Networks, Support Vector Machines, etc)
      1. Lots of fiddling (size, architecture, choice of training algorithm, etc)
      2. No explanation for a prediction
      3. Different models lead to the same results
      4. It all depends on the data
   2. The quality of the data
      1. Bias and Discrimination
      2. Transparency, Accountability
      3. Creativity and Ownership
      4. Social Manipulation and Misinformation
      5. Privacy, Security, and Surveillance
7. The current state of AI
   1. Applied in real-world situations in many niches (give examples)
   2. General AI: generate text (ChatGPT), images (DALL-E), music (Udio), speech-to-text, text-to-speech, etc
   3. AI in science fiction
   4. Can AI ever be truly self aware?


Further material
----------------

- https://en.wikipedia.org/wiki/Perceptron
- https://dev.to/trekhleb/interactive-machine-learning-experiments-3ga7
- https://www.kaggle.com/code/prashant111/comprehensive-guide-to-ann-with-keras
- https://www.geeksforgeeks.org/implementation-of-perceptron-algorithm-for-xor-logic-gate-with-2-bit-binary-input/
- https://thewalrus.ca/ai-hype/