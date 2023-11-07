# Makemore-MPL
We implement a multilayer perceptron (MLP) character-level language model. In this video we also introduce many basics of machine learning (e.g. model training, learning rate tuning, hyperparameters, evaluation, train/dev/test splits, under/overfitting, etc.).


Links:
- makemore on github: https://github.com/karpathy/makemore
- jupyter notebook I built in this video: https://github.com/karpathy/nn-zero-t...
- collab notebook (new)!!!: https://colab.research.google.com/dri...
- Bengio et al. 2003 MLP language model paper (pdf): https://www.jmlr.org/papers/volume3/b...
- my website: https://karpathy.ai
- my twitter:  

 / karpathy  
- (new) Neural Networks: Zero to Hero series Discord channel:  

 / discord   , for people who'd like to chat more and go beyond youtube comments

Useful links:
- PyTorch internals ref http://blog.ezyang.com/2019/05/pytorc...

Exercises:
- E01: Tune the hyperparameters of the training to beat my best validation loss of 2.2
- E02: I was not careful with the intialization of the network in this video. (1) What is the loss you'd get if the predicted probabilities at initialization were perfectly uniform? What loss do we achieve? (2) Can you tune the initialization to get a starting loss that is much more similar to (1)?
- E03: Read the Bengio et al 2003 paper (link above), implement and try any idea from the paper. Did it work?
