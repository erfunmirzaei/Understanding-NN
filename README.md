# Understanding-NN
Replicated “Understanding Individual Neuron Importance Using Information Theory” paper.


## Summary key points of the paper[1]

We characterize the outputs of individual neurons in a trained
feed-forward neural network by entropy, mutual information with the
class variable, and a class selectivity measure based on
Kullback-Leibler divergence.

● By cumulatively ablating neurons in the network, we connect these
information-theoretic measures to the impact their removal has on
classification performance on the test set.

● We observe that, looking at the neural network as a whole, none of
these measures is a good indicator for classification performance,
confirming recent results by Morcos et al.[2] Looking at specific
layers separately, both mutual information and class selectivity are
positively correlated with classification performance.

● We observe that, looking at the neural network as a whole, none of
these measures is a good indicator for classification performance,
thus confirming recent results by Morcos et al.

● However, looking at specific layers separately, both mutual
information and class selectivity are positively correlated with
classification performance.

● We then discuss pruning neurons from neural networks to reduce
computational complexity of inference.

● We conclude that it is ill-advised to compare these measures across
layers, and that different layers may be most appropriately
characterized by different measures.

● We discuss pruning neurons from neural networks to reduce
computational complexity of inference.

● Drawing from our results, we perform pruning based on
information-theoretic measures on a fully connected feed-forward
neural network with two hidden layers trained on MNIST dataset and
compare the results to a recently proposed pruning method.

● We show that the common practice of retraining after pruning can
partly be obviated by a surgery step called bias balancing, without
incurring significant performance degradation.

[1] Amjad, Rana Ali, Kairen Liu, and Bernhard C. Geiger. “Understanding
Neural Networks and Individual Neuron Importance via Information-Ordered
Cumulative Ablation.” IEEE Transactions on Neural Networks and Learning
Systems (2021): 1–11. Crossref. Web.

[2] Morcos, Ari S., et al. "On the importance of single directions for
generalization." arXiv preprint arXiv:1803.06959 (2018).
