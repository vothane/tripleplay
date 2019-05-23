# tripleplay
A tool for comparing MLB pitchers using deep learning. Motivation is from baseballsavant.mlb.com where they do comparisons of hitters (not very good IMO) but not pitchers.

![](OhYu.gif)

Workflow is very much like laser_show but instead will use convnets to process images. I didn't use convnets in laser_show because how the hit markers were large and overlapped 
one another thus leading to information loss in the convolutions. Latter I will demostrate how to use tractable unsupervised
learning ML algorithms, t-SNE in this case, to ascertain what the hidden layers maybe learning (discernible latent features in data). 
Then possibly using ensemble algos as well. 