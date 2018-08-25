---
layout: default
---

## Introduction

This repository will contain deep learning projects, with their trained models and all the related files to it.
Toy projects of deep learning is not aim for this repository collection instead projects with some real implications will
be selected to work with.
Also, alternative approach to deep learning models their efficiency, ease of use and throughput for particular use-case will
be discussed. Currently, aim is to restrict ourself to limited four modules only and implement them in different manners,
study their efficiency with deep learning models. Hopefully, create newer models also as per need.

Current use cases under test involves:

|   Modules               |                 Use Cases                     |
|:------------------------|:----------------------------------------------|
| Chatbot                 | TroubleShooting, Personality, Recruiting      |
| VQA                     | Product, Brand Identification, Recommendation |
| Activity Classification | Audio and Visual Aid, Education               |
| Depth Analysis          | Realtime Audio and Visual Aid                 |

* * *

## Literature Survey

1. [10] VQA: Visual Question Answering the task of free-form and open-ended Visual Question
Answering (VQA) is by giving an image and a natural language question about the image, the task is
to provide an accurate natural language answer ​ Pros: In this paper proposed combining an LSTM for
the question with a CNN for the image to generate an answer a similar model is evaluated in this
paper. ​ Cons:​ Accuracy 54.06%

2. [1] Dynamic Memory Networks for Visual and Textual Question Answering We have
proposed new modules for the DMN framework to achieve strong results without supervision of
supporting facts. These improvements include the input fusion layer to allow interactions between
input facts and a novel attention based GRU that allows for logical reasoning over ordered inputs.
Pros:​ architecture, the dynamic memory network(DMN). ​ Cons: ​ Accuracy 60.4%
3. [9] Generative Adversarial Text to Image Synthesis In this work we are interested in
translating text in the form of single-sentence human-written descriptions directly into image pixels.
Pros: develop a novel deep architecture and GAN formulation to effectively bridge these advances in
text and image modelling, translating visual concepts from characters to pixels. ​ Cons: On Close
inspection it is clear that the generated scenes are not usually coherent;
4. [11] Estimated Depth Map Helps Image Classification Therefore, we present a way of
transferring domain knowledge on depth estimation to a separate image classification task over a
disjoint set of train, and test data. ​ Pros: 2-layer feed-forward neural network yielded a performance
increase of 4%, when comparing a NN trained on the RGB dataset to the NN trained on the RGBD
dataset. ​ Cons:​ We get 56% and 52% validation accuracy with RGBD and RGB dataset respectively.

* * *

## References

[1] Caiming Xiong, Stephen Merity, and Richard Socher. Dynamic memory networks for visual and
textual question answering. arXiv preprint arXiv:1603.01417, 2016.
[2] Donahue, J., Hendricks, L.A., Guadarrama, S., et al.: ‘Long-term recurrent convolutional
networks for visual recognition and description’. IEEE Conf. Computer Vision and Pattern
Recognition (CVPR), 2015
[3] GloVe: Global Vectors for Word Representation. ​ https://nlp.stanford.edu/projects/glove/​ .
[4] ​ https://github.com/machrisaa/tensorflow-vgg?files=1
[5] Karpathy, A., and Fei-Fei, L.: ‘Deep visual-semantic alignments for generating image
descriptions’. The IEEE Conf. Computer Vision and Pattern Recognition (CVPR), 2015
[6] K. Simonyan and A. Zisserman. Very deep convolutional networks for large-scale image
recognition. arXiv preprint arXiv:1409.1556, 2014.. Szegedy, W. Liu, Y.
[7] Mansimov, E., Parisotto, E., Ba, J. L., and Salakhutdinov, R. Generating images from captions
with attention. ICLR, 2016.
[8]M. Abadi, A. Agarwal, P. Barham, E. Brevdo, Z. Chen, C. Citro, G. S. Corrado, A. Davis, J. Dean,
M. Devin, S. Ghemawat, I. Goodfellow, A. Harp, G. Irving, M. Isard, Y. Jia, R. Jozefowicz, L.
Kaiser, M. Kudlur, J. Levenberg, D. Man ́e, R. Monga, S. Moore, D. Murray, C. Olah, M. Schuster, J.
Shlens, B. Steiner, I. Sutskever, K. Talwar, P. Tucker, V. Vanhoucke, V. Vasudevan, F. Vi ́egas, O.
Vinyals, P. Warden, M.Wattenberg, M.Wicke, Y. Yu, and X. Zheng. Tensor-Flow: Large-scale
machine learning on heterogeneous systems, 2015. Software available from tensorflow.org.
[9] Scott Reed, Zeynep Akata, Xinchen Yan, Lajanugen Logeswaran Bernt Schiele, Honglak Lee.
Generative Adversarial Text to Image Synthesis arXiv: 1605.05396v2 [cs.NE] 5 Jun 2016
[10] Stanislaw Antol, Aishwarya Agrawal, Jiasen Lu, Margaret Mitchell, Dhruv Batra, C. Lawrence
Zitnick, Devi Parikh, Virginia Tech Microsoft Research, VQA: Visual Question Answering IEEE
Explore, Year 2015
[11] Yihui He, Xi’an Jiaotong University, Xi’an, China Estimated Depth Map Helps Image
Classification, arXiv:1709.07077v1 [cs.CV] 20 Sep 2017

* * *
