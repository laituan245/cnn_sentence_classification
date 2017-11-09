## Convolutional Neural Networks for Sentence Classification
This code is a slightly modified implementation of the model CNN-nonstatic mentioned in the paper [Convolutional Neural Networks for Sentence Classification](http://arxiv.org/abs/1408.5882) (EMNLP 2014). However, other models (e.g, CNN-static) can easily be implemented by tweaking the code in *model.py*.

There are differences:
* This implementation uses Glove instead of Word2Vec.
* This implementation does not use the L2 norm constraint.

### Example output
GPU output:
```
===> Iter 500: | Train acc 0.5755 | Test acc 0.7188
===> Iter 1000: | Train acc 0.7207 | Test acc 0.7348
...
...
===> Iter 5500: | Train acc 0.9816 | Test acc 0.7910
```
