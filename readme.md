我为什么要学习nlp？

ai的爆发在我大学的时候就已经开始了，当时我是存粹看不懂，后面准备面试的时候也没有时间，到现在已经差不多5年了，我现在有时间，并且平常生活都有听过，所以想了解一下。

平常也会对ai技术进行想象，比如想着游戏里能自己通过白话文来构建一个人格、武器，这种，但其实现在想想，ai都需要训练集训练，ai最终的目标就是模拟人格、复制人格，像gpt那样万能的模型可以从网络上得到训练集，但个人、或者虚拟人格都很难获得完整的训练集，所以只要在行为采集上没有突破，复制人格应该会很难。

不过，就算实现不了这一点，nlp还是很有魅力的，比如识别未知金融实体，能让模型通过网上的信息对公司、股票等进行分析，这在信息处理上很有帮助，能够代替以前使用策略的方式来进行数据分析的方法

为什么是nlp不是别的方向？

因为我觉得nlp是最有前途的，前面说过ai的最终目标是模拟人格，而无论是图像识别、让ai自动工作，都是要基于够智能，而训练人格就是需要文字描述，所以自然语言处理就是最前面的，虽然这个方向很大，可能对现在的我没有帮助，而且学习ai很有门槛，但好奇就总是会使人想要去做。

### 资源
#### 起源
- [西西嘛呦的博客园地址](https://home.cnblogs.com/u/xiximayou)
- [西西嘛呦的知乎地址](https://www.zhihu.com/people/gong-ou-bo)
- [西西嘛呦的GitHub地址](https://github.com/taishan1994)

#### 衍生
- [2019互联网金融新实体发现](https://www.datafountain.cn/competitions/361)
- [金融实体发现方案](https://zhuanlan.zhihu.com/p/100884995)
- [西西嘛呦关注博主1的nlp方向博文](https://www.cnblogs.com/pinard/category/894695.html?page=2)
- [西西嘛呦关注博主2的nlp方向博文](https://www.cnblogs.com/pinard/category/894695.html?page=1)
- [30天吃掉那只-tensorflow2 Github地址](https://github.com/lyhue1991/eat_tensorflow2_in_30_days#30%E5%A4%A9%E5%90%83%E6%8E%89%E9%82%A3%E5%8F%AA-tensorflow2)
- [nlp学习理论与项目GitHub地址](https://github.com/NLP-LOVE/ML-NLP/tree/master/NLP/16.%20NLP)

### 碎碎念
好像NLP这个领域，虽然理论也很重要，但主要还是要看场景是怎样来选择不同的做法，比如做信息提取，如果自己建模型跑出来的效果不如直接用chatGPT api的方法，那可能会选择不建模型了，而且训练模型还需要训练集、计算机资源等高门槛

太技术的东西就是这样，因为太技术，所以分为理论与技术，像我这样的草包入门，就是从实践入手再往深层技术去了解，但如果是搞科研的人应该是按照从理论-技术-实践的方向去了解，所以像我的这种方式不能生成新的东西，只能根据别人的成果去了解现有的东西.

### 目标
我看西西嘛呦很多都是看论文来获取知识的，但对我这种刚入门的来说好像这种方式太难了，还是先了解ai、nlp的一些大致概念与常见做法吧、

我的目的是最终能上手，所以掌握实践流程很重要，而不是专注于一个框架怎么用、底层原理是什么、有那么多方向选哪个好，我现在入门最重要的是先能从0到1，这样解决别的问题就能有思路了

还是要按照教程来先学习框架的语法吗？毕竟不这样我也没有数据集，想要实现目标也没有方法，可能跟着教程走还是学的最快的，准备数据、数据预处理都是工具，到了模型的时候才是决定高低的重点

- 《Python深度学习》与30天吃掉那只-tensorflow2结合起来读、实践

### 常用名词
#### NLP
NLP 是自然语言处理（Natural Language Processing）的缩写，是计算机科学和人工智能的一个分支，致力于研究如何使计算机理解、解释、生成和处理人类语言。NLP 涵盖了多种技术和方法，包括：

- 文本分析：如情感分析、主题建模
- 语言生成：如机器翻译、文本生成
- 语言理解：如问答系统、信息检索
- 语音识别和合成：如语音助手


#### LLM
大语言模型是指通过大量文本数据训练出来的能够理解和生成自然语言的大型深度学习模型。LLM 是 NLP 的一种具体实现，它在以下几个方面具有显著特点：

##### NLP与LLM的关系
NLP 是学科，LLM 是工具：NLP 是研究自然语言处理的学科，包含了广泛的理论和技术；LLM 则是其中一种强大的工具，用于实现具体的 NLP 任务。

#### PyTorch
PyTorch 是一个开源的深度学习框架，由 Facebook 的人工智能研究团队开发和维护。它于 2016 年首次发布，已经成为广泛使用的深度学习框架之一，尤其在研究界和工业界都得到了广泛的应用。PyTorch 拥有活跃的社区和丰富的第三方扩展库，如 torchvision（用于计算机视觉）、torchaudio（用于音频处理）和 torchtext（用于自然语言处理）。

#### dgl
DGL 是 Deep Graph Library 的缩写，是一个用于深度学习和图神经网络（Graph Neural Networks, GNNs）的开源库。DGL 由亚马逊和北京大学等多个研究机构联合开发，旨在提供高效、灵活的图计算框架，使研究人员和工程师能够方便地开发和应用图神经网络。

DGL 可以与 PyTorch、TensorFlow 等主流深度学习框架无缝集成，利用这些框架的丰富生态系统进行模型训练和优化。

通过图神经网络对社交网络中的节点和边进行建模和分析，可以用于推荐系统、用户行为预测等。

#### TensorFlow和PyTorch的区别
TensorFlow 和 PyTorch 是两大主流的深度学习框架，它们在功能上有很多相似之处，但在设计理念、使用方式和生态系统方面存在一些显著的区别。以下是它们之间的关系和主要区别：
计算图构建：

TensorFlow：采用静态计算图（Static Computation Graph），模型的计算图在训练之前构建，这使得模型的优化和部署更加高效。

PyTorch：采用动态计算图（Dynamic Computation Graph），计算图在运行时动态构建，提供了更灵活和直观的调试和开发体验。

#### BERT
BERT（Bidirectional Encoder Representations from Transformers）是一种基于 Transformer 模型的预训练语言表示方法，由Google在2018年提出。PyTorch是一个用于深度学习的开源机器学习库，由Facebook开发并维护。

PyTorch 实现：BERT的原始实现是基于TensorFlow的，但由于PyTorch在研究和开发社区中的广泛应用和受欢迎程度，很多人开始将BERT以及其他Transformer模型迁移到PyTorch上。因此，有很多PyTorch版本的BERT实现，这些实现通常能够更方便地与PyTorch生态系统中的其他库集成。


### 步骤与上手
基于chatGPT的零样本信息提取



