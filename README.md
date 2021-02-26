# BSC_Public_Github_Repository
 Github repo for everything public

 Transfer-learning seemed to be the obvious solution to this, my first, Kaggle competition. Pretty soon into the competition I stumbled over a notebook by Sachin Prabhu using the SnapMix algorithm described in https://arxiv.org/abs/2012.04846 , "SnapMix: Semantically Proportional Mixing for Augmenting Fine-grained Data". There is also a code repo on github:  https://github.com/Shaoli-Huang/SnapMix . 
 The code is written in PyTorch, I don't know PyTorch but found it interessting to try implementing the very same algorithm using tf.keras - knowing about Keras from the book by F. Chollet.
 My implementation is not doing too well though: LB/PB about 44% while the notebook by S.P. reaches > 80% accuracy
 Clearly SnapMix requires more than knowing "model.fit" - so it was a steep learning curve for me - and trying to read the PyTorch-code, the tf.keras and the TensorFlow documentations and tutorials I came to the conclusion, that tf.keras is more implicit (of course, that's the whole purpose of Keras) than PyTorch and that knowing/ using PyTorch improves understanding of the mechanism behind the frameworks: e.g. I always wondered how the derivatives for backprob are calculated by Keras - never heard about autodiff before. 

 ...so the next project is learning Pytorch and then comming back to SnapMix and give it a new try, be it using TensorFlow, tf.keras or Pytorch.

The ResNet implementation used can be found here: https://www.kaggle.com/xhlulu/tf-keras-resnet?select=resnet50_notop.h5
 
