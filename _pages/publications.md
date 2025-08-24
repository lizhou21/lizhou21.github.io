---
layout: archive
title: "📖 Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sub>
\# denotes co‑first authors;    
\* denotes corresponding author;   
<ins>underlined names</ins> indicate students co‑supervised with Prof. Haizhou Li at CUHK-Shenzhen.
</sub>

# 2025
**Hanfu-Bench: A Multimodal Benchmark on Cross-Temporal Cultural Understanding and Transcreation**   
**Li Zhou**\#\*, <ins>Lutong Yu</ins>\# (master), <ins>Dongchu Xie</ins>(undergraduate), Shaohuan Cheng, Wenyan Li, Haizhou Li   
EMNLP 2025 main. [[Arxiv]](https://arxiv.org/abs/2506.01565)

**From Word to World: Evaluate and Mitigate Culture Bias via Word Association Test**   
<ins>Xunlian Dai</ins> (visiting undergraduate), **Li Zhou**\*, Benyou Wang, Haizhou Li   
EMNLP 2025 main. [[Arxiv]](https://arxiv.org/abs/2505.18562)

**RAG-Instruct: Boosting LLMs with diverse retrieval-augmented instructions**   
Wanlong Liu\#, Junying Chen\#, Ke Ji, **Li Zhou**, Wenyu Chen, Benyou Wang   
EMNLP 2025 main. [[Arxiv]](https://arxiv.org/abs/2501.00353)


# 2024
**Beyond Binary: Towards Fine-Grained LLM-Generated Text Detection via Role Recognition and Involvement Measurement**   
Zihao Cheng\#, **Li Zhou**\#\*, Feng Jiang, Benyou Wang, Haizhou Li   
Arxiv 2024. [[Arxiv]](https://arxiv.org/abs/2410.14259)

**Does Mapo Tofu Contain Coffee? Probing LLMs for Food-related Cultural Knowledge**   
**Li Zhou**, Taelin Karidi, Nicolas Garneau, Yong Cao, Wanlong Liu, Wenyu Chen, Haizhou Li, Daniel Hershcovich   
Arxiv 2024. [[Arxiv]](https://arxiv.org/pdf/2404.06833.pdf)

**A Compressive Memory-based Retrieval Approach for Event Argument Extractiont**   
Wanlong Liu, Enqi Zhang, Shaohuan Cheng, **Li Zhou**, Dingyi Zeng, Chen Zhang, Malu Zhang, Wenyu Chen   
COLING 2025. [[Arxiv]](https://arxiv.org/abs/2409.09322)

**Dynamic Training for Handling Textual Label Noise**   
Shaohuan Cheng, Wenyu Chen, Wanlong Liu, **Li Zhou**, Honglin Zhao, Weishan Kong, Hong Qu, Mingsheng Fu   
Applied Intelligence 2024. [[Journal]](https://link.springer.com/article/10.1007/s10489-024-05738-x)

**FoodieQA: A Multimodal Dataset for Fine-Grained Understanding of Chinese Food Culture**   
Wenyan Li, Xinyu Zhang, Jiaang Li, Qiwei Peng, Raphael Tang, **Li Zhou**, Weijia Zhang, Guimin Hu, Yifei Yuan, Anders Søgaard, Daniel Hershcovich, Desmond Elliott   
EMNLP 2024. [[Arxiv]](https://arxiv.org/abs/2405.01884)


**Beyond Single-Event Extraction: Towards Efficient Document-Level Multi-Event Argument Extraction**   
Wanlong Liu, **Li Zhou**, Dingyi Zeng, Yichen Xiao, Shaohuan Cheng, Chen Zhang, Grandee Lee, Malu Zhang, Wenyu Chen   
Findings of ACL 2024. [[Arxiv]](https://arxiv.org/abs/2405.01884)

**CreoleVal: Multilingual Multitask Benchmarks for Creoles**   
Heather Lent, Kushal Tatariya, Raj Dabre, Yiyi Chen, Marcell Fekete, Esther Ploeger, **Li Zhou**, Hans Erik Heje, Diptesh Kanojia, Paul Belony, Marcel Bollmann, Loïc Grobol, Miryam de Lhoneux, Daniel Hershcovich, Michel DeGraff, Anders Søgaard, Johannes Bjerva   
Transactions of the Association for Computational Linguistics (TACL). [[Arxiv]](https://arxiv.org/abs/2310.19567)


**MLPs Compass: What is learned when MLPs are combined with PLMs?**   
**Li Zhou**, Wenyu Chen, Yong Cao, Dingyi Zeng, Wanlong Liu, Hong Qu.  
ICASSP 2024. [[Arxiv]](https://arxiv.org/abs/2401.01667) [[Proceedings]](https://ieeexplore.ieee.org/document/10447714)


**Cultural Adaptation of Recipes**   
Yong Cao\*, Yova Kementchedjhieva\*, Ruixiang Cui, Antonia Karamolegkou, **Li Zhou**, Megan Dare, Lucia Donatelli, Daniel Hershcovich   
Transactions of the Association for Computational Linguistics (TACL).[[Arxiv]](https://arxiv.org/abs/2310.17353)


# 2023
**Rethinking Relation Classification with Graph Meaning Representations**   
**Li Zhou**, Wenyu Chen, Dingyi Zeng, Malu Zhang, Daniel Hershcovich   
Arxiv 2023. [[Arxiv]](https://arxiv.org/abs/2310.09772)

**Cultural Compass: Predicting Transfer Learning Success in Offensive Language Detection with Cultural Features**   
**Li Zhou**,  Antonia Karamolegkou, Wenyu Chen, Daniel Hershcovich   
Findings of EMNLP 2023. [[Arxiv]](https://arxiv.org/abs/2310.06458) [[Proceedings]](https://aclanthology.org/2023.findings-emnlp.845/)

**Copyright Violations and Large Language Models**   
Antonia Karamolegkou\*, Jiaang Li\*, **Li Zhou**, Anders Søgaard   
EMNLP 2023. [[Arxiv]](https://arxiv.org/abs/2310.13771) [[Proceedings]](https://aclanthology.org/2023.emnlp-main.458/)

**Cross-Cultural Transfer Learning for Chinese Offensive Language Detection**   
**Li Zhou**, Laura Cabello, Yong Cao, Daniel Hershcovich   
Cross-Cultural Considerations in NLP Workshop at EACL 2023 [[Proceedings]](https://aclanthology.org/2023.c3nlp-1.2/) [[Arxiv]](https://arxiv.org/abs/2303.17927)

**Assessing Cross-Cultural Alignment between ChatGPT and Human Societies: An Empirical Study**   
Yong Cao, **Li Zhou**, Seolhwa Lee, Laura Cabello Piqueras, Min Chen, Daniel Hershcovich   
Cross-Cultural Considerations in NLP Workshop at EACL 2023 [[Proceedings]](https://aclanthology.org/2023.c3nlp-1.7/) [[Arxiv]](https://arxiv.org/abs/2303.17466)

**DPGNN: Dual-perception graph neural network for representation learning**   
**Li Zhou**, Wenyu Chen, Dingyi Zeng, Shaohuan Cheng, Wanlong Liu, Malu Zhang, Hong Qu   
Knowledge-Based Systems [[Journal]](https://www.sciencedirect.com/science/article/pii/S0950705123001272) [[PDF]](https://lizhou21.github.io/files/DPGNN.pdf)

**Rethinking Random Walk in Graph Representation Learning**   
Dingyi Zeng, Wenyu Chen, Wanlong Liu, **Li Zhou**, Hong Qu   
ICASSP 2023 [[Proceedings]](https://ieeexplore.ieee.org/abstract/document/10096316/)

**Substructure aware graph neural networks**   
Dingyi Zeng\*, Wanlong Liu\*, Wenyu Chen, **Li Zhou**, Malu Zhang, Hong Qu   
AAAI 2023 [[Proceedings]](https://ojs.aaai.org/index.php/AAAI/article/view/26318)

# 2022

**A simple graph neural network via layer sniffer**   
Dingyi Zeng\*, *<ins>Li Zhou\*</ins>*, Wanlong Liu, Hong Qu, Wenyu Chen   
ICASSP 2022 [[Proceedings]](https://ieeexplore.ieee.org/abstract/document/9746357)

**Document-Level Relation Extraction with Structure Enhanced Transformer Encoder**   
Wanlong Liu, **Li Zhou**, Dingyi Zeng, Hong Qu   
IJCNN 2022 [[Proceedings]](https://ieeexplore.ieee.org/abstract/document/9892647)

# 2020

**A weighted GCN with logical adjacency matrix for relation extraction**   
*<ins>Li Zhou\*</ins>*, Tingyu Wang*, Hong Qu, Li Huang, Yuguo Liu   
ECAI 2020 [[Proceedings]](https://ebooks.iospress.nl/doi/10.3233/FAIA200360)


