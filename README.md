# Artificial Intelligence Lab Reporsitory

**Project SpaceModel**

- Electronic book source: www.gutenberg.org
- Neural Network source : www.neuralnetworksanddeeplearning.com

### Description of project

Using an electronic book, we choose a random chapter and remove
all blank spaces between words. Example "The brown fox jumps"
will be converted into "Thebrownfoxjumps". Next we will teach
a model to utilize the rest of the chapters in the book and create 
an English model to learn from and correct the target chapter. 
This requires the use of a recursive neural network and unsurpervised
learning techiqnue.

### Team

- Michael M.Meskhi
- Enes Kemal Ergin
- Bedir Tapkan
- Utku Yurter
- Hamza Emra
- Inamullah Rasuna

###Source of project idea
   ----------------------

Take a book in electronic format like a Jane Austen book from project Gutenberg. Take the last chapter in that book. Remove all the spaces.

Now write a computer program to put all the spaces back. You can easily count how many it got right since you have the original text.

1. Do it using Hidden Markov Models based on a frequency dictionary of English.

2. Do it using a Genetic Algorithm using an oracle based on the same frequency dictionary.

3. Do it using machine learning to learn a Model of English based on all the other chapters of the book as a training corpus using only unsupervised learning.

You can expect to get about 85% correct using the first two methods.
If you get results better than 95% correct, talk to me.
If you get 99.99% correct using #3 then you have created a true AI.
