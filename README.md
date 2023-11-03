# DICTH-main

Using the code should cite the following paper:


[1] Zijian Chao, Shuli Cheng*, Yongming Li.Deep Internally Connected Transformer Hashing for Image Retrieval.Knowledge-based systems，2023, 279, 110953.  （IF=8.8）.


[2] Zhiwei Zhang, Shuli Cheng, Liejun Wang*, Combined query image retrieval based on hybrid coding of CNN and Mix-Transformer.Expert Systems With Applications. 2023,234，121060. (IF=8.5).

########################################################################################################################################################################################################
Description:

Transformer based on self-attention mechanism has made remarkable achievements in natural language processing, which inspired the application research of Transformer in computer vision. The current deep hashing algorithms extract image features through the convolutional neural network (CNN). CNN concentrates on local information, and features lack global dependency information, which has an impact on image retrieval accuracy. To remedy the above defects, this paper proposes deep internally connected Transformer hashing for image retrieval (DICTH). DICTH has designed an improved Transformer block: internally connected Transformer block (ICT). ICT performs an embedded transformation on the feature maps, splices the generated Keys and Queries, to explore the rich context information between Query–Key pairs, and then dynamically encodes through multi-layer convolution to learn the context multi-head self-attention matrix. By combining ICT and ResNet18 to achieve self-attention injection, a long-distance dependency is established in the feature space to make up for the shortcomings of pure CNN in the feature extraction process and guide the algorithm to learn more accurate hash codes. At the same time, in the face of complex label information in big data sets, this paper uses an improved cross-entropy loss function: T-cross-entropy loss, to promote network learning of hash codes with more ability to distinguish between classes. In this paper, a lot of experiments have been conducted on CIFAR10, NUS-WIDE and MS-COCO datasets to verify the performance of DICTH.


