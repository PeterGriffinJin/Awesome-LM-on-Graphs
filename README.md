# Awesome-Language-Model-on-Graphs
A curated list of papers and resources about language model on graphs.

## Contents
- [Awesome-LM-on-Graphs](#awesome-lm-on-graphs)
  - [Contents](#contents)
  - [Datasets](#datasets)
  - [Representation Learning](#representation-learning)
  - [Pretraining](#pretraining)
  - [Classification](#classification)
  - [Contribution](#contribution)


## Datasets
### Text-attributed network
- Microsoft Academic network (MAG)
<br>Networks from 19 domains including CS, Mathematics, Geology, etc.
<br>Nodes: papers/authors/venues; Edges: citation/co-authorship/publish-in.
<br>Text: paper title, paper abstract on nodes.
<br>[[PDF](https://arxiv.org/abs/2302.03341)] [[Data](https://zenodo.org/record/7611544)] [[Preprocessing Code](https://github.com/PeterGriffinJin/Patton/blob/main/data_process/process_mag.ipynb)]
- Amazon Items
<br>Networks from 24 domains including Home, Clothing, Sports, etc.
<br>Nodes: items; Edges: co-purchase/co-viewed/same-brand.
<br>Text: item title and description on nodes.
<br>[[PDF](https://arxiv.org/pdf/1602.01585.pdf)] [[Data](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon/links.html)] [[Preprocessing Code](https://github.com/PeterGriffinJin/Patton/blob/main/data_process/process_amazon.ipynb)]



## Representation Learning
- [GraphFormers: GNN-nested Transformers for
Representation Learning on Textual Graph](https://arxiv.org/abs/2105.02605)
<br>Junhan Yang, Zheng Liu, Shitao Xiao, Chaozhuo Li, Defu Lian, Sanjay Agrawal, Amit Singh, Guangzhong Sun, Xing Xie.
<br>*NeurIPs 2021*.
<br>[[PDF](https://arxiv.org/abs/2105.02605)] [[Code](https://github.com/microsoft/GraphFormers)]

- [Heterformer: Transformer-based Deep Node Representation Learning on Heterogeneous Text-Rich Networks](https://arxiv.org/abs/2205.10282)
<br>Bowen Jin, Yu Zhang, Qi Zhu, Jiawei Han.
<br>*KDD 2023*.
<br>[[PDF](https://arxiv.org/abs/2205.10282)] [[Code](https://github.com/PeterGriffinJin/Heterformer)]

- [Edgeformers: Graph-Empowered Transformers for Representation Learning on Textual-Edge Networks](https://openreview.net/pdf?id=2YQrqe4RNv)
<br>Bowen Jin, Yu Zhang, Yu Meng, Jiawei Han.
<br>*ICLR 2023*.
<br>[[PDF](https://openreview.net/pdf?id=2YQrqe4RNv)] [[Code](https://github.com/PeterGriffinJin/Edgeformers)]


## Pretraining
- [LinkBERT: Pretraining Language Models with Document Links](https://arxiv.org/pdf/2203.15827.pdf)
<br>Michihiro Yasunaga, Jure Leskovec, Percy Liang.
<br>*ACL 2022*.
<br>[[PDF](https://arxiv.org/pdf/2203.15827.pdf)] [[Code](https://github.com/michiyasunaga/LinkBERT)]

- [Patton: Language Model Pretraining on Text-rich Networks](https://arxiv.org/abs/2305.12268)
<br>Bowen Jin, Wentao Zhang, Yu Zhang, Yu Meng, Xinyang Zhang, Qi Zhu, Jiawei Han.
<br>*ACL 2023*.
<br>[[PDF](https://arxiv.org/abs/2305.12268)] [[Code](https://github.com/PeterGriffinJin/Patton)]

- [DRAGON: Deep Bidirectional Language-Knowledge Graph Pretraining](https://cs.stanford.edu/~myasu/papers/dragon_neurips22.pdf)
<br>Michihiro Yasunaga, Antoine Bosselut, Hongyu Ren, Xikun Zhang, Christopher D. Manning, Percy Liang, Jure Leskovec.
<br>*NeurIPs 2022*.
<br>[[PDF](https://cs.stanford.edu/~myasu/papers/dragon_neurips22.pdf)] [[Code](https://github.com/michiyasunaga/dragon)]

## Classification
- [Metadata-Induced Contrastive Learning for Zero-Shot Multi-Label Text Classification](https://yuzhimanhua.github.io/papers/www22zhang.pdf)
<br>Yu Zhang, Zhihong Shen, Chieh-Han Wu, Boya Xie, Junheng Hao, Ye-Yi Wang, Kuansan Wang, Jiawei Han.
<br>**.
<br>[[PDF](https://yuzhimanhua.github.io/papers/www22zhang.pdf)] [[Code](https://github.com/yuzhimanhua/MICoL)]

- [Learning on Large-scale Text-attributed graphs via variational inference](https://openreview.net/pdf?id=q0nmYciuuZN)
<br>Jianan Zhao, Meng Qu, Chaozhuo Li, Hao Yan, Qian Liu, Rui Li, Xing Xie, Jian Tang.
<br>*ACL 2023*.
<br>[[PDF](https://openreview.net/pdf?id=q0nmYciuuZN)] [[Code](https://github.com/AndyJZhao/GLEM)]

## Question Answering
- [GreaseLM: Graph Reasoning Enhanced Language Models for Question Answering](https://cs.stanford.edu/~myasu/papers/greaselm_iclr22.pdf)
<br>Xikun Zhang, Antoine Bosselut, Michihiro Yasunaga, Hongyu Ren, Percy Liang, Christopher D Manning and Jure Leskovec.
<br>*ICLR 2022*.
<br>[[PDF](https://cs.stanford.edu/~myasu/papers/greaselm_iclr22.pdf)] [[Code](https://github.com/snap-stanford/GreaseLM)]


## Contribution
Contributions to this repository are welcome!

If you find any error or have relevant resources, feel free to open an issue or a pull request.


<!-- - []()
<br>
<br>**.
<br>[[PDF]()] [[Code]()] -->
