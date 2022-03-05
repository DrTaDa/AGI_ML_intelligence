### Classifiers are already interpretable

A lot of fuss is being made about "interpretable AI", with the goal of opening up the "black box" of AI.

Let's say I train a classifier to differentiate between categories of animals.
These categories, like any of the concepts we use to think as humans, have appeared in through reinforcement learning.
These categories, or concepts, appear because they are useful for planning, reasoning or communication.
And we communicate our categories to the other members of our species using words, that are labels that we stick on the concepts.

Therefore, when we train a classifier to differentiate between cats and dogs, we task our program to give for an image, a label that us humans agreed on.
Therefore, the program is interpretable by nature. It is what we just tasked it to do:
"Please put these images in arbitrary categories that can be understood by humans and that make sense for humans".
It cannot get more interpretable than that.

Note that the made up concepts of "dogs" and "cats", could be replaced by any arbitrary words and sets of images, and the classifier would stay do its best to satisfy us (for example read [Understanding deep learning requires re-thinking generalization, C. Zhang et al](https://arxiv.org/pdf/1611.03530.pdf) )

### Pixel-wise video prediction is an awful metric to use to train an AGI

In his last year blog [Self-supervised learning: The dark matter of intelligence, Y. LeCun](https://ai.facebook.com/blog/self-supervised-learning-the-dark-matter-of-intelligence/) mentions video prediction as a useful self-supervised learning technique.

Prediction and sequential learning are two of the major learning components of the mammalian brain. And next-state prediction has showed to be a drive for synaptic plasticity in cortical microcolumns.

However, in the field of ML, this has been wrongfully understood as: 
It makes sense to train an algorithm to predict the next visual input because it is what the biological brain does.
However, that is not what the brain does. Humans and animals think in concepts. These concepts are formed by grouping representation that often pop up together.
When the human brain performs next state prediction they do not predict the exact sensory input at the next state. Instead, they predict the next representations that could arise in the near future.
The human brain is way closer to MuZero than to video prediction.

Therefore, we shouldn't blame a program for producing blurry video prediction as no human would ever be able to produce an accurate prediction of their next visual input.


