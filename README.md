# NLP_Paper_Pool
<!-- TABLE OF CONTENTS -->
## Table of Contents
* [Datset](#dataset)
  * [Open Domain QA](#open-domain-qa)
  * [Multi-hop QA](#multi-hop-qa)
* [Machine Translation](#machine-translation)
* [Machine Translation (Non-Autoregressive)](#machine-translation-non-autoregressive)
* [Machine Translation (Low-Resource)](#machine-translation-low-resource)
* [Model Compression](#model-compression)
* [Attention](#attention)
* [Transformers](#transformers)
* [Training Tips for Transformers](#training-tips-for-transformers)
  * [Positional Encoding](#positional-encoding)
  * [Char Embedding](#char-embedding)
  * [Long Text](#long-text)
  * [Word Sense Disambiguation](#word-sense-disambiguation)
  * [Pretraining](#pretraining)
    * [Auxiliary Tasks](#auxiliary-tasks)
    * [Special Tokens Across Layers](#special-tokens-across-layers)
    * [Sub-modules](#sub-modules)
  * [Miscellaneous](#miscellaneous)
* [Explaination](#explaination)
* [Rich Answer Type](#rich-answer-type)
* [Optimizer](#optimizer)
* [Text Attribute Transfer](#text-attribute-transfer)
* [Layer Analysis](#layer-analysis)

<!-- Dataset -->
## Dataset
### Open Domain QA
- October 2020: [Open-Domain Question Answering Goes Conversational via Question Rewriting](https://arxiv.org/abs/2010.04898)
### Multi-hop QA
- November 2020: [Constructing A Multi-hop QA Dataset for Comprehensive Evaluation of Reasoning Steps](https://arxiv.org/abs/2011.01060)

<!-- Machine Translation -->
## Machine Translation
- December 2020: [Train Once, and Decode As You Like](https://www.aclweb.org/anthology/2020.coling-main.25.pdf)
- November 2020: [Language Models not just for Pre-training: Fast Online Neural Noisy Channel Modeling](https://arxiv.org/abs/2011.07164)
- October 2020: [Nearest Neighbor Machine Translation](https://arxiv.org/abs/2010.00710)
- October 2020: [Inference Strategies for Machine Translation with Conditional Masking](https://arxiv.org/abs/2010.02352)
- October 2020: [Multi-task Learning for Multilingual Neural Machine Translation](https://arxiv.org/abs/2010.02523)
- September 2020: [Energy-Based Reranking: Improving Neural Machine Translation Using Energy-Based Models](https://arxiv.org/abs/2009.13267)
- September 2020: [Softmax Tempering for Training Neural Machine Translation Models](https://arxiv.org/abs/2009.09372)
- September 2020: [CSP: Code-Switching Pre-training for Neural Machine Translation](https://arxiv.org/abs/2009.08088)
- June 2020: [Deep Encoder, Shallow Decoder: Reevaluating the Speed-Quality Tradeoff in Machine Translation](https://arxiv.org/abs/2006.10369)

<!-- Machine Translation (Non-Autoregressive)-->
## Machine Translation (Non-Autoregressive)
- November 2020: [Context-Aware Cross-Attention for Non-Autoregressive Translation](https://arxiv.org/abs/2011.00770)
- April 2020: [Non-Autoregressive Machine Translation with Latent Alignments](https://arxiv.org/abs/2004.07437)

<!-- Machine Translation (Low-Resource)-->
## Machine Translation (Low-Resource)
- October 2020: [Cross-lingual Machine Reading Comprehension with Language Branch Knowledge Distillation](https://arxiv.org/abs/2010.14271)
- October 2020: [Improving Target-side Lexical Transfer in Multilingual Neural Machine Translation](https://arxiv.org/abs/2010.01667)
- September 2020: [Harnessing Multilinguality in Unsupervised Machine Translation for Rare Languages](https://arxiv.org/abs/2009.11201)

<!-- Model Compression -->
## Model Compression
- October 2020: [Adversarial Self-Supervised Data-Free Distillation for Text Classification](https://arxiv.org/abs/2010.04883)
- October 2020: [Optimizing Transformers with Approximate Computing for Faster, Smaller and more Accurate NLP Models](https://arxiv.org/abs/2010.03688)
- September 2020: [Contrastive Distillation on Intermediate Representations for Language Model Compression](https://arxiv.org/abs/2009.14167v1)
- September 2020: [Weight Distillation: Transferring the Knowledge in Neural Network Parameters](https://arxiv.org/abs/2009.09152)
- June 2020: [SqueezeBERT: What can computer vision teach NLP about efficient neural networks?](https://arxiv.org/abs/2006.11316)
- February 2020: [BERT-of-Theseus: Compressing BERT by Progressive Module Replacing](https://arxiv.org/abs/2002.02925)
- February 2020: [Compressing Large-Scale Transformer-Based Models: A Case Study on BERT](https://arxiv.org/abs/2002.11985)

<!-- Attention -->
## Attention
- October 2020: [Long Document Ranking with Query-Directed Sparse Transformer](https://arxiv.org/abs/2010.12683)
- October 2020: [SMYRF: Efficient Attention using Asymmetric Clustering](https://arxiv.org/abs/2010.05315)
- October 2020: [Improving Attention Mechanism with Query-Value Interaction](https://arxiv.org/abs/2010.03766)
- October 2020: [Guiding Attention for Self-Supervised Learning with Transformers](https://arxiv.org/abs/2010.02399)
- September 2020: [An Attention Free Transformer](https://openreview.net/forum?id=pW--cu2FCHY)
- September 2020: [Sparsifying Transformer Models with Differentiable Representation Pooling](https://arxiv.org/abs/2009.05169)
- September 2020: [Repulsive Attention: Rethinking Multi-head Attention as Bayesian Inference](https://arxiv.org/abs/2009.09364)
- June 2020: [Limits to Depth Efficiencies of Self-Attention](https://arxiv.org/abs/2006.12467)
- May 2020: [Hard-Coded Gaussian Attention for Neural Machine Translation](https://arxiv.org/abs/2005.00742)
- November 2019: [Location Attention for Extrapolation to Longer Sequences](https://arxiv.org/abs/1911.03872)

<!-- Transforemrs -->
## Transformers
- 2020: Colorization Transformer
- October 2020: [N-ODE Transformer: A Depth-Adaptive Variant of the Transformer Using Neural Ordinary Differential Equations](https://arxiv.org/abs/2010.11358)
- August 2020: [DeLighT: Very Deep and Light-weight Transformer](https://arxiv.org/abs/2008.00623)
- April 2020: [Fast and Accurate Deep Bidirectional Language Representations for Unsupervised Learning](https://arxiv.org/abs/2004.08097)
- May 2019: [Unified Language Model Pre-training for Natural Language Understanding and Generation](https://arxiv.org/abs/1905.03197)

<!-- Traning Tips for Transformers -->
## Training Tips for Transformers
### Positional Encoding
- March 2020: [Learning to Encode Position for Transformer with Continuous Dynamical Model](https://arxiv.org/abs/2003.09229)
### Char Embedding
-November 2020: [CharBERT: Character-aware Pre-trained Language Model](https://arxiv.org/abs/2011.01513)
### Long Text
- October 2020: [Long Document Ranking with Query-Directed Sparse Transformer](https://arxiv.org/abs/2010.12683)
- June 2020: [Progressive Generation of Long Text](https://arxiv.org/abs/2006.15720)
### Word Sense Disambiguation
- November 2020: [Detecting Word Sense Disambiguation Biases in Machine Translation for Model-Agnostic Adversarial Attacks](https://arxiv.org/abs/2011.01846)
### Pretraining
#### Auxiliary Tasks
- October 2020: [On Losses for Modern Language Models](https://arxiv.org/abs/2010.01694)
#### Special Tokens Across Layers
- October 2020: [Cross-Thought for Sentence Encoder Pre-training](https://arxiv.org/abs/2010.03652)
#### Sub-modules
- October 2020: [VECO: Variable Encoder-decoder Pre-training for Cross-lingual Understanding and Generation](https://arxiv.org/abs/2010.16046)
### Miscellaneous
- July 2020: [Data Movement Is All You Need: A Case Study on Optimizing Transformers](https://arxiv.org/abs/2007.00072)

<!-- Explaination -->
## Explaination
- October 2020: [Explaining and Improving Model Behavior with k Nearest Neighbor Representations](https://arxiv.org/abs/2010.09030)
- April 2020: [Attention Module is Not Only a Weight: Analyzing Transformers with Vector Norms](https://arxiv.org/abs/2004.10102)
- September 2019: [Learning to Deceive with Attention-Based Explanations](https://arxiv.org/abs/1909.07913)

<!-- Rich Answer Type -->
## Rich Answer Type
- September 2020:[No Answer is Better Than Wrong Answer: A Reflection Model for Document Level Machine Reading Comprehension](https://arxiv.org/abs/2009.12056)

<!-- Optimizer -->
## Optimizer
- September 2020:[Apollo: An Adaptive Parameter-wise Diagonal Quasi-Newton Method for Nonconvex Stochastic Optimization](https://arxiv.org/abs/2009.13586)

<!-- Text Attribute Transfer -->
## Text Attribute Transfer
- November 2020:[Deep Learning for Text Attribute Transfer: A Survey](https://arxiv.org/abs/2011.00416)

<!-- Layer Analysis-->
## Layer Analysis
- October 2020 :[Do Wide and Deep Networks Learn the Same Things? Uncovering How Neural Network Representations Vary with Width and Depth](https://arxiv.org/abs/2010.15327)

## Need to update
1. An Attention Free Transformer
