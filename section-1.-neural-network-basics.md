# Section 1. Neural Network Basics

## Neural Network

### Table of Contents

### Beginners Guide

If you are a total beginner to this, start here!

1. Visit hackmd.io
2. Click "Sign in"
3. Choose a way to sign in
4. Start writing note!

### 1. Introduction to Neural Networks

在看本文之前你可能已经对Neural Network有了一定的了解。Neural Network可以抽象的表示为下图：【图1】 Neural Network的最基本组成单位是Neuron，在图中用一个圆圈表示。该图所表示的是一个有两个Hidden Layer的Neural Network。该Neural Network的层数为5层。接下来我们定义一下变量： 

$$
w_{jk}^l \text{表示第}(l-1)\text{层的第}k\text{个neuron连接到第}l\text{层的第}j\text{个neuron的权重；} \\
b_j^l \text{表示第}l\text{层的第}j\text{个neuron的bias；} \\
z_j^l \text{表示第}l\text{层的第}j\text{个neuron的输入，即：}z_l^j=\sum_k {w_{jk}^l a^{l-1}_k+b^l_j} \\
a_j^l \text{表示第}l\text{层的第}j\text{个neuron的输出，即：}a^j_l=\sigma(\sum_k {w_{jk}^l a^{l-1}_k+b_j^l)} \\
$$



