# Must-read papers on GNN
GNN: graph neural network

Contributed by Jie Zhou, Ganqu Cui, Zhengyan Zhang and Yushi Bai.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Models</a></td></tr>
<tr>
    <td>&emsp;<a href="#basic-models">2.1 Basic Models</a></td>
    <td>&ensp;<a href="#graph-types">2.2 Graph Types</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#pooling-methods">2.3 Pooling Methods</a></td>
    <td>&ensp;<a href="#analysis">2.4 Analysis</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#efficiency">2.5 Efficiency</a></td>
    <td></td>
</tr>
<tr><td colspan="2"><a href="#applications">3. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="#physics">3.1 Physics</a></td>
    <td>&ensp;<a href="#chemistry-and-biology">3.2 Chemistry and Biology</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#knowledge-graph">3.3 Knowledge Graph</a></td>
    <td>&ensp;<a href="#recommender-systems">3.4 Recommender Systems</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#computer-vision">3.5 Computer Vision</a></td>
    <td>&ensp;<a href="#natural-language-processing">3.6 Natural Language Processing</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#generation">3.7 Generation</a></td>
    <td>&ensp;<a href="#combinatorial-optimization">3.8 Combinatorial Optimization</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#adversarial-attack">3.9 Adversarial Attack</a></td>
    <td>&ensp;<a href="#graph-clustering">3.10 Graph Clustering</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#graph-classification">3.11 Graph Classification</a></td>
    <td>&ensp;<a href="#reinforcement-learning">3.12 Reinforcement Learning</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#traffic-network">3.13 Traffic Network</a></td>
    <td>&ensp;<a href="#few-shot-and-zero-shot-learning">3.14 Few-shot and Zero-shot Learning</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#program-representation">3.15 Program Representation</a></td>
    <td>&ensp;<a href="#social-network">3.16 Social Network</a></td>
</tr> 
</table>

## [Survey papers](#content)
1. **Graph Neural Networks: A Review of Methods and Applications.** arxiv 2018. [paper](https://arxiv.org/pdf/1812.08434.pdf)
    
    *Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun.* 

1. **A Comprehensive Survey on Graph Neural Networks.** arxiv 2019. [paper](https://arxiv.org/pdf/1901.00596.pdf)

    *Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu.*

1. **Deep Learning on Graphs: A Survey.** arxiv 2018. [paper](https://arxiv.org/pdf/1812.04202.pdf)

    *Ziwei Zhang, Peng Cui, Wenwu Zhu.*

1. **Relational Inductive Biases, Deep Learning, and Graph Networks.** arxiv 2018. [paper](https://arxiv.org/pdf/1806.01261.pdf)

    *Battaglia, Peter W and Hamrick, Jessica B and Bapst, Victor and Sanchez-Gonzalez, Alvaro and Zambaldi, Vinicius and Malinowski, Mateusz and Tacchetti, Andrea and Raposo, David and Santoro, Adam and Faulkner, Ryan and others.*

1. **Geometric Deep Learning: Going beyond Euclidean data.** IEEE SPM 2017. [paper](https://arxiv.org/pdf/1611.08097.pdf)

    *Bronstein, Michael M and Bruna, Joan and LeCun, Yann and Szlam, Arthur and Vandergheynst, Pierre.*

1. **Computational Capabilities of Graph Neural Networks.** IEEE TNN 2009. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4703190)

    *Scarselli, Franco and Gori, Marco and Tsoi, Ah Chung and Hagenbuchner, Markus and Monfardini, Gabriele.*

1. **Neural Message Passing for Quantum Chemistry.** ICML 2017. [paper](https://arxiv.org/pdf/1704.01212.pdf)

    *Gilmer, Justin and Schoenholz, Samuel S and Riley, Patrick F and Vinyals, Oriol and Dahl, George E.*

1. **Non-local Neural Networks.** CVPR 2018. [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Non-Local_Neural_Networks_CVPR_2018_paper.pdf)

    *Wang, Xiaolong and Girshick, Ross and Gupta, Abhinav and He, Kaiming.*

1. **The Graph Neural Network Model.** IEEE TNN 2009. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4700287)

    *Scarselli, Franco and Gori, Marco and Tsoi, Ah Chung and Hagenbuchner, Markus and Monfardini, Gabriele.*


## [Models](#content)   
    
### [Basic Models](#content)
1. **Graphical-Based Learning Environments for Pattern Recognition.** SSPR/SPR 2004. [paper](https://link.springer.com/content/pdf/10.1007%2F978-3-540-27868-9_4.pdf)

    *Franco Scarselli, Ah Chung Tsoi, Marco Gori, Markus Hagenbuchner.*

1. **A new model for learning in graph domains.** IJCNN 2005. [paper](https://www.researchgate.net/profile/Franco_Scarselli/publication/4202380_A_new_model_for_earning_in_raph_domains/links/0c9605188cd580504f000000.pdf)

    *Marco Gori, Gabriele Monfardini, Franco Scarselli.*

1. **Graph Neural Networks for Ranking Web Pages.** WI 2005. [paper](https://www.researchgate.net/profile/Franco_Scarselli/publication/221158677_Graph_Neural_Networks_for_Ranking_Web_Pages/links/0c9605188cd5090ede000000/Graph-Neural-Networks-for-Ranking-Web-Pages.pdf)

    *Franco Scarselli, Sweah Liang Yong, Marco Gori, Markus Hagenbuchner, Ah Chung Tsoi, Marco Maggini.*
    
1. **Spectral Networks and Locally Connected Networks on Graphs.** ICLR 2014. [paper](https://arxiv.org/pdf/1312.6203.pdf)

    *Joan Bruna, Wojciech Zaremba, Arthur Szlam, Yann LeCun.*
    
1. **Deep Convolutional Networks on Graph-Structured Data.** arxiv 2015. [paper](https://arxiv.org/pdf/1506.05163.pdf)

    *Mikael Henaff, Joan Bruna, Yann LeCun.*
    
1. **Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering.** NIPS 2016. [paper](http://papers.nips.cc/paper/6081-convolutional-neural-networks-on-graphs-with-fast-localized-spectral-filtering.pdf)

    *Michaël Defferrard, Xavier Bresson, Pierre Vandergheynst.*

1. **Diffusion-Convolutional Neural Networks.** NIPS 2016. [paper](https://arxiv.org/pdf/1511.02136.pdf)

    *James Atwood, Don Towsley.*
    
1. **Gated Graph Sequence Neural Networks.** ICLR 2016. [paper](https://arxiv.org/pdf/1511.05493.pdf)

    *Yujia Li, Daniel Tarlow, Marc Brockschmidt, Richard Zemel.*
    
1. **Learning Convolutional Neural Networks for Graphs.** ICML 2016. [paper](http://proceedings.mlr.press/v48/niepert16.pdf)

    *Mathias Niepert, Mohamed Ahmed, Konstantin Kutzkov.* 
    
1. **Semantic Object Parsing with Graph LSTM.** ECCV 2016. [paper](https://link.springer.com/content/pdf/10.1007%2F978-3-319-46448-0_8.pdf)

    *Xiaodan Liang, Xiaohui Shen, Jiashi Feng, Liang Lin, Shuicheng Yan.*
    
1. **Semi-Supervised Classification with Graph Convolutional Networks.** ICLR 2017. [paper](https://arxiv.org/pdf/1609.02907.pdf)

    *Thomas N. Kipf, Max Welling.*
    
1. **Inductive Representation Learning on Large Graphs.** NIPS 2017. [paper](https://arxiv.org/pdf/1706.02216.pdf)

    *William L. Hamilton, Rex Ying, Jure Leskovec.*
    
1. **Geometric deep learning on graphs and manifolds using mixture model cnns.** CVPR 2017. [paper](https://arxiv.org/pdf/1611.08402.pdf)

    *Federico Monti, Davide Boscaini, Jonathan Masci, Emanuele Rodolà, Jan Svoboda, Michael M. Bronstein.*
    
1. **Graph Attention Networks.** ICLR 2018. [paper](https://mila.quebec/wp-content/uploads/2018/07/d1ac95b60310f43bb5a0b8024522fbe08fb2a482.pdf)

    *Petar Velickovic, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Lio, Yoshua Bengio.*

1. **Covariant Compositional Networks For Learning Graphs.** ICLR 2018. [paper](https://arxiv.org/pdf/1801.02144.pdf)

    *Risi Kondor, Hy Truong Son, Horace Pan, Brandon Anderson, Shubhendu Trivedi.*

1. **Graph Partition Neural Networks for Semi-Supervised Classification.** ICLR 2018. [paper](https://arxiv.org/pdf/1803.06272.pdf)

    *Renjie Liao, Marc Brockschmidt, Daniel Tarlow, Alexander L. Gaunt, Raquel Urtasun, Richard Zemel.*
    
1. **Inference in Probabilistic Graphical Models by Graph Neural Networks.** ICLR Workshop 2018. [paper](https://arxiv.org/pdf/1803.07710.pdf)

    *KiJung Yoon, Renjie Liao, Yuwen Xiong, Lisa Zhang, Ethan Fetaya, Raquel Urtasun, Richard Zemel, Xaq Pitkow.*

1. **Structure-Aware Convolutional Neural Networks.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7287-structure-aware-convolutional-neural-networks.pdf)

    *Jianlong Chang, Jie Gu, Lingfeng Wang, Gaofeng Meng, Shiming Xiang, Chunhong Pan.*
    
1. **Bayesian Semi-supervised Learning with Graph Gaussian Processes.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1809.04379)

    *Yin Cheng Ng, Nicolò Colombo, Ricardo Silva.*
    
1. **Adaptive Graph Convolutional Neural Networks.** AAAI 2018. [paper](https://arxiv.org/pdf/1801.03226.pdf)

    *Ruoyu Li, Sheng Wang, Feiyun Zhu, Junzhou Huang.*    
<details><summary> more </summary> 

21. **Dual Graph Convolutional Networks for Graph-Based Semi-Supervised Classification.** WWW 2018. [paper](http://delivery.acm.org/10.1145/3190000/3186116/p499-zhuang.pdf?ip=123.134.247.159&id=3186116&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1564108433_6b20d1fe2ab710632bc8434ad3a00bc8)

    *Chenyi Zhuang, Qiang Ma.*

22. **Learning Steady-States of Iterative Algorithms over Graphs.** ICML 2018. [paper](http://proceedings.mlr.press/v80/dai18a/dai18a.pdf)

    *Hanjun Dai, Zornitsa Kozareva, Bo Dai, Alex Smola, Le Song.*

1. **Graph Capsule Convolutional Neural Networks.** ICML 2018 Workshop. [paper](https://arxiv.org/pdf/1805.08090.pdf)

    *Saurabh Verma, Zhi-Li Zhang.*
    
1. **Capsule Graph Neural Network.** ICLR 2019. [paper](https://openreview.net/pdf?id=Byl8BnRcYm)

    *Zhang Xinyi, Lihui Chen.*
    
1. **Graph Wavelet Neural Network.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1ewdiR5tQ)

    *Bingbing Xu, Huawei Shen, Qi Cao, Yunqi Qiu, Xueqi Cheng.*

1. **Deep Graph Infomax.** ICLR 2019. [paper](https://openreview.net/pdf?id=rklz9iAcKQ)

    *Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm.*
    
1. **Predict then Propagate: Graph Neural Networks meet Personalized PageRank.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1gL-2A9Ym)

    *Johannes Klicpera, Aleksandar Bojchevski, Stephan Günnemann.*

1. **LanczosNet: Multi-Scale Deep Graph Convolutional Networks.** ICLR 2019. [paper](https://openreview.net/pdf?id=BkedznAqKQ)

    *Renjie Liao, Zhizhen Zhao, Raquel Urtasun, Richard Zemel.*

1. **Invariant and Equivariant Graph Networks.** ICLR 2019. [paper](https://openreview.net/pdf?id=Syx72jC9tm)

    *Haggai Maron, Heli Ben-Hamu, Nadav Shamir, Yaron Lipman.*

1. **GMNN: Graph Markov Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1905.06214)

    *Meng Qu, Yoshua Bengio, Jian Tang.*
    
1. **Position-aware Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1906.04817)

    *Jiaxuan You, Rex Ying, Jure Leskovec.*

1. **Disentangled Graph Convolutional Networks.** ICML 2019. [paper](http://proceedings.mlr.press/v97/ma19a/ma19a.pdf)

    *Jianxin Ma, Peng Cui, Kun Kuang, Xin Wang, Wenwu Zhu.*
    
1. **Stochastic Blockmodels meet Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1905.05738)

    *Nikhil Mehta, Lawrence Carin, Piyush Rai.*

1. **Learning Discrete Structures for Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1903.11960)

    *Luca Franceschi, Mathias Niepert, Massimiliano Pontil, Xiao He.*

1. **MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing.** ICML 2019. [paper](https://arxiv.org/pdf/1905.00067)

    *Sami Abu-El-Haija, Bryan Perozzi, Amol Kapoor, Nazanin Alipourfard, Kristina Lerman, Hrayr Harutyunyan, Greg Ver Steeg, Aram Galstyan.*

1. **DEMO-Net: Degree-specific Graph Neural Networks for Node and Graph Classification.** KDD 2019. [paper](https://arxiv.org/pdf/1906.02319.pdf)

    *Jun Wu, Jingrui He, Jiejun Xu.*

1. **Graph Representation Learning via Hard and Channel-Wise Attention Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1907.04652)

    *Hongyang Gao, Shuiwang Ji.*
    
1. **Graph Learning-Convolutional Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.09971.pdf)

    *Bo Jiang, Ziyan Zhang, Doudou Lin, Jin Tang.*

1. **Data Representation and Learning with Graph Diffusion-Embedding Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Jiang_Data_Representation_and_Learning_With_Graph_Diffusion-Embedding_Networks_CVPR_2019_paper.pdf)

    *Bo Jiang, Doudou Lin, Jin Tang, Bin Luo.*
    
1. **Label Efficient Semi-Supervised Learning via Graph Filtering.** CVPR 2019. [paper](https://arxiv.org/pdf/1901.09993.pdf)

    *Qimai Li, Xiao-Ming Wu, Han Liu, Xiaotong Zhang, Zhichao Guan.*
    
1. **SPAGAN: Shortest Path Graph Attention Network.** IJCAI 2019. [paper](https://cse.buffalo.edu/~jsyuan/papers/2019/SPAGAN_Shortest_Path_Graph_Attention_Network.pdf)

    *Yiding Yang, Xinchao Wang, Mingli Song, Junsong Yuan, Dacheng Tao.*
    
1. **Topology Optimization based Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_to.pdf)

    *Liang Yang, Zesheng Kang, Xiaochun Cao, Di Jin, Bo Yang, Yuanfang Guo.*
    
1. **Hierarchical Graph Convolutional Networks for Semi-supervised Node Classification.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.06667.pdf)

    *Fenyu Hu, Yanqiao Zhu, Shu Wu, Liang Wang, Tieniu Tan.*
    
1. **Masked Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_mask.pdf)

    *Liang Yang, Fan Wu, Yingkui Wang, Junhua Gu, Yuanfang Guo.*
    
1. **Dual Self-Paced Graph Convolutional Network: Towards Reducing Attribute Distortions Induced by Topology.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_paced.pdf)

    *Liang Yang, Zhiyang Chen, Junhua Gu, Yuanfang Guo.* 

1. **Bayesian graph convolutional neural networks for semi-supervised classification.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.11103.pdf)

    *Yingxue Zhang, Soumyasundar Pal, Mark Coates, Deniz Üstebay.*
    
1. **GeniePath: Graph Neural Networks with Adaptive Receptive Paths.** AAAI 2019. [paper](https://arxiv.org/pdf/1802.00910.pdf)

    *Ziqi Liu, Chaochao Chen, Longfei Li, Jun Zhou, Xiaolong Li, Le Song, Yuan Qi.*
    
1. **Gaussian-Induced Convolution for Graphs.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.04393.pdf)

    *Jiatao Jiang, Zhen Cui, Chunyan Xu, Jian Yang.*
    
1. **Fisher-Bures Adversary Graph Convolutional Networks.** UAI 2019. [paper](https://arxiv.org/pdf/1903.04154.pdf)

    *Ke Sun, Piotr Koniusz, Zhen Wang.*
    
1. **N-GCN: Multi-scale Graph Convolution for Semi-supervised Node Classification.** UAI 2019. [paper](https://arxiv.org/pdf/1802.08888.pdf)

    *Sami Abu-El-Haija, Amol Kapoor, Bryan Perozzi, Joonseok Lee.*
    
1. **Confidence-based Graph Convolutional Networks for Semi-Supervised Learning.** AISTATS 2019. [paper](https://arxiv.org/pdf/1901.08255.pdf)

    *Shikhar Vashishth, Prateek Yadav, Manik Bhandari, Partha Talukdar.*
    
1. **Lovasz Convolutional Networks.** AISTATS 2019. [paper](https://arxiv.org/pdf/1805.11365.pdf)

    *Prateek Yadav, Madhav Nimishakavi, Naganand Yadati, Shikhar Vashishth, Arun Rajkumar, Partha Talukdar.*
</details>
    
### [Graph Types](#content)
1. **DyRep: Learning Representations over Dynamic Graphs.** ICLR 2019. [paper](https://openreview.net/pdf?id=HyePrhR5KX)

    *Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha.*

1. **Hypergraph Neural Networks.** AAAI 2019. [paper](https://arxiv.org/pdf/1809.09401.pdf)

    *Yifan Feng, Haoxuan You, Zizhao Zhang, Rongrong Ji, Yue Gao.*

1. **Heterogeneous Graph Attention Network.** WWW 2019. [paper](https://arxiv.org/pdf/1903.07293.pdf)

    *Xiao Wang, Houye Ji, Chuan Shi, Bai Wang, Peng Cui, P. Yu, Yanfang Ye.*
    
1. **Representation Learning for Attributed Multiplex Heterogeneous Network.** KDD 2019. [paper](https://arxiv.org/pdf/1905.01669.pdf)

    *Yukuo Cen, Xu Zou, Jianwei Zhang, Hongxia Yang, Jingren Zhou, Jie Tang.*
    
1. **ActiveHNE: Active Heterogeneous Network Embedding.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.05659.pdf)
    
    *Xia Chen, Guoxian Yu, Jun Wang, Carlotta Domeniconi, Zhao Li, Xiangliang Zhang.*
    
1. **GCN-LASE: Towards Adequately Incorporating Link Attributes in Graph Convolutional Networks.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.09817.pdf)

    *Ziyao Li, Liang Zhang, Guojie Song.*
    
1. **Dynamic Hypergraph Neural Networks.** IJCAI 2019. [paper](https://www.ijcai.org/proceedings/2019/0366.pdf)

    *Jianwen Jiang, Yuxuan Wei, Yifan Feng, Jingxuan Cao, Yue Gao.*
    
1. **Exploiting Interaction Links for Node Classification with Deep Graph Neural Networks.** IJCAI 2019. [paper](https://www.ijcai.org/proceedings/2019/0447.pdf)

    *Hogun Park, Jennifer Neville.*
    
1. **Exploiting Edge Features in Graph Neural Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1809.02709.pdf)

    *Liyu Gong, Qiang Cheng.*  
    

### [Pooling Methods](#content)
1. **Hierarchical Graph Representation Learning with Differentiable Pooling.** NeurIPS 2018. [paper](https://papers.nips.cc/paper/7729-hierarchical-graph-representation-learning-with-differentiable-pooling.pdf)

    *Zhitao Ying, Jiaxuan You, Christopher Morris, Xiang Ren, Will Hamilton, Jure Leskovec.*

1. **Self-Attention Graph Pooling.** ICML 2019. [paper](https://arxiv.org/pdf/1904.08082)

    *Junhyun Lee, Inyeop Lee, Jaewoo Kang.*

1. **Graph U-Nets.** ICML 2019. [paper](http://proceedings.mlr.press/v97/gao19a/gao19a.pdf)

    *Hongyang Gao, Shuiwang Ji.*
    
1. **Graph Convolutional Networks with EigenPooling.** KDD 2019. [paper](https://arxiv.org/pdf/1904.13107.pdf)

    *Yao Ma, Suhang Wang, Charu C. Aggarwal, Jiliang Tang.*
    
1. **Relational Pooling for Graph Representations.** ICML 2019. [paper](https://arxiv.org/pdf/1903.02541)

    *Ryan L. Murphy, Balasubramaniam Srinivasan, Vinayak Rao, Bruno Ribeiro.*
    
### [Analysis](#content)
1. **A Comparison between Recursive Neural Networks and Graph Neural Networks.** IJCNN 2006. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1716174)

    *Vincenzo Di Massa, Gabriele Monfardini, Lorenzo Sarti, Franco Scarselli, Marco Maggini, Marco Gori.*
    
1. **Neural networks for relational learning: an experimental comparison.** Machine Learning 2011. [paper](https://link.springer.com/content/pdf/10.1007%2Fs10994-010-5196-5.pdf)

    *Werner Uwents, Gabriele Monfardini, Hendrik Blockeel, Marco Gori, Franco Scarselli.*
    
1. **Mean-field theory of graph neural networks in graph partitioning.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7689-mean-field-theory-of-graph-neural-networks-in-graph-partitioning.pdf)

    *Tatsuro Kawamoto, Masashi Tsubaki, Tomoyuki Obuchi.*

1. **Representation Learning on Graphs with Jumping Knowledge Networks.** ICML 2018. [paper](https://arxiv.org/pdf/1806.03536.pdf)

    *Keyulu Xu, Chengtao Li, Yonglong Tian, Tomohiro Sonobe, Ken-ichi Kawarabayashi, Stefanie Jegelka.* 
    
1. **Deeper Insights into Graph Convolutional Networks for Semi-Supervised Learning.** AAAI 2018. [paper](https://arxiv.org/pdf/1801.07606.pdf)
    
    *Qimai Li, Zhichao Han, Xiao-Ming Wu.*

1. **How Powerful are Graph Neural Networks?** ICLR 2019. [paper](https://openreview.net/pdf?id=ryGs6iA5Km)

    *Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka.*

1. **Stability and Generalization of Graph Convolutional Neural Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1905.01004.pdf)

    *Saurabh Verma, Zhi-Li Zhang.*

1. **Simplifying Graph Convolutional Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1902.07153)

    *Felix Wu, Tianyi Zhang, Amauri Holanda de Souza Jr., Christopher Fifty, Tao Yu, Kilian Q. Weinberger.*

1. **Explainability Methods for Graph Convolutional Neural Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pope_Explainability_Methods_for_Graph_Convolutional_Neural_Networks_CVPR_2019_paper.pdf)

    *Phillip E. Pope, Soheil Kolouri, Mohammad Rostami, Charles E. Martin, Heiko Hoffmann.*

1. **Can GCNs Go as Deep as CNNs?** ICCV 2019. [paper](https://arxiv.org/pdf/1904.03751.pdf)

    *Guohao Li, Matthias Müller, Ali Thabet, Bernard Ghanem.*

1. **Weisfeiler and Leman Go Neural: Higher-order Graph Neural Networks.** AAAI 2019. [paper](https://arxiv.org/pdf/1810.02244.pdf)    

    *Christopher Morris, Martin Ritzert, Matthias Fey, William L. Hamilton, Jan Eric Lenssen, Gaurav Rattan, Martin Grohe.*
    
### [Efficiency](#content)
1. **Stochastic Training of Graph Convolutional Networks with Variance Reduction.** ICML 2018. [paper](http://www.scipaper.net/uploadfile/2018/0716/20180716100330880.pdf)
    
    *Jianfei Chen, Jun Zhu, Le Song.*
    
1. **FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling.** ICLR 2018. [paper](https://arxiv.org/pdf/1801.10247.pdf)

    *Jie Chen, Tengfei Ma, Cao Xiao.*
    
1. **Adaptive Sampling Towards Fast Graph Representation Learning.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1809.05343.pdf)

    *Wenbing Huang, Tong Zhang, Yu Rong, Junzhou Huang.*
    
1. **Large-Scale Learnable Graph Convolutional Networks.** KDD 2018. [paper](https://arxiv.org/pdf/1808.03965.pdf)

    *Hongyang Gao, Zhengyang Wang, Shuiwang Ji.*
    
1. **Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1905.07953.pdf)

    *Wei-Lin Chiang, Xuanqing Liu, Si Si, Yang Li, Samy Bengio, Cho-Jui Hsieh.*
    
1. **A Degeneracy Framework for Scalable Graph Autoencoders.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.08813.pdf)

    *Guillaume Salha, Romain Hennequin, Viet Anh Tran, Michalis Vazirgiannis.*

## [Applications](#content)

### [Physics](#content)

1. **Discovering objects and their relations from entangled scene representations.** ICLR Workshop 2017. [paper](https://arxiv.org/pdf/1702.05068.pdf)

    *David Raposo, Adam Santoro, David Barrett, Razvan Pascanu, Timothy Lillicrap, Peter Battaglia.*  

1. **A simple neural network module for relational reasoning.** NIPS 2017. [paper](https://arxiv.org/pdf/1706.01427.pdf)

    *Adam Santoro, David Raposo, David G.T. Barrett, Mateusz Malinowski, Razvan Pascanu, Peter Battaglia, Timothy Lillicrap.*  

1. **Interaction Networks for Learning about Objects, Relations and Physics.** NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)

    *Peter Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu.* 
    
1. **Visual Interaction Networks: Learning a Physics Simulator from Video.** NIPS 2017. [paper](http://papers.nips.cc/paper/7040-visual-interaction-networks-learning-a-physics-simulator-from-video.pdf)

    *Nicholas Watters, Andrea Tacchetti, Théophane Weber, Razvan Pascanu, Peter Battaglia, Daniel Zoran.* 

1. **Graph networks as learnable physics engines for inference and control.** ICML 2018. [paper](https://arxiv.org/pdf/1806.01242.pdf)

    *Alvaro Sanchez-Gonzalez, Nicolas Heess, Jost Tobias Springenberg, Josh Merel, Martin Riedmiller, Raia Hadsell, Peter Battaglia.* 

1. **Learning Multiagent Communication with Backpropagation.** NIPS 2016. [paper](https://arxiv.org/pdf/1605.07736.pdf)

    *Sainbayar Sukhbaatar, Arthur Szlam, Rob Fergus.* 

1. **VAIN: Attentional Multi-agent Predictive Modeling.** NIPS 2017 [paper](https://arxiv.org/pdf/1706.06122.pdf)

    *Yedid Hoshen.* 

1. **Neural Relational Inference for Interacting Systems.** ICML 2018. [paper](https://arxiv.org/pdf/1802.04687.pdf)

    *Thomas Kipf, Ethan Fetaya, Kuan-Chieh Wang, Max Welling, Richard Zemel.* 

1. **Graph Element Networks: adaptive, structured computation and memory.** ICML 2019. [paper](https://arxiv.org/pdf/1904.09019)

    *Ferran Alet, Adarsh K. Jeewajee, Maria Bauza, Alberto Rodriguez, Tomas Lozano-Perez, Leslie Pack Kaelbling.*

    
### [Chemistry and Biology](#content)

1. **Convolutional networks on graphs for learning molecular fingerprints.** NIPS 2015. [paper](https://arxiv.org/pdf/1509.09292.pdf)

    *David Duvenaud, Dougal Maclaurin, Jorge Aguilera-Iparraguirre, Rafael Gómez-Bombarelli, Timothy Hirzel, Alán Aspuru-Guzik, Ryan P. Adams.* 

1. **Molecular Graph Convolutions: Moving Beyond Fingerprints.** Journal of computer-aided molecular design 2016. [paper](https://arxiv.org/pdf/1603.00856.pdf)

    *Steven Kearnes, Kevin McCloskey, Marc Berndl, Vijay Pande, Patrick Riley.* 

1. **Protein Interface Prediction using Graph Convolutional Networks.** NIPS 2017. [paper](http://papers.nips.cc/paper/7231-protein-interface-prediction-using-graph-convolutional-networks.pdf)

    *Alex Fout, Jonathon Byrd, Basir Shariat, Asa Ben-Hur.* 

1. **Hybrid Approach of Relation Network and Localized Graph Convolutional Filtering for Breast Cancer Subtype Classification.** IJCAI 2018. [paper](https://arxiv.org/abs/1711.05859)

    *Sungmin Rhee, Seokjun Seo, Sun Kim.*

1. **Modeling polypharmacy side effects with graph convolutional networks.** ISMB 2018. [paper](https://arxiv.org/abs/1802.00543)

    *Marinka Zitnik, Monica Agrawal, Jure Leskovec.*

1. **MR-GNN: Multi-Resolution and Dual Graph Neural Network for Predicting Structured Entity Interactions.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.09558.pdf)

    *Nuo Xu, Pinghui Wang, Long Chen, Jing Tao, Junzhou Zhao.*
    
1. **Pre-training of Graph Augmented Transformers for Medication Recommendation.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.00346.pdf)

    *Junyuan Shang, Tengfei Ma, Cao Xiao, Jimeng Sun.*

1. **GAMENet: Graph Augmented MEmory Networks for Recommending Medication Combination.** AAAI 2019. [paper](https://arxiv.org/pdf/1809.01852.pdf)

    *Junyuan Shang, Cao Xiao, Tengfei Ma, Hongyan Li, Jimeng Sun.*
    
1. **AffinityNet: semi-supervised few-shot learning for disease type prediction.** AAAI 2019. [paper](https://arxiv.org/pdf/1805.08905.pdf)

    *Tianle Ma, Aidong Zhang.*

1. **Graph Transformation Policy Network for Chemical Reaction Prediction.** KDD 2019. [paper](https://arxiv.org/pdf/1812.09441)

    *Kien Do, Truyen Tran, Svetha Venkatesh.*

1. **Functional Transparency for Structured Data: a Game-Theoretic Approach.** ICML 2019. [paper](https://arxiv.org/pdf/1902.09737)

    *Guang-He Lee, Wengong Jin, David Alvarez-Melis, Tommi S. Jaakkola.*

1. **Learning Multimodal Graph-to-Graph Translation for Molecular Optimization.** ICLR 2019. [paper](https://openreview.net/pdf?id=B1xJAsA5F7)

    *Wengong Jin, Kevin Yang, Regina Barzilay, Tommi Jaakkola.*

1. **A Generative Model For Electron Paths.** ICLR 2019. [paper](https://openreview.net/pdf?id=r1x4BnCqKX)

    *John Bradshaw, Matt J. Kusner, Brooks Paige, Marwin H. S. Segler, José Miguel Hernández-Lobato.*

### [Knowledge Graph](#content)
1. **Modeling Relational Data with Graph Convolutional Networks.** ESWC 2018. [paper](https://arxiv.org/pdf/1703.06103.pdf)

    *Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling.*

1. **Cross-lingual Knowledge Graph Alignment via Graph Convolutional Networks.** EMNLP 2018. [paper](http://www.aclweb.org/anthology/D18-1032)

    *Zhichun Wang, Qingsong Lv, Xiaohan Lan, Yu Zhang.*

1. **Representation learning for visual-relational knowledge graphs.** arxiv 2017. [paper](https://arxiv.org/pdf/1709.02314.pdf)

    *Daniel Oñoro-Rubio, Mathias Niepert, Alberto García-Durán, Roberto González, Roberto J. López-Sastre.*
    
1. **End-to-end Structure-Aware Convolutional Networks for Knowledge Base Completion.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.04441.pdf)

    *Chao Shang, Yun Tang, Jing Huang, Jinbo Bi, Xiaodong He, Bowen Zhou.*
    
1. **Knowledge Transfer for Out-of-Knowledge-Base Entities : A Graph Neural Network Approach.** IJCAI 2017. [paper](https://arxiv.org/pdf/1706.05674.pdf)

    *Takuo Hamaguchi, Hidekazu Oiwa, Masashi Shimbo, Yuji Matsumoto.* 

1. **Logic Attention Based Neighborhood Aggregation for Inductive Knowledge Graph Embedding.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.01399.pdf)

    *Peifeng Wang, Jialong Han, Chenliang Li, Rong Pan.*

1. **Dynamic Graph Generation Network: Generating Relational Knowledge from Diagrams.** CVPR 2018. [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kim_Dynamic_Graph_Generation_CVPR_2018_paper.pdf)

    *Haoyu Wang, Defu Lian, Yong Ge.*

1. **Estimating Node Importance in Knowledge Graphs Using Graph Neural Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1905.08865)

    *Namyong Park, Andrey Kan, Xin Luna Dong, Tong Zhao, Christos Faloutsos.*

1. **OAG: Toward Linking Large-scale Heterogeneous Entity Graphs.** KDD 2019. [paper](http://keg.cs.tsinghua.edu.cn/jietang/publications/KDD19-Zhang-et-al-Open_Academic_Graph.pdf)

    *Fanjin Zhang, Xiao Liu, Jie Tang, Yuxiao Dong, Peiran Yao, Jie Zhang, Xiaotao Gu, Yan Wang, Bin Shao, Rui Li, Kuansan Wang.*

1. **Learning Attention-based Embeddings for Relation Prediction in Knowledge Graphs.** ACL 2019. [paper](https://arxiv.org/pdf/1906.01195)

    *Deepak Nathani, Jatin Chauhan, Charu Sharma, Manohar Kaul.*

1. **Cross-lingual Knowledge Graph Alignment via Graph Matching Neural Network.** ACL 2019. [paper](https://128.84.21.199/pdf/1905.11605)

    *Kun Xu, Mo Yu, Yansong Feng, Yan Song, Zhiguo Wang, Dong Yu.*


### [Recommender Systems](#content)

1. **Graph Convolutional Neural Networks for Web-Scale Recommender Systems.** KDD 2018. [paper](https://arxiv.org/abs/1806.01973)

    *Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec.*

1. **Geometric Matrix Completion with Recurrent Multi-Graph Neural Networks.** NIPS 2017. [paper](https://arxiv.org/abs/1704.06803)

    *Federico Monti, Michael M. Bronstein, Xavier Bresson.*

1. **Graph Convolutional Matrix Completion.** 2017. [paper](https://arxiv.org/abs/1706.02263)

    *Rianne van den Berg, Thomas N. Kipf, Max Welling.*

1. **STAR-GCN: Stacked and Reconstructed Graph Convolutional Networks for Recommender Systems.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.13129.pdf)

    *Jiani Zhang, Xingjian Shi, Shenglin Zhao, Irwin King.*
    
1. **Binarized Collaborative Filtering with Distilling Graph Convolutional Networks.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.01829.pdf)

    *Haoyu Wang, Defu Lian, Yong Ge.*
    
1. **Graph Contextualized Self-Attention Network for Session-based Recommendation.** IJCAI 2019. [paper](https://www.ijcai.org/proceedings/2019/0547.pdf)
    
    *Chengfeng Xu, Pengpeng Zhao, Yanchi Liu, Victor S. Sheng, Jiajie Xu, Fuzhen Zhuang, Junhua Fang, Xiaofang Zhou.*

1. **Session-based Recommendation with Graph Neural Networks.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.00855.pdf)

    *Shu Wu, Yuyuan Tang, Yanqiao Zhu, Liang Wang, Xing Xie, Tieniu Tan.*
    
1. **Geometric Hawkes Processes with Graph Convolutional Recurrent Neural Networks.** AAAI 2019. [paper](https://jshang2.github.io/pubs/geo.pdf)

    *Jin Shang, Mingxuan Sun.*

1. **Knowledge-aware Graph Neural Networks with Label Smoothness Regularization for Recommender Systems.** KDD 2019. [paper](https://arxiv.org/pdf/1905.04413)

    *Hongwei Wang, Fuzheng Zhang, Mengdi Zhang, Jure Leskovec, Miao Zhao, Wenjie Li, Zhongyuan Wang.*

1. **Exact-K Recommendation via Maximal Clique Optimization.** KDD 2019. [paper](https://arxiv.org/pdf/1905.07089)

    *Yu Gong, Yu Zhu, Lu Duan, Qingwen Liu, Ziyu Guan, Fei Sun, Wenwu Ou, Kenny Q. Zhu.*

1. **KGAT: Knowledge Graph Attention Network for Recommendation.** KDD 2019. [paper](https://arxiv.org/pdf/1905.07854)

    *Xiang Wang, Xiangnan He, Yixin Cao, Meng Liu, Tat-Seng Chua.*
    
1. **Knowledge Graph Convolutional Networks for Recommender Systems.** WWW 2019. [paper](https://arxiv.org/pdf/1904.12575.pdf)

    *Hongwei Wang, Miao Zhao, Xing Xie, Wenjie Li, Minyi Guo.*
    
1. **Dual Graph Attention Networks for Deep Latent Representation of Multifaceted Social Effects in Recommender Systems.** WWW 2019. [paper](https://arxiv.org/pdf/1903.10433.pdf)

    *Qitian Wu, Hengrui Zhang, Xiaofeng Gao, Peng He, Paul Weng, Han Gao, Guihai Chen.*
    
1. **Graph Neural Networks for Social Recommendation.** WWW 2019. [paper](https://arxiv.org/pdf/1902.07243.pdf)

    *Wenqi Fan, Yao Ma, Qing Li, Yuan He, Eric Zhao, Jiliang Tang, Dawei Yin.*

### [Computer Vision](#content)
1. **Graph Neural Networks for Object Localization.** ECAI 2006. [paper](http://ebooks.iospress.nl/volumearticle/2775)

    *Gabriele Monfardini, Vincenzo Di Massa, Franco Scarselli, Marco Gori.*

1. **Learning Human-Object Interactions by Graph Parsing Neural Networks.** ECCV 2018. [paper](https://arxiv.org/pdf/1808.07962.pdf)

    *Siyuan Qi, Wenguan Wang, Baoxiong Jia, Jianbing Shen, Song-Chun Zhu.*

1. **Learning Conditioned Graph Structures for Interpretable Visual Question Answering.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1806.07243)

    *Will Norcliffe-Brown, Efstathios Vafeias, Sarah Parisot.*

1. **Symbolic Graph Reasoning Meets Convolutions.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7456-symbolic-graph-reasoning-meets-convolutions.pdf)

    *Xiaodan Liang, Zhiting Hu, Hao Zhang, Liang Lin, Eric P. Xing.*

1. **Out of the Box: Reasoning with Graph Convolution Nets for Factual Visual Question Answering.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7531-out-of-the-box-reasoning-with-graph-convolution-nets-for-factual-visual-question-answering.pdf)

    *Medhini Narasimhan, Svetlana Lazebnik, Alexander Schwing.*

1. **Structural-RNN: Deep Learning on Spatio-Temporal Graphs.** CVPR 2016. [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf)

    *Ashesh Jain, Amir R. Zamir, Silvio Savarese, Ashutosh Saxena.*

1. **Relation Networks for Object Detection.** CVPR 2018. [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Hu_Relation_Networks_for_CVPR_2018_paper.pdf)

    *Han Hu, Jiayuan Gu, Zheng Zhang, Jifeng Dai, Yichen Wei.*

1. **Learning Region features for Object Detection.** ECCV 2018. [paper](https://arxiv.org/pdf/1803.07066)

    *Jiayuan Gu, Han Hu, Liwei Wang, Yichen Wei, Jifeng Dai.*

1. **The More You Know: Using Knowledge Graphs for Image Classification.** CVPR 2017. [paper](https://arxiv.org/pdf/1612.04844.pdf)

    *Kenneth Marino, Ruslan Salakhutdinov, Abhinav Gupta.* 

1. **Understanding Kin Relationships in a Photo.** TMM 2012. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6151163)

    *Siyu Xia, Ming Shao, Jiebo Luo, Yun Fu.* 
    
1. **Graph-Structured Representations for Visual Question Answering.** CVPR 2017. [paper](https://arxiv.org/pdf/1609.05600.pdf)

    *Damien Teney, Lingqiao Liu, Anton van den Hengel.* 

1. **Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition.** AAAI 2018. [paper](https://arxiv.org/pdf/1801.07455.pdf)

    *Sijie Yan, Yuanjun Xiong, Dahua Lin.* 

1. **Dynamic Graph CNN for Learning on Point Clouds.** CVPR 2018. [paper](https://arxiv.org/pdf/1801.07829.pdf)

    *Yue Wang, Yongbin Sun, Ziwei Liu, Sanjay E. Sarma, Michael M. Bronstein, Justin M. Solomon.* 

1. **PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation.** CVPR 2018. [paper](https://arxiv.org/pdf/1612.00593.pdf)
    
    *Charles R. Qi, Hao Su, Kaichun Mo, Leonidas J. Guibas.* 

1. **3D Graph Neural Networks for RGBD Semantic Segmentation.** CVPR 2017. [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Qi_3D_Graph_Neural_ICCV_2017_paper.pdf)

    *Xiaojuan Qi, Renjie Liao, Jiaya Jia, Sanja Fidler, Raquel Urtasun.* 

1. **Iterative Visual Reasoning Beyond Convolutions.** CVPR 2018. [paper](https://arxiv.org/pdf/1803.11189)

    *Xinlei Chen, Li-Jia Li, Li Fei-Fei, Abhinav Gupta.* 

1. **Dynamic Edge-Conditioned Filters in Convolutional Neural Networks on Graphs.** CVPR 2017. [paper](https://arxiv.org/pdf/1704.02901)

    *Martin Simonovsky, Nikos Komodakis.* 

1. **Situation Recognition with Graph Neural Networks.** ICCV 2017. [paper](https://arxiv.org/pdf/1708.04320)

    *Ruiyu Li, Makarand Tapaswi, Renjie Liao, Jiaya Jia, Raquel Urtasun, Sanja Fidler.* 

1. **Deep Reasoning with Knowledge Graph for Social Relationship Understanding.** IJCAI 2018. [paper](https://arxiv.org/pdf/1807.00504.pdf)

    *Zhouxia Wang, Tianshui Chen, Jimmy Ren, Weihao Yu, Hui Cheng, Liang Lin.* 

1. **I Know the Relationships: Zero-Shot Action Recognition via Two-Stream Graph Convolutional Networks and Knowledge Graphs.** AAAI 2019. [paper](http://nlpr-web.ia.ac.cn/mmc/homepage/jygao/JY_Gao_files/Conference_Papers/AAAI2019-GJY.pdf)
    
    *Junyu Gao, Tianzhu Zhang, Changsheng Xu.*
    
<details><summary>more</summary>
    
21. **Graph CNNs with Motif and Variable Temporal Block for Skeleton-based Action Recognition.** AAAI 2019. [paper](https://ecs.victoria.ac.nz/foswiki/pub/Groups/Graphics/RGB-DDataProcessingForRobotics/Graph%20CNNs%20with%20Motif%20and%20Variable%20Temporal%20Block%20for%20Skeleton-based%20Action%20Recognition.pdf)

    *Yu-Hui Wen, Lin Gao, Hongbo Fu, Fang-Lue Zhang, Shihong Xia.*
    
1. **Multi-Label Image Recognition with Graph Convolutional Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.03582.pdf)

    *Zhao-Min Chen, Xiu-Shen Wei, Peng Wang, Yanwen Guo.*
    
1. **Spatial-Aware Graph Relation Network for Large-Scale Object Detection.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_Spatial-Aware_Graph_Relation_Network_for_Large-Scale_Object_Detection_CVPR_2019_paper.pdf)

    *Hang Xu, Chenhan Jiang, Xiaodan Liang, Zhenguo Li.*
    
1. **GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)

    *Xinhong Ma, Tianzhu Zhang, Changsheng Xu.*
    
1. **Mind Your Neighbours: Image Annotation With Metadata Neighbourhood Graph Co-Attention Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Mind_Your_Neighbours_Image_Annotation_With_Metadata_Neighbourhood_Graph_Co-Attention_CVPR_2019_paper.pdf)

    *Junjie Zhang, Qi Wu, Jian Zhang, Chunhua Shen, Jianfeng Lu.*
    
1. **Attentive Relational Networks for Mapping Images to Scene Graphs.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.10696.pdf)

    *Mengshi Qi, Weijian Li, Zhengyuan Yang, Yunhong Wang, Jiebo Luo.*
    
1. **Knowledge-Embedded Routing Network for Scene Graph Generation.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.03326.pdf)

    *Tianshui Chen, Weihao Yu, Riquan Chen, Liang Lin.*
    
1. **Auto-Encoding Scene Graphs for Image Captioning.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.02378.pdf)

    *Xu Yang, Kaihua Tang, Hanwang Zhang, Jianfei Cai.*
    
1. **Learning to Cluster Faces on an Affinity Graph.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.02749.pdf)

    *Lei Yang, Xiaohang Zhan, Dapeng Chen, Junjie Yan, Chen Change Loy, Dahua Lin.*
    
1. **Learning a Deep ConvNet for Multi-label Classification with Partial Labels.** CVPR 2019. [paper](https://arxiv.org/pdf/1902.09720.pdf)

    *Thibaut Durand, Nazanin Mehrasa, Greg Mori.*
    
1. **Graph Convolutional Label Noise Cleaner: Train a Plug-and-play Action Classifier for Anomaly Detection.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.07256.pdf)

    *Jia-Xing Zhong, Nannan Li, Weijie Kong, Shan Liu, Thomas H. Li, Ge Li.*
    
1. **Learning Actor Relation Graphs for Group Activity Recognition.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.10117.pdf)

    *Jianchao Wu, Limin Wang, Li Wang, Jie Guo, Gangshan Wu.*
    
1. **ABC: A Big CAD Model Dataset For Geometric Deep Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.06216.pdf)

    *Sebastian Koch, Albert Matveev, Zhongshi Jiang, Francis Williams, Alexey Artemov, Evgeny Burnaev, Marc Alexa, Denis Zorin, Daniele Panozzo.*
    
1. **Neighbourhood Watch: Referring Expression Comprehension via Language-guided Graph Attention Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.04794.pdf)

    *Peng Wang, Qi Wu, Jiewei Cao, Chunhua Shen, Lianli Gao, Anton van den Hengel.*
    
1. **Graph-Based Global Reasoning Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.12814.pdf)

    *Yunpeng Chen, Marcus Rohrbach, Zhicheng Yan, Shuicheng Yan, Jiashi Feng, Yannis Kalantidis.*

1. **Linkage Based Face Clustering via Graph Convolution Network.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.11306.pdf)

    *Zhongdao Wang, Liang Zheng, Yali Li, Shengjin Wang.*
    
1. **Fast Interactive Object Annotation with Curve-GCN.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.06874.pdf)

    *Huan Ling, Jun Gao, Amlan Kar, Wenzheng Chen, Sanja Fidler.*
    
1. **Semantic Graph Convolutional Networks for 3D Human Pose Regression.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.03345.pdf)

    *Long Zhao, Xi Peng, Yu Tian, Mubbasir Kapadia, Dimitris N. Metaxas.*
    
1. **Neural Task Graphs: Generalizing to Unseen Tasks from a Single Video Demonstration.** CVPR 2019. [paper](https://arxiv.org/pdf/1807.03480.pdf)

    *De-An Huang, Suraj Nair, Danfei Xu, Yuke Zhu, Animesh Garg, Li Fei-Fei, Silvio Savarese, Juan Carlos Niebles.*
    
1. **Graphonomy: Universal Human Parsing via Graph Transfer Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.04536.pdf)

    *Ke Gong, Yiming Gao, Xiaodan Liang, Xiaohui Shen, Meng Wang, Liang Lin.*
    
1. **Learning Context Graph for Person Search.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.01830.pdf)

    *Yichao Yan, Qiang Zhang, Bingbing Ni, Wendong Zhang, Minghao Xu, Xiaokang Yang.*
    
1. **Occlusion-Net: 2D/3D Occluded Keypoint Localization Using Graph Networks.** CVPR 2019. [paper](http://www.cs.cmu.edu/~mvo/index_files/Papers/ONet_19.pdf)

    *N. Dinesh Reddy, Minh Vo, Srinivasa G. Narasimhan.*
    
1. **MAN: Moment Alignment Network for Natural Language Moment Retrieval via Iterative Graph Adjustment.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.00087.pdf)

    *Da Zhang, Xiyang Dai, Xin Wang, Yuan-Fang Wang, Larry S. Davis.*
    
1. **Context-Aware Visual Compatibility Prediction.** CVPR 2019. [paper](https://arxiv.org/pdf/1902.03646.pdf)

    *Guillem Cucurull, Perouz Taslakian, David Vazquez.*
    
1. **Graph Attention Convolution for Point Cloud Semantic Segmentation.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Graph_Attention_Convolution_for_Point_Cloud_Semantic_Segmentation_CVPR_2019_paper.pdf)

    *Lei Wang, Yuchun Huang, Yaolin Hou, Shenman Zhang, Jie Shan.*
    
1. **An Attention Enhanced Graph Convolutional LSTM Network for Skeleton-Based Action Recognition.** CVPR 2019. [paper](https://arxiv.org/pdf/1902.09130.pdf)

    *Chenyang Si, Wentao Chen, Wei Wang, Liang Wang, Tieniu Tan.*
    
1. **Actional-Structural Graph Convolutional Networks for Skeleton-based Action Recognition.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.12659.pdf)

    *Maosen Li, Siheng Chen, Xu Chen, Ya Zhang, Yanfeng Wang, Qi Tian.*
    
1. **Graph Convolutional Tracking.** CVPR 2019. [paper](http://nlpr-web.ia.ac.cn/mmc/homepage/jygao/JY_Gao_files/Conference_Papers/GCT-CVPR2019-GJY.pdf)

    *Junyu Gao, Tianzhu Zhang, Changsheng Xu.*
    
1. **Two-Stream Adaptive Graph Convolutional Networks for Skeleton-Based Action Recognition.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_Two-Stream_Adaptive_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.pdf)

    *Lei Shi, Yifan Zhang, Jian Cheng, Hanqing Lu.*

1. **Skeleton-Based Action Recognition With Directed Graph Neural Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_Skeleton-Based_Action_Recognition_With_Directed_Graph_Neural_Networks_CVPR_2019_paper.pdf)

    *Lei Shi, Yifan Zhang, Jian Cheng, Hanqing Lu.*
    
1. **Neural Module Networks.** CVPR 2016. [paper](https://arxiv.org/pdf/1511.02799.pdf)

    *Jacob Andreas, Marcus Rohrbach, Trevor Darrell, Dan Klein.*

1. **LatentGNN: Learning Efficient Non-local Relations for Visual Recognition.** ICML 2019. [paper](https://arxiv.org/pdf/1905.11634)

    *Songyang Zhang, Shipeng Yan, Xuming He.*

1. **Graph Convolutional Gaussian Processes.** ICML 2019. [paper](https://arxiv.org/pdf/1905.05739)

    *Ian Walker, Ben Glocker.*

1. **GEOMetrics: Exploiting Geometric Structure for Graph-Encoded Objects.** ICML 2019. [paper](https://arxiv.org/pdf/1901.11461)

    *Edward J. Smith, Scott Fujimoto, Adriana Romero, David Meger.*
</details>

### [Natural Language Processing](#content)

1. **Conversation Modeling on Reddit using a Graph-Structured LSTM.** TACL 2018. [paper](https://arxiv.org/pdf/1704.02080)

    *Vicky Zayats, Mari Ostendorf.* 

1. **Learning Graphical State Transitions.** ICLR 2017. [paper](https://openreview.net/forum?id=HJ0NvFzxl)

    *Daniel D. Johnson.*

1. **Multiple Events Extraction via Attention-based Graph Information Aggregation.** EMNLP 2018. [paper](https://arxiv.org/pdf/1809.09078.pdf)

    *Xiao Liu, Zhunchen Luo, Heyan Huang.*

1. **Recurrent Relational Networks.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7597-recurrent-relational-networks.pdf)

    *Rasmus Palm, Ulrich Paquet, Ole Winther.*

1. **Improved Semantic Representations From Tree-Structured Long Short-Term Memory Networks.** ACL 2015. [paper](https://www.aclweb.org/anthology/P15-1150)

    *Kai Sheng Tai, Richard Socher, Christopher D. Manning.*

1. **Encoding Sentences with Graph Convolutional Networks for Semantic Role Labeling.** EMNLP 2017. [paper](https://arxiv.org/abs/1703.04826)

    *Diego Marcheggiani, Ivan Titov.*

1. **Graph Convolutional Networks with Argument-Aware Pooling for Event Detection.** AAAI 2018. [paper](http://ix.cs.uoregon.edu/~thien/pubs/graphConv.pdf)

    *Thien Huu Nguyen, Ralph Grishman.*

1. **Exploiting Semantics in Neural Machine Translation with Graph Convolutional Networks.** NAACL 2018. [paper](http://www.aclweb.org/anthology/N18-2078)

    *Diego Marcheggiani, Joost Bastings, Ivan Titov.*

1. **Exploring Graph-structured Passage Representation for Multi-hop Reading Comprehension with Graph Neural Networks.** 2018. [paper](https://arxiv.org/abs/1809.02040)

    *Linfeng Song, Zhiguo Wang, Mo Yu, Yue Zhang, Radu Florian, Daniel Gildea.*

1. **Graph Convolution over Pruned Dependency Trees Improves Relation Extraction.** EMNLP 2018. [paper](https://arxiv.org/abs/1809.10185)

    *Yuhao Zhang, Peng Qi, Christopher D. Manning.*

1. **N-ary relation extraction using graph state LSTM.** EMNLP 18. [paper](https://arxiv.org/abs/1808.09101)

    *Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea.*

1. **A Graph-to-Sequence Model for AMR-to-Text Generation.** ACL 2018. [paper](https://arxiv.org/abs/1805.02473)

    *Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea.*
    
1. **Graph-to-Sequence Learning using Gated Graph Neural Networks.** ACL 2018. [paper](https://arxiv.org/pdf/1806.09835.pdf)

    *Daniel Beck, Gholamreza Haffari, Trevor Cohn.*

1. **Cross-Sentence N-ary Relation Extraction with Graph LSTMs.** TACL. [paper](https://arxiv.org/abs/1708.03743)

    *Nanyun Peng, Hoifung Poon, Chris Quirk, Kristina Toutanova, Wen-tau Yih.*

1. **Sentence-State LSTM for Text Representation.** ACL 2018. [paper](https://arxiv.org/abs/1805.02474)

    *Yue Zhang, Qi Liu, Linfeng Song.*

1. **End-to-End Relation Extraction using LSTMs on Sequences and Tree Structures.** ACL 2016. [paper](https://arxiv.org/abs/1601.00770)

    *Makoto Miwa, Mohit Bansal.*

1. **Graph Convolutional Encoders for Syntax-aware Neural Machine Translation.** EMNLP 2017. [paper](https://arxiv.org/pdf/1704.04675)

    *Joost Bastings, Ivan Titov, Wilker Aziz, Diego Marcheggiani, Khalil Sima'an.* 

1. **Semi-supervised User Geolocation via Graph Convolutional Networks.** ACL 2018. [paper](https://arxiv.org/pdf/1804.08049.pdf)

    *Afshin Rahimi, Trevor Cohn, Timothy Baldwin.* 

1. **Modeling Semantics with Gated Graph Neural Networks for Knowledge Base Question Answering.** COLING 2018. [paper](https://arxiv.org/pdf/1808.04126.pdf)

    *Daniil Sorokin, Iryna Gurevych.* 

1. **Graph Convolutional Networks for Text Classification.** AAAI 2019. [paper](https://arxiv.org/pdf/1809.05679.pdf)

    *Liang Yao, Chengsheng Mao, Yuan Luo.* 
    
<details><summary>more</summary>

21. **Constructing Narrative Event Evolutionary Graph for Script Event Prediction.** IJCAI 2018. [paper](https://arxiv.org/pdf/1805.05081.pdf)

    *Zhongyang Li, Xiao Ding, Ting Liu.* 

1. **Incorporating Syntactic and Semantic Information in Word Embeddings using Graph Convolutional Networks.** ACL 2019. [paper](https://arxiv.org/pdf/1809.04283)

    *Shikhar Vashishth, Manik Bhandari, Prateek Yadav, Piyush Rai, Chiranjib Bhattacharyya, Partha Talukdar*

1. **PaperRobot: Incremental Draft Generation of Scientific Ideas.** ACL 2019. [paper](https://arxiv.org/pdf/1905.07870)

    *Qingyun Wang, Lifu Huang, Zhiying Jiang, Kevin Knight, Heng Ji, Mohit Bansal, Yi Luan.*

1. **Inter-sentence Relation Extraction with Document-level Graph Convolutional Neural Network.** ACL 2019. [paper](https://arxiv.org/pdf/1906.04684)

    *Sunil Kumar Sahu, Fenia Christopoulou, Makoto Miwa, Sophia Ananiadou.*

1. **Textbook Question Answering with Multi-modal Context Graph Understanding and Self-supervised Open-set Comprehension.** ACL 2019. [paper](https://arxiv.org/pdf/1811.00232)

    *Daesik Kim, Seonhoon Kim, Nojun Kwak.*

1. **Multi-hop Reading Comprehension across Multiple Documents by Reasoning over Heterogeneous Graphs.** ACL 2019. [paper](https://arxiv.org/pdf/1905.07374)

    *Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, Bowen Zhou.*

1. **Dynamically Fused Graph Network for Multi-hop Reasoning.** ACL 2019. [paper](https://arxiv.org/pdf/1905.06933)

    *Yunxuan Xiao, Yanru Qu, Lin Qiu, Hao Zhou, Lei Li, Weinan Zhang, Yong Yu.*

1. **Cognitive Graph for Multi-Hop Reading Comprehension at Scale.** ACL 2019. [paper](https://arxiv.org/pdf/1905.05460)

    *Ming Ding, Chang Zhou, Qibin Chen, Hongxia Yang, Jie Tang.*

1. **Joint Type Inference on Entities and Relations via Graph Convolutional Networks.** ACL 2019. [paper](http://www.czsun.site/publications/joint_entrel_gcn.pdf)

    *Changzhi Sun, Yeyun Gong, Yuanbin Wu, Ming Gong, Daxing Jiang, Man Lan, Shiliang Sun1, Nan Duan.*

1. **Attention Guided Graph Convolutional Networks for Relation Extraction.** ACL 2019. [paper](http://www.statnlp.org/wp-content/uploads/2019/06/Attention_Guided_Graph_Convolutional_Networks_for_Relation_Extraction.pdf)

    *Zhijiang Guo, Yan Zhang, Wei Lu.*

1. **GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extraction.** ACL 2019. [paper](https://tsujuifu.github.io/pubs/acl19_graph-rel.pdf)

    *Tsu-Jui Fu, Peng-Hsuan Li, Wei-Yun Ma.*

1. **Graph Neural Networks with Generated Parameters for Relation Extraction.** ACL 2019. [paper](https://arxiv.org/pdf/1902.00756)

    *Hao Zhu, Yankai Lin, Zhiyuan Liu, Jie Fu, Tat-seng Chua, Maosong Sun.*

1. **Generating Logical Forms from Graph Representations of Text and Entities.** ACL 2019. [paper](https://arxiv.org/pdf/1905.08407)

    *Peter Shaw, Philip Massey, Angelica Chen, Francesco Piccinno, Yasemin Altun.*

1. **Matching Article Pairs with Graphical Decomposition and Convolutions.** ACL 2019. [paper](https://arxiv.org/pdf/1802.07459)

    *Bang Liu, Di Niu, Haojie Wei, Jinghong Lin, Yancheng He, Kunfeng Lai, Yu Xu.*

1. **Representing Schema Structure with Graph Neural Networks for Text-to-SQL Parsing.** ACL 2019. [paper](https://arxiv.org/pdf/1905.06241)

    *Ben Bogin, Matt Gardner, Jonathan Berant.*

1. **Coherent Comment Generation for Chinese Articles with a Graph-to-Sequence Model.** ACL 2019. [paper](https://arxiv.org/pdf/1906.01231)

    *Wei Li, Jingjing Xu, Yancheng He, Shengli Yan, Yunfang Wu, Xu sun.*
    
1. **GEAR: Graph-based Evidence Aggregating and Reasoning for Fact Verification.** ACL 2019. [paper](https://www.aclweb.org/anthology/P19-1085)

    *Jie Zhou, Xu Han, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun.*

1. **Look Again at the Syntax: Relational Graph Convolutional Network for Gendered Ambiguous Pronoun Resolution.** ACL 2019. [paper](https://arxiv.org/pdf/1905.08868.pdf)

    *Yinchuan Xu, Junlin Yang.*

1. **Structured Neural Summarization.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1ersoRqtm)

    *Patrick Fernandes, Miltiadis Allamanis, Marc Brockschmidt.*
    
1. **Long-tail Relation Extraction via Knowledge Graph Embeddings and Graph Convolution Networks.** NAACL 2019. [paper](https://arxiv.org/pdf/1903.01306.pdf)

    *Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, Huajun Chen.*
    
1. **Text Generation from Knowledge Graphs with Graph Transformers.** NAACL 2019. [paper](https://arxiv.org/pdf/1904.02342.pdf)

    *Rik Koncel-Kedziorski, Dhanush Bekal, Yi Luan, Mirella Lapata, Hannaneh Hajishirzi.*
    
1. **Question Answering by Reasoning Across Documents with Graph Convolutional Networks.** NAACL 2019. [paper](https://arxiv.org/pdf/1808.09920.pdf)

    *Nicola De Cao, Wilker Aziz, Ivan Titov.*
    
1. **BAG: Bi-directional Attention Entity Graph Convolutional Network for Multi-hop Reasoning Question Answering.** NAACL 2019. [paper](https://arxiv.org/pdf/1904.04969.pdf)

    *Yu Cao, Meng Fang, Dacheng Tao.*
        
1. **GraphIE: A Graph-Based Framework for Information Extraction.** NAACL 2019. [paper](https://arxiv.org/pdf/1810.13083.pdf)

    *Yujie Qian, Enrico Santus, Zhijing Jin, Jiang Guo, Regina Barzilay.*
    
1. **Graph Convolution for Multimodal Information Extraction from Visually Rich Documents.** NAACL 2019. [paper](https://arxiv.org/pdf/1903.11279.pdf)

    *Xiaojing Liu, Feiyu Gao, Qiong Zhang, Huasha Zhao.*

1. **Structural Neural Encoders for AMR-to-text Generation.** NAACL 2019. [paper](https://arxiv.org/pdf/1903.11410.pdf)

    *Marco Damonte, Shay B. Cohen.*
    
1. **Abusive Language Detection with Graph Convolutional Networks.** NAACL 2019. [paper](https://arxiv.org/pdf/1904.04073.pdf)

    *Pushkar Mishra, Marco Del Tredici, Helen Yannakoudakis, Ekaterina Shutova.*
 
1. **Learning Graph Pooling and Hybrid Convolutional Operations for Text Representations.** WWW 2019. [paper](https://arxiv.org/pdf/1901.06965.pdf)

    *Hongyang Gao, Yongjun Chen, Shuiwang Ji.*
</details>
    
### [Generation](#content)

1. **Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1806.02473)

    *Jiaxuan You, Bowen Liu, Rex Ying, Vijay Pande, Jure Leskovec.*

1. **Constrained Generation of Semantically Valid Graphs via Regularizing Variational Autoencoders.** NeurIPS 2018. [paper](https://papers.nips.cc/paper/7942-constrained-generation-of-semantically-valid-graphs-via-regularizing-variational-autoencoders.pdf)

    *Tengfei Ma, Jie Chen, Cao Xiao.*

1. **Learning deep generative models of graphs.** ICLR Workshop 2018. [paper](https://arxiv.org/abs/1803.03324)

    *Yujia Li, Oriol Vinyals, Chris Dyer, Razvan Pascanu, Peter Battaglia.*

1. **MolGAN: An implicit generative model for small molecular graphs.** 2018. [paper](https://arxiv.org/abs/1805.11973)

    *Nicola De Cao, Thomas Kipf.*

1. **GraphRNN: Generating Realistic Graphs with Deep Auto-regressive Models.** ICML 2018. [paper](https://arxiv.org/abs/1802.08773)

    *Jiaxuan You, Rex Ying, Xiang Ren, William L. Hamilton, Jure Leskovec.*

1. **NetGAN: Generating Graphs via Random Walks.** ICML 2018. [paper](https://arxiv.org/abs/1803.00816)

    *Aleksandar Bojchevski, Oleksandr Shchur, Daniel Zügner, Stephan Günnemann.*

1. **Graphite: Iterative Generative Modeling of Graphs.** ICML 2019. [paper](https://arxiv.org/pdf/1803.10459)

    *Aditya Grover, Aaron Zweig, Stefano Ermon.*

1. **Generative Code Modeling with Graphs.** ICLR 2019. [paper](https://openreview.net/pdf?id=Bke4KsA5FX)

    *Marc Brockschmidt, Miltiadis Allamanis, Alexander L. Gaunt, Oleksandr Polozov.*

### [Combinatorial Optimization](#content)

1. **Combinatorial Optimization with Graph Convolutional Networks and Guided Tree Search.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7335-combinatorial-optimization-with-graph-convolutional-networks-and-guided-tree-search.pdf)

    *Zhuwen Li, Qifeng Chen, Vladlen Koltun.*

1. **Learning a SAT Solver from Single-Bit Supervision.** ICLR 2019. [paper](https://arxiv.org/abs/1802.03685)

    *Daniel Selsam, Matthew Lamm, Benedikt Bünz, Percy Liang, Leonardo de Moura, David L. Dill.*

1. **A Note on Learning Algorithms for Quadratic Assignment with Graph Neural Networks.** PADL 2017. [paper](https://www.padl.ws/papers/Paper%2017.pdf)

    *Alex Nowak, Soledad Villar, Afonso S. Bandeira, Joan Bruna.*

1. **Attention Solves Your TSP, Approximately.** 2018. [paper](https://arxiv.org/abs/1803.08475)

    *Wouter Kool, Herke van Hoof, Max Welling.*

1. **Learning to Solve NP-Complete Problems - A Graph Neural Network for Decision TSP.** AAAI 2019. [paper](https://arxiv.org/pdf/1809.02721.pdf)

    *Marcelo O. R. Prates, Pedro H. C. Avelar, Henrique Lemos, Luis Lamb, Moshe Vardi.*

1. **DAG-GNN: DAG Structure Learning with Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1904.10098)

    *Yue Yu, Jie Chen, Tian Gao, Mo Yu.*

### [Adversarial Attack](#content)
1. **Adversarial Attacks on Neural Networks for Graph Data.** KDD 2018. [paper](http://delivery.acm.org/10.1145/3230000/3220078/p2847-zugner.pdf?ip=101.5.139.169&id=3220078&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2E587F3204F5B62A59%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1545706391_e7484be677293ffb5f18b39ce84a0df9)

    *Daniel Zügner, Amir Akbarnejad, Stephan Günnemann.*

1. **Adversarial Attack on Graph Structured Data.** ICML 2018. [paper](https://arxiv.org/abs/1806.02371)

    *Hanjun Dai, Hui Li, Tian Tian, Xin Huang, Lin Wang, Jun Zhu, Le Song.*

1. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.** IJCAI 2019. [paper](https://arxiv.org/pdf/1903.01610.pdf)

    *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.*
    
1. **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.04214.pdf)

    *Kaidi Xu, Hongge Chen, Sijia Liu, Pin-Yu Chen, Tsui-Wei Weng, Mingyi Hong, Xue Lin.*

1. **Robust Graph Convolutional Networks Against Adversarial Attacks.** KDD 2019. [paper](http://pengcui.thumedialab.com/papers/RGCN.pdf)

    *Dingyuan Zhu, Ziwei Zhang, Peng Cui, Wenwu Zhu.*

1. **Certifiable Robustness and Robust Training for Graph Convolutional Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1906.12269)

    *Daniel Zügner, Stephan Günnemann.*

1. **Adversarial Attacks on Node Embeddings via Graph Poisoning.** ICML 2019. [paper](https://arxiv.org/pdf/1809.01093)

    *Aleksandar Bojchevski, Stephan Günnemann.*

1. **Adversarial Attacks on Graph Neural Networks via Meta Learning.** ICLR 2019. [paper]()

    *Daniel Zügner, Stephan Günnemann.*

1. **PeerNets: Exploiting Peer Wisdom Against Adversarial Attacks.** ICLR 2019. [paper](https://openreview.net/pdf?id=Sk4jFoA9K7)

    *Jan Svoboda, Jonathan Masci, Federico Monti, Michael Bronstein, Leonidas Guibas.*

### [Graph Clustering](#content)

1. **Attributed Graph Clustering: A Deep Attentional Embedding Approach.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.06532.pdf)

    *Chun Wang, Shirui Pan, Ruiqi Hu, Guodong Long, Jing Jiang, Chengqi Zhang.*
    
1. **Attributed Graph Clustering via Adaptive Graph Convolution.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.01210.pdf)

    *Xiaotong Zhang, Han Liu, Qimai Li, Xiao-Ming Wu.*
    
### [Graph Classification](#content)
1. **Contextual Graph Markov Model: A Deep and Generative Approach to Graph Processing.** ICML 2018. [paper](https://arxiv.org/pdf/1805.10636.pdf)

    *Davide Bacciu, Federico Errica, Alessio Micheli.*

1. **Semi-Supervised Graph Classification: A Hierarchical Graph Perspective.** WWW 2019. [paper](https://arxiv.org/pdf/1904.05003.pdf)
    
    *Jia Li, Yu Rong, Hong Cheng, Helen Meng, Wenbing Huang, Junzhou Huang.*
    
1. **DDGK: Learning Graph Representations for Deep Divergence Graph Kernels.** WWW 2019. [paper](https://arxiv.org/pdf/1904.09671.pdf)

    *Rami Al-Rfou, Dustin Zelle, Bryan Perozzi.*
    
1. **Unsupervised Inductive Graph-Level Representation Learning via Graph-Graph Proximity.** IJCAI 2019. [paper](https://arxiv.org/pdf/1904.01098.pdf)

    *Yunsheng Bai, Hao Ding, Yang Qiao, Agustin Marinovic, Ken Gu, Ting Chen, Yizhou Sun, Wei Wang.*

### [Reinforcement Learning](#content)

1. **NerveNet: Learning Structured Policy with Graph Neural Networks.** ICLR 2018. [paper](https://openreview.net/pdf?id=S1sqHMZCb)

    *Tingwu Wang, Renjie Liao, Jimmy Ba, Sanja Fidler.* 

1. **Structured Dialogue Policy with Graph Neural Networks.** ICCL 2018. [paper](http://www.aclweb.org/anthology/C18-1107)

    *Lu Chen, Bowen Tan, Sishan Long, Kai Yu.* 
    
1. **Action Schema Networks: Generalised Policies with Deep Learning.** AAAI 2018. [paper](https://arxiv.org/abs/1709.04271)

    *Sam Toyer, Felipe Trevizan, Sylvie Thiébaux, Lexing Xie.*

1. **Relational inductive bias for physical construction in humans and machines.** CogSci 2018. [paper](https://arxiv.org/abs/1806.01203)

    *Jessica B. Hamrick, Kelsey R. Allen, Victor Bapst, Tina Zhu, Kevin R. McKee, Joshua B. Tenenbaum, Peter W. Battaglia.* 

1. **Relational Deep Reinforcement Learning.** arxiv 2018. [paper](https://arxiv.org/abs/1806.01830)

    *Vinicius Zambaldi, David Raposo, Adam Santoro, Victor Bapst, Yujia Li, Igor Babuschkin, Karl Tuyls, David Reichert, Timothy Lillicrap, Edward Lockhart, Murray Shanahan, Victoria Langston, Razvan Pascanu, Matthew Botvinick, Oriol Vinyals, Peter Battaglia.*
    
1. **Playing Text-Adventure Games with Graph-Based Deep Reinforcement Learning.** NAACL 2019. [paper](https://arxiv.org/pdf/1812.01628.pdf)

    *Prithviraj Ammanabrolu, Mark O. Riedl.*

### [Traffic Network](#content)

1. **Spatiotemporal Multi‐Graph Convolution Network for Ride-hailing Demand Forecasting.** AAAI 2019. [paper](http://www-scf.usc.edu/~yaguang/papers/aaai19_multi_graph_convolution.pdf)

    *Xu Geng, Yaguang Li, Leye Wang, Lingyu Zhang, Qiang Yang, Jieping Ye, Yan Liu.*
    
1. **Attention Based Spatial-Temporal Graph Convolutional Networks for Traffic Flow Forecasting.** AAAI 2019. [paper](https://github.com/Davidham3/ASTGCN/blob/master/papers/2019%20AAAI_Attention%20Based%20Spatial-Temporal%20Graph%20Convolutional%20Networks%20for%20Traffic%20Flow%20Forecasting.pdf)

    *Shengnan Guo, Youfang Lin, Ning Feng, Chao Song, Huaiyu Wan.*

1. **Traffic Graph Convolutional Recurrent Neural Network: A Deep Learning Framework for Network-Scale Traffic Learning and Forecasting.** arxiv 2018. [paper](https://arxiv.org/pdf/1802.07007.pdf)

    *Zhiyong Cui, Kristian Henrickson, Ruimin Ke, Yinhai Wang.* 

1. **Spatio-Temporal Graph Convolutional Networks: A Deep Learning Framework for Traffic Forecasting.** IJCAI 2018. [paper](https://arxiv.org/pdf/1709.04875.pdf)
    
    *Bing Yu, Haoteng Yin, Zhanxing Zhu.* 

1. **Origin-Destination Matrix Prediction via Graph Convolution: a New Perspective of Passenger Demand Modeling.** KDD 2019. [paper](https://www.dropbox.com/s/erz0b9c13aeoelj/KDD19-Yuandong.pdf?dl=0)

    *Yuandong Wang, Hongzhi Yin, Hongxu Chen, Tianyu Wo, Jie Xu, Kai Zheng.*

1. **Predicting Path Failure In Time-Evolving Graphs.** KDD 2019. [paper](https://arxiv.org/pdf/1905.03994)

    *Jia Li, Zhichao Han, Hong Cheng, Jiao Su, Pengyun Wang, Jianfeng Zhang, Lujia Pan.*
    
1. **Stochastic Weight Completion for Road Networks using Graph Convolutional Networks.** ICDE 2019. [paper](http://people.cs.aau.dk/~byang/papers/ICDE2019-GCWC.pdf)

    *Jilin Hu, Chenjuan Guo, Bin Yang, Christian S. Jensen.*
    
1. **STG2Seq: Spatial-temporal Graph to Sequence Model for Multi-step Passenger Demand Forecasting.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.10069.pdf)

    *Lei Bai, Lina Yao, Salil.S Kanhere, Xianzhi Wang, Quan.Z Sheng.*
    
1. **Graph WaveNet for Deep Spatial-Temporal Graph Modeling.** IJCAI 2019. [paper](https://shiruipan.github.io/pdf/IJCAI-19-graph-wavenet.pdf)

    *Zonghan Wu, Shirui Pan, Guodong Long, Jing Jiang, Chengqi Zhang.*

### [Few-shot and Zero-shot Learning](#content)

1. **Few-Shot Learning with Graph Neural Networks.** ICLR 2018. [paper](https://arxiv.org/pdf/1711.04043.pdf)

    *Victor Garcia, Joan Bruna.* 

1. **Prototype Propagation Networks (PPN) for Weakly-supervised Few-shot Learning on Category Graph.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.04042.pdf)

    *Lu Liu, Tianyi Zhou, Guodong Long, Jing Jiang, Lina Yao, Chengqi Zhang.*

1. **Edge-labeling Graph Neural Network for Few-shot Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1905.01436.pdf)

    *Jongmin Kim, Taesup Kim, Sungwoong Kim, Chang D. Yoo.*
    
1. **Generating Classification Weights with GNN Denoising Autoencoders for Few-Shot Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1905.01102.pdf)

    *Spyros Gidaris, Nikos Komodakis.*
    
1. **Zero-shot Recognition via Semantic Embeddings and Knowledge Graphs.** CVPR 2018. [paper](https://arxiv.org/pdf/1803.08035.pdf)

    *Xiaolong Wang, Yufei Ye, Abhinav Gupta.* 

1. **Rethinking Knowledge Graph Propagation for Zero-Shot Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1805.11724.pdf)

    *Michael Kampffmeyer, Yinbo Chen, Xiaodan Liang, Hao Wang, Yujia Zhang, Eric P. Xing.* 

1. **Multi-Label Zero-Shot Learning with Structured Knowledge Graphs.** CVPR 2018. [paper](https://arxiv.org/pdf/1711.06526.pdf)

    *Chung-Wei Lee, Wei Fang, Chih-Kuan Yeh, Yu-Chiang Frank Wang.* 

### [Program Representation](#content)

1. **Learning to Represent Programs with Graphs.** ICLR 2018. [paper](https://arxiv.org/abs/1711.00740)

    *Miltiadis Allamanis, Marc Brockschmidt, Mahmoud Khademi.*

1. **Open Vocabulary Learning on Source Code with a Graph-Structured Cache.** ICML 2019. [paper](https://arxiv.org/pdf/1810.08305)

    *Milan Cvitkovic, Badal Singh, Anima Anandkumar.*

### [Social Network](#content)

1. **DeepInf: Social Influence Prediction with Deep Learning.** KDD 2018. [paper](https://arxiv.org/pdf/1807.05560.pdf)

    *Jiezhong Qiu, Jian Tang, Hao Ma, Yuxiao Dong, Kuansan Wang, Jie Tang.*

1. **Characterizing and Forecasting User Engagement with In-app Action Graph: A Case Study of Snapchat.** KDD 2019. [paper](https://arxiv.org/pdf/1906.00355)

    *Yozen Liu, Xiaolin Shi, Lucas Pierce, Xiang Ren.*

1. **MCNE: An End-to-End Framework for Learning Multiple Conditional Network Representations of Social Network.** KDD 2019. [paper](https://arxiv.org/pdf/1905.11013)

    *Hao Wang, Tong Xu, Qi Liu, Defu Lian, Enhong Chen, Dongfang Du, Han Wu, Wen Su.*

1. **Is a Single Vector Enough? Exploring Node Polysemy for Network Embedding.** KDD 2019. [paper](https://arxiv.org/pdf/1905.10668)

    *Ninghao Liu, Qiaoyu Tan, Yuening Li, Hongxia Yang, Jingren Zhou, Xia Hu.*

1. **Encoding Social Information with Graph Convolutional Networks for Political Perspective Detection in News Media.** ACL 2019. [paper](https://www.cs.purdue.edu/homes/dgoldwas//downloads/papers/LiG_acl_2019.pdf)

    *Chang Li, Dan Goldwasser.*
    
1. **Fine-grained Event Categorization with Heterogeneous Graph Convolutional Networks.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.04580.pdf)

    *Hao Peng, Jianxin Li, Qiran Gong, Yangqiu Song, Yuanxing Ning, Kunfeng Lai, Philip S. Yu.*
