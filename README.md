## Model

This model is a CNN based only on the character level as charCNN [1]. It exploit the benefit of deep structure for text understanding task as [3]. The first work of transfer a shallow CNN & distant supervision can be read at [5]. The aim of this model is to transfer a very deep (rather than a shallow) network and base only on character level without any feature-engineering at the word level [5]. This kind of transfer is depicted in [6]:

<p align="center">
  <img src="http://yosinski.com/static/proj/convnet_transfer_lines_crop.png" width="400"/>
</p>

The evaluation is on small data set of Semval-2013 (2.3k/0.9k pos/neg tweets). The input is a big Twitter's emoticon data set (1.6 M balanced pos/neg tweets) [4].

## Reference Articles

- [1] Xiang Zhang, Junbo Zhao, Yann LeCun. Character-level Convolutional Networks for Text Classification. Advances in Neural Information Processing Systems 28 (NIPS 2015)
- [2] Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. Deep Residual Learning for Image Recognition. IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016
- [3] Alexis Conneau, Holger Schwenk, Loïc Barrault, Yann LeCun. Very Deep Convolutional Networks for Natural Language Processing. CoRR 2016
- [4] Alec Go. Richa Bhayani. Lei Huang. Twitter Sentiment Classification using Distant Supervision. Stanford
- [5] Duyu Tang, Furu Wei, Bing Qin, Ting Liu, Ming Zhou. Coooolll: A Deep Learning System for Twitter Sentiment Classification. Proceedings of the 8th International Workshop on Semantic Evaluation (SemEval 2014)
- [6] Jason Yosinski, Jeff Clune, Yoshua Bengio, and Hod Lipson. How transferable are features in deep neural networks? NIPS 2014

## Reference Source Codes

- https://github.com/dennybritz/cnn-text-classification-tf
