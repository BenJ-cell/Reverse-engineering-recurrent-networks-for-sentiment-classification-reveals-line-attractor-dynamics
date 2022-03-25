# Reverse-engineering-recurrent-networks-for-sentiment-classification-reveals-line-attractor-dynamics
RNNs have been utilized in various applications such as speech recognition, sentiment
analysis, music, and video. In neuroscience, RNNs have been used for modeling large-scale
neural recordings and as a generator of scientific hypotheses by studying the network’s
learned representations. However, RNNs are generally viewed as black boxes. While there
has been progress in understanding their operation on simple tasks, rigorously understanding
how they solve complex tasks remains a significant challenge. In the industry the results of our
algorithms lead to decision-making and having the power to linearize our problem help us
explain with words and arguments why a decision is made and help us understand further
how the network learns its decisions. In the end, these experiments helped us demonstrate that amazingly we can find a
human and interpretable way of computing in some tasks solved across a wide range
of RNNs. We have also shown that RNN architectures converge to a low-dimensional
representation for the task of sentiment classification, even though they are able to
implement high dimensional and nonlinear computations. So we may now
quantitatively understand how a RNN solves the sentiment analysis task by
interpreting its linear approximation. By understanding the linear dynamics in a
general RNN solving certain tasks, we can gain back the explainability lost by those
black boxes while keeping its accuracy!

LINK OF SEVERAL RELATED IMPLEMENTATIONS : https://github.com/google-research/computation-thru-dynamics working on 
Latent Factor Analysis via Dynamical Systems, Fixed point finding training a GRU to make a binary decision and study 
it via fixed point finding.
The fixed point finder GRU decision-making GRU yields:
1. the underlying fixed points
2. the first order taylor series approximations around those fixed points.
