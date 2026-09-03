# Awesome Machine Learning for Combinatorial Optimization Resources with stars

We would like to maintain a list of resources that utilize machine learning technologies to solve combinatorial optimization problems.

We mark work contributed by [Thinklab](http://thinklab.sjtu.edu.cn) with ⭐.

*Maintained by members in SJTU-Thinklab: Chang Liu, Runzhong Wang, Jiayi Zhang, Zelin Zhao, Haoyu Geng, Tianzhe Wang, Wenxuan Guo, Wenjie Wu, Nianzu Yang, Ziao Guo, Yang Li, Hao Xiong, Jiale Ma, Wenzheng Pan and Junchi Yan. We also thank [all contributers from the community](https://github.com/Thinklab-SJTU/awesome-ml4co/graphs/contributors) ⭐ 2,165 | 🐛 0 | 🌐 Python | 📅 2026-07-19!*

*We are looking for post-docs interested in machine learning especially for learning combinatorial solvers, dynamic graphs, and reinforcement learning. Please send your up-to-date resume via yanjunchi AT sjtu.edu.cn.*

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr>
<tr><td colspan="2"><a href="#problems">2. Problems</a></td></tr> 
<tr>
	<td>&emsp;<a href=#travelling-salesman-problem>2.1 Travelling Salesman Problem (TSP)</a></td>
	<td>&emsp;<a href=#job-shop-scheduling-problem>2.2 Job Shop Scheduling Problem (JSSP)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#flow-shop-problem>2.3 Flow Shop Problem (FSP)</a></td>
	<td>&emsp;<a href=#sorting-&-ranking>2.4 Sorting & Ranking (Sort&Rank)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#graph-matching>2.5 Graph Matching (GM)</a></td>
	<td>&emsp;<a href=#quadratic-assignment-problem>2.6 Quadratic Assignment Problem (QAP)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#portfolio-optimization>2.7 Portfolio Optimization (PortOpt)</a></td>
	<td>&emsp;<a href=#maximal-cut>2.8 Maximal Cut</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#vehicle-routing-problem>2.9 Vehicle Routing Problem (VRP)</a></td>
	<td>&emsp;<a href=#maximum-independent-set>2.10 Maximum Independent Set</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#generalization>2.11 Generalization</a></td>
	<td>&emsp;<a href=#orienteering-problem>2.12 Orienteering Problem (OP)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#knapsack>2.13 Knapsack</a></td>
	<td>&emsp;<a href=#boolean-satisfiability>2.14 Boolean Satisfiability (SAT)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#computing-resource-allocation>2.15 Computing Resource Allocation</a></td>
	<td>&emsp;<a href=#bin-packing-problem>2.16 Bin Packing Problem (BPP)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#graph-edit-distance>2.17 Graph Edit Distance (GED)</a></td>
	<td>&emsp;<a href=#hamiltonian-cycle-problem>2.18 Hamiltonian Cycle Problem (HCP)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#graph-coloring>2.19 Graph Coloring</a></td>
	<td>&emsp;<a href=#maximal-common-subgraph>2.20 Maximal Common Subgraph (MCS)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#influence-maximization>2.21 Influence Maximization</a></td>
	<td>&emsp;<a href=#max-clique>2.22 Max Clique</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#mixed-integer-programming>2.23 Mixed Integer Programming (MIP)</a></td>
	<td>&emsp;<a href=#causal-discovery>2.24 Causal Discovery</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#game-theoretic-semantics>2.25 Game Theoretic Semantics</a></td>
	<td>&emsp;<a href=#differentiable-optimization>2.26 Differentiable Optimization</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#car-dispatch>2.27 Car Dispatch</a></td>
	<td>&emsp;<a href=#electronic-design-automation>2.28 Electronic Design Automation (EDA)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#conjunctive-query-containment>2.29 Conjunctive Query Containment</a></td>
	<td>&emsp;<a href=#virtual-network-embedding>2.30 Virtual Network Embedding (VNE)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#predict+optimize>2.31 Predict+Optimize</a></td>
	<td>&emsp;<a href=#optimal-power-flow>2.32 Optimal Power Flow</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#facility-location-problem>2.33 Facility Location Problem (FLP)</a></td>
	<td>&emsp;<a href=#combinatorial-drug-recommendation>2.34 Combinatorial Drug Recommendation</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#stochastic-combinatorial-optimization>2.35 Stochastic Combinatorial Optimization</a></td>
	<td>&emsp;<a href=#vertex-cover>2.36 Vertex Cover</a></td>
</tr>
</table>

### [Survey Papers](#content)

1. **Neural Networks for Combinatorial Optimization: A Review of More Than a Decade of Research** INFORMS Journal on Computing, 1999. [journal](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.11.1.15)

   *Kate A. Smith*

2. **Model-Based Search for Combinatorial Optimization: A Critical Survey.** Annals of Operations Research, 2004. [journal](https://link.springer.com/article/10.1023/B:ANOR.0000039526.52305.af)

   *Mark Zlochin, Mauro Birattari, Nicolas Meuleau, Marco Dorigo*

3. **A Survey of Reinforcement Learning and Agent-Based Approaches to Combinatorial Optimization.** Citeseer, 2012. [journal](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.468.5208\&rep=rep1\&type=pdf)

   *Victor Miagkikh*

4. **Machine Learning Approaches to Learning Heuristics for Combinatorial Optimization Problems.** Procedia Manufacturing, 2018. [journal](https://www.sciencedirect.com/science/article/pii/S2351978918311351)

   *Sadegh Mirshekarian, Dusan Sormaz*

5. **Boosting combinatorial problem modeling with machine learning.** IJCAI, 2018. [paper](https://www.ijcai.org/Proceedings/2018/0772.pdf)

   *Michele Lombardi, Michela Milano*

6. **Deep Reinforcement Learning as a Job Shop Scheduling Solver: A Literature Review** Hybrid Intelligent Systems, 2018. [journal](http://link.springer.com/10.1007/978-3-030-14347-3_34)

   *Bruno Cunha, Ana M. Madureira, Benjamim Fonseca, Duarte Coelho*

7. **A Review of combinatorial optimization with graph neural networks.** BigDIA, 2019. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=\&arnumber=8802843)

   *Tingfei Huang, Yang Ma, Yuzhen Zhou, Honglan Huang Huang, Dongmei Chen, Zidan Gong, Yao Liu*

8. **Machine Learning for Combinatorial Optimization: a Methodological Tour d'horizon.** EJOR, 2020. [journal](https://arxiv.org/abs/1811.06128)

   *Yoshua Bengio, Andrea Lodi, Antoine Prouvost*

9. **Reinforcement Learning for Combinatorial Optimization: A Survey.** Arxiv, 2020. [paper](https://arxiv.org/abs/2003.03600)

   *Nina Mazyavkina, Sergey Sviridov, Sergei Ivanov, Evgeny Burnaev*

10. **⭐Learning Graph Matching and Related Combinatorial Optimization Problems.** IJCAI, 2020. [paper](https://www.ijcai.org/proceedings/2020/0694.pdf)

    *Junchi Yan, Shuang Yang, Edwin R. Hancock*

11. **Learning Combinatorial Optimization on Graphs: A Survey with Applications to Networking.** IEEE ACCESS, 2020. [journal](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=\&arnumber=9125934)

    *Natalia Vesselinova, Rebecca Steinert, Daniel F. Perez-Ramirez, Magnus Boman*

12. **From Shallow to Deep Interactions Between Knowledge Representation, Reasoning and Machine Learning.** Arxiv, 2020. [paper](https://arxiv.org/abs/1912.06612)

    *Zied Bouraoui, Antoine Cornuéjols, Thierry Denœux, Sébastien Destercke, Didier Dubois, Romain Guillaume, João Marques-Silva, Jérôme Mengin, Henri Prade, Steven Schockaert, Mathieu Serrurier, Christel Vrain*

13. **A Survey on Reinforcement Learning for Combinatorial Optimization.** Arxiv, 2020. [paper](https://arxiv.org/abs/2008.12248v2)

    *Yunhao Yang, Andrew Whinston*

14. **Research Reviews of Combinatorial Optimization Methods Based on Deep Reinforcement Learning. (in chinese)** 自动化学报, 2020. [journal](http://www.aas.net.cn/article/doi/10.16383/j.aas.c200551)

    *Kai-Wen Li, Tao Zhang, Rui Wang, Wei-Jian Qin, Hui-Hui He, Hong Huang*

15. **Graph Learning for Combinatorial Optimization: A Survey of State-of-the-Art.** Data Science and Engineering, 2021. [journal](https://link.springer.com/article/10.1007/s41019-021-00155-3)

    *Yue Peng, Byron Choi, Jianliang Xu*

16. **Machine Learning for Electronic Design Automation (EDA) : A Survey** TODAES, 2021. [journal](https://arxiv.org/abs/2102.03357)

    *Guyue Huang, Jingbo Hu, Yifan He, Jialong Liu, Mingyuan Ma, Zhaoyang Shen, Juejian Wu, Yuanfan Xu, Hengrui Zhang, Kai Zhong, others*

17. **⭐A Survey for Solving Mixed Integer Programming via Machine Learning** Neurocomputing, 2022. [journal](https://www.sciencedirect.com/science/article/pii/S0925231222014035)

    *Jiayi Zhang, Chang Liu, Xijun Li, Hui-Ling Zhen, Mingxuan Yuan, Yawen Li, Junchi Yan*

18. **Combinatorial Optimization and Reasoning with Graph Neural Networks** JMLR, 2023. [journal](https://jmlr.org/papers/volume24/21-0449/21-0449.pdf)

    *Quentin Cappart, Didier Chetelat, Elias B. Khalil, Andrea Lodi, Christopher Morris, Petar Velickovic*

19. **Applicability of Neural Combinatorial Optimization: A Critical View** TELO, 2024. [journal](https://dl.acm.org/doi/pdf/10.1145/3647644), [code](https://github.com/TheLeprechaun25/Applicability-NCO) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-02-08

    *Andoni I. Garmendia, Josu Ceberio, Alexander Mendiburu*

20. **Survey on Neural Routing Solvers** Arxiv, 2026. [paper](https://arxiv.org/abs/2602.21761)

    *Yunpeng Ba, Xi Lin, Changliang Zhou, Ruihao Zheng, Zhenkun Wang, Xinyan Liang, Zhichao Lu, Jianyong Sun, Yuhua Qian, Qingfu Zhang*

## [Problems](#content)

### [Travelling Salesman Problem](#content)

#### Benchmark Results (Beta)

*Beta feature: benchmark charts are generated from `data/benchmark_results.csv`. The results, sourced directly from original papers using common benchmarks, are presented to directly illustrate the evolution of performance. Runtime is normalized to 1000 instances by instance count only; hardware is not normalized. Gap charts show main-experiment points within benchmark-specific gap bounds (3.5% for TSP-500, 5% otherwise); within each baseline, slower points are shown only when they improve gap.*

##### Uniform TSP-500

[![Uniform TSP-500 benchmark chart](assets/benchmarks/travelling-salesman-problem_uniform-tsp-500_all-baselines.svg)](assets/benchmarks/travelling-salesman-problem_uniform-tsp-500_all-baselines.svg)

##### Uniform TSP-1000

[![Uniform TSP-1000 benchmark chart](assets/benchmarks/travelling-salesman-problem_uniform-tsp-1000_all-baselines.svg)](assets/benchmarks/travelling-salesman-problem_uniform-tsp-1000_all-baselines.svg)

1. **Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model** ICML, 2024. [paper](https://openreview.net/forum?id=BwAkaxqiLB), [code](https://github.com/FeiLiu36/EoH) ⭐ 356 | 🐛 6 | 🌐 Python | 📅 2026-08-06

   *Fei Liu, Xialiang Tong, Mingxuan Yuan, Xi Lin, Fu Luo, Zhenkun Wang, Zhichao Lu, Qingfu Zhang*

2. **An Efficient Graph Convolutional Network Technique for the Travelling Salesman Problem** Arxiv, 2019. [paper](https://arxiv.org/abs/1906.01227), [code](https://github.com/chaitjo/graph-convnet-tsp) ⚠️ Archived

   *Chaitanya K. Joshi, Thomas Laurent, Xavier Bresson*

3. **ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution** NeurIPS, 2024. [paper](https://openreview.net/forum?id=483IPG0HWL), [code](https://github.com/ai4co/reevo) ⭐ 294 | 🐛 0 | 🌐 Python | 📅 2026-01-24

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Federico Berto, Chuanbo Hua, Haeyeon Kim, Jinkyoo Park, Guojie Song*

4. **POMO: Policy Optimization with Multiple Optima for Reinforcement Learning.** NeurIPS, 2020. [paper](https://arxiv.org/abs/2010.16011), [code](https://github.com/yd-kwon/POMO/) ⭐ 267 | 🐛 1 | 🌐 Python | 📅 2022-10-02

   *Yeong-Dae Kwon, Jinho Choo, Byoungjip Kim, Iljoo Yoon, Seungjai Min, Youngjune Gwon*

5. **DIFUSCO: Graph-based Diffusion Solvers for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=JV8Ff0lgVV), [code](https://github.com/Edward-Sun/DIFUSCO) ⭐ 265 | 🐛 2 | 🌐 Python | 📅 2024-09-10

   *Zhiqing Sun, Yiming Yang*

6. **Learning TSP Requires Rethinking Generalization** CP, 2021. [paper](https://arxiv.org/pdf/2006.07054.pdf), [code](https://github.com/chaitjo/learning-tsp) ⚠️ Archived

   *Chaitanya K. Joshi, Quentin Cappart, Louis-Martin Rousseau, Thomas Laurent*

7. **DeepACO: Neural-enhanced Ant Systems for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=cd5D1DD923), [code](https://github.com/henry-yeh/DeepACO) ⭐ 197 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-29

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Helan Liang, Yong Li*

8. **GLOP: Learning Global Partition and Local Construction for Solving Large-Scale Routing Problems in Real-Time** AAAI, 2024. [paper](https://arxiv.org/abs/2312.08224), [code](https://github.com/henry-yeh/GLOP) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2025-01-25

   *Haoran Ye, Jiarui Wang, Helan Liang, Zhiguang Cao, Yong Li, Fanzhang Li*

9. **Neural Combinatorial Optimization with Heavy Decoder: Toward Large Scale Generalization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=RBI4oAbdpm), [code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/LEHD) ⭐ 101 | 🐛 0 | 🌐 Python | 📅 2025-05-28

   *Fu Luo, Xi Lin, Fei Liu, Qingfu Zhang, Zhenkun Wang*

10. **UDC: A Unified Neural Divide-and-Conquer Framework for Large-Scale Combinatorial Optimization Problems** NeurIPS, 2024. [paper](https://openreview.net/pdf?id=dCgbyvmlwL), [code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/UDC-Large-scale-CO-master) ⭐ 101 | 🐛 0 | 🌐 Python | 📅 2025-05-28

    *Zhi Zheng, Changliang Zhou, Tong Xialiang, Mingxuan Yuan, Zhenkun Wang*

11. **⭐LinSATNet: The Positive Linear Satisfiability Neural Networks** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25110), [code](https://github.com/Thinklab-SJTU/LinSATNet) ⭐ 93 | 🐛 1 | 🌐 Python | 📅 2024-04-12

    *Runzhong Wang, Yunhao Zhang, Ziao Guo, Tianyi Chen, Xiaokang Yang, Junchi Yan*

12. **Large Language Models as End-to-end Combinatorial Optimization Solvers** NeurIPS, 2025. [paper](https://neurips.cc/virtual/2025/loc/san-diego/poster/115835), [code](https://github.com/Summer142857/LLMCoSolver) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2025-10-24

    *Xia Jiang, Yaoxin Wu, Minshuo Li, Zhiguang Cao, Yingqian Zhang*

13. **⭐T2T: From Distribution Learning in Training to Gradient Search in Testing for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=JtF0ugNMv2), [code](https://github.com/Thinklab-SJTU/T2TCO) ⭐ 75 | 🐛 0 | 🌐 Python | 📅 2025-07-02

    *Yang Li, Jinpei Guo, Runzhong Wang, Junchi Yan*

14. **Learning Generalizable Models for Vehicle Routing Problems via Knowledge Distillation** NeurIPS, 2022. [paper](https://openreview.net/forum?id=sOVNpUEgKMp), [code](https://github.com/jieyibi/AMDKD) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2025-10-30

    *Jieyi Bi, Yining Ma, Jiahai Wang, Zhiguang Cao, Jinbiao Chen, Yuan Sun, Yeow Meng Chee*

15. **Towards Omni-generalizable Neural Methods for Vehicle Routing Problems** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25267), [code](https://github.com/RoyalSkye/Omni-VRP) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2025-06-03

    *Zhou Jianan, Yaoxin Wu, Wen Song, Zhiguang Cao, Jie Zhang*

16. **Learning 2-opt Heuristics for the Traveling Salesman Problem via Deep Reinforcement Learning** ACML, 2020. [paper](http://proceedings.mlr.press/v129/costa20a), [code](https://github.com/paulorocosta/learning-2opt-drl) ⭐ 58 | 🐛 1 | 🌐 Python | 📅 2020-10-20

    *d O Costa, Paulo R, Jason Rhuggenaath, Yingqian Zhang, Alp Akcay*

17. **H-tsp: Hierarchically solving the large-scale traveling salesman problem** AAAI, 2023. [paper](https://www.microsoft.com/en-us/research/publication/h-tsp-hierarchically-solving-the-large-scale-traveling-salesman-problem/), [code](https://github.com/Learning4Optimization-HUST/H-TSP) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2025-03-21

    *Xuanhao Pan, Yan Jin, Yuandong Ding, Mingxiao Feng, Li Zhao, Lei Song, Jiang Bian*

18. **PARCO: Parallel AutoRegressive Models for Multi-Agent Combinatorial Optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=9F2Cmgo17M), [code](https://github.com/ai4co/parco) ⭐ 57 | 🐛 2 | 🌐 Python | 📅 2025-12-03

    *Federico Berto, Chuanbo Hua, Laurin Luttmann, Jiwoo Son, Junyoung Park, Kyuree Ahn, Changhyun Kwon, Lin Xie, Jinkyoo Park*

19. **Learning to Search Feasible and Infeasible Regions of Routing Problems with Flexible Neural k-Opt** NeurIPS, 2023. [paper](https://openreview.net/forum?id=q1JukwH2yP), [code](https://github.com/yining043/NeuOpt) ⭐ 56 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-07-24

    *Yining Ma, Zhiguang Cao, Yeow Meng Chee*

20. **⭐ML4CO-Bench-101: Benchmark Machine Learning for Classic Combinatorial Problems on Graphs** NeurIPS, 2025. [paper](https://openreview.net/forum?id=ye4ntB1Kzi), [code](https://github.com/Thinklab-SJTU/ML4CO-Bench-101) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2025-11-17

    *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

21. **⭐Unify ML4TSP: Drawing Methodological Principles for TSP and Beyond from Streamlined Design Space of Learning and Search** ICLR, 2025. [paper](https://openreview.net/pdf?id=grU1VKEOLi), [code](https://github.com/Thinklab-SJTU/ML4TSPBench) ⭐ 46 | 🐛 0 | 🌐 C | 📅 2025-05-20

    *Yang Li, Jiale Ma, Wenzheng Pan, Runzhong Wang, Haoyu Geng, Nianzu Yang, Junchi Yan*

22. **BQ-NCO: Bisimulation Quotienting for Efficient Neural Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=BRqlkTDvvm), [code](https://github.com/naver/bq-nco) ⭐ 45 | 🐛 3 | 🌐 Python | 📅 2023-11-17

    *Darko Drakulic, Sofia Michel, Florian Mai, Arnaud Sors, Jean-Marc Andreoli*

23. **Simulation-guided Beam Search for Neural Combinatorial Optimization** NeurIPS, 2022. [paper](https://openreview.net/forum?id=tYAS1Rpys5), [code](https://github.com/yd-kwon/SGBS) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2022-10-02

    *Jinho Choo, Yeong-Dae Kwon, Jihoon Kim, Jeongwoo Jae, Andr{'e} Hottung, Kevin Tierney, Youngjune Gwon*

24. **Pointerformer: Deep Reinforced Multi-Pointer Transformer for the Traveling Salesman Problem** Arxiv, 2023. [paper](https://arxiv.org/abs/2304.09407), [code](https://github.com/Pointerformer/Pointerformer) ⭐ 43 | 🐛 7 | 🌐 Python | 📅 2022-02-16

    *Yan Jin, Yuandong Ding, Xuanhao Pan, Kun He, Li Zhao, Tao Qin, Lei Song, Jiang Bian*

25. **Position: Rethinking Post-Hoc Search-Based Neural Approaches for Solving Large-Scale Traveling Salesman Problems** ICML, 2024. [paper](https://arxiv.org/abs/2406.03503), [code](https://github.com/xyfffff/rethink_mcts_for_tsp) ⭐ 42 | 🐛 2 | 🌐 C | 📅 2025-04-06

    *Yifan Xia, Xianliang Yang, Zichuan Liu, Zhihao Liu, Lei Song, Jiang Bian*

26. **Sym-NCO: Leveraging Symmetricity for Neural Combinatorial Optimization** NeurIPS, 2022. [paper](https://openreview.net/forum?id=kHrE2vi5Rvs), [code](https://github.com/alstn12088/Sym-NCO) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2026-02-20

    *Minsu Kim, Junyoung Park, Jinkyoo Park*

27. **Combining Reinforcement Learning with Lin-Kernighan-Helsgaun Algorithm for the Traveling Salesman Problem** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/17476/17283), [code](https://github.com/JHL-HUST/VSR-LKH-V2) ⭐ 30 | 🐛 1 | 🌐 C | 📅 2024-01-26

    *Jiongzhi Zheng, Kun He, Jianrong Zhou, Yan Jin, Chu-Min Li*

28. **Reinforced Lin–Kernighan–Helsgaun Algorithms for the Traveling Salesman Problems** Knowledge-Based Systems, 2023. [journal](https://www.sciencedirect.com/science/article/pii/S0950705122012400), [code](https://github.com/JHL-HUST/VSR-LKH-V2) ⭐ 30 | 🐛 1 | 🌐 C | 📅 2024-01-26

    *Jiongzhi Zheng, Kun He, Jianrong Zhou, Yan Jin, Chu-Min Li*

29. **G-LNS: Generative Large Neighborhood Search for LLM-Based Automatic Heuristic Design** Arxiv, 2026. [paper](https://arxiv.org/abs/2602.08253), [code](https://github.com/ZBoyn/G-LNS) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2026-02-10

    *Baoyun Zhao, He Wang, Liang Zeng*

30. **Preference Optimization for Combinatorial Optimization Problems** ICML, 2025. [paper](https://openreview.net/forum?id=Jwe5FJ8QGx), [code](https://github.com/MingjunPan/Preference-Optimization-for-Combinatorial-Optimization-Problems) ⭐ 29 | 🐛 3 | 🌐 Python | 📅 2025-06-06

    *Mingjun Pan, Guanquan Lin, You-Wei Luo, Bin Zhu, Zhien Dai, Lijun Sun, Chun Yuan*

31. **EoH-S: Evolution of Heuristic Set using LLMs for Automated Heuristic Design** AAAI, 2026. [paper](https://arxiv.org/abs/2508.03082), [code](https://github.com/FeiLiu36/EoH-S) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-05-20

    *Fei Liu, Yilu Liu, Qingfu Zhang, Xialiang Tong, Mingxuan Yuan*

32. **The First AI4TSP Competition: Learning to Solve Stochastic Routing Problems** Arxiv, 2022. [paper](https://arxiv.org/abs/2201.10453), [code](https://github.com/paulorocosta/ai-for-tsp-competition) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2022-11-22

    *Laurens Bliek, Paulo da Costa, Reza Refaei Afshar, Yingqian Zhang, Tom Catshoek, Daniel Vos, Sicco Verwer, Fynn Schmitt-Ulms, Andre Hottung, Tapan Shah, others*

33. **Distilling Autoregressive Models to Obtain High-Performance Non-autoregressive Solvers for Vehicle Routing Problems with Faster Inference Speed** AAAI, 2024. [paper](https://arxiv.org/abs/2312.12469), [code](https://github.com/xybFight/GNARKD) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2024-03-28

    *Yubin Xiao, Di Wang, Boyang Li, Mingzhao Wang, Xuan Wu, Changliang Zhou, You Zhou*

34. **Efficient Meta Neural Heuristic for Multi-Objective Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=593fc38lhN), [code](https://github.com/bill-cjb/EMNH) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2023-10-25

    *Jinbiao Chen, Jiahai Wang, Zizhen Zhang, Zhiguang Cao, Te Ye, Siyuan Chen*

35. **Neural Multi-Objective Combinatorial Optimization with Diversity Enhancement** NeurIPS, 2023. [paper](https://openreview.net/forum?id=N4JkStI1fe), [code](https://github.com/bill-cjb/NHDE) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2023-10-25

    *Jinbiao Chen, Zizhen Zhang, Zhiguang Cao, Yaoxin Wu, Yining Ma, Te Ye, Jiahai Wang*

36. **⭐COExpander: Adaptive Solution Expansion for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=KMaBXMWsBM), [code](https://github.com/Thinklab-SJTU/COExpander) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2025-06-28

    *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

37. **Optimization by Parallel Quasi-Quantum Annealing with Gradient-Based Sampling** ICLR, 2025. [paper](https://openreview.net/forum?id=9EfBeXaXf0), [code](https://github.com/Yuma-Ichikawa/QQA4CO) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-08-29

    *Yuma Ichikawa, Yamato Arai*

38. **⭐Fast T2T: Optimization Consistency Speeds Up Diffusion-Based Training-to-Testing Solving for Combinatorial Optimization** NeurIPS, 2024. [paper](https://openreview.net/pdf?id=xDrKZOZEOc), [code](https://github.com/Thinklab-SJTU/Fast-T2T) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2025-07-02

    *Yang Li, Jinpei Guo, Runzhong Wang, Hongyuan Zha, Junchi Yan*

39. **Collaboration! Towards Robust Neural Methods for Routing Problems** NeurIPS, 2024. [paper](https://openreview.net/forum?id=YfQA78gEFA), [code](https://github.com/RoyalSkye/Routing-CNF) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2024-11-16

    *Jianan Zhou, Yaoxin Wu, Zhiguang Cao, Wen Song, Jie Zhang, Zhiqi Shen*

40. **⭐ROCO: A General Framework for Evaluating Robustness of Combinatorial Optimization Solvers on Graphs** ICLR, 2023. [paper](https://openreview.net/forum?id=2r6YMqz4Mml), [code](https://github.com/Thinklab-SJTU/ROCO) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2024-10-23

    *Han Lu, Zenan Li, Runzhong Wang, Qibing Ren, Xijun Li, Mingxuan Yuan, Jia Zeng, Xiaokang Yang, Junchi Yan*

41. **Adversarial Generative Flow Network for Solving Vehicle Routing Problems** ICLR, 2025. [paper](https://openreview.net/forum?id=tBom4xOW1H), [code](https://github.com/ZHANG-NI/AGFN) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2025-10-06

    *Ni Zhang, Jingfeng Yang, Zhiguang Cao, Xu Chi*

42. **⭐UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP** ICLR, 2025. [paper](https://openreview.net/forum?id=yEwakMNIex), [code](https://github.com/Thinklab-SJTU/UniCO) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-06-20

    *Wenzheng Pan, Hao Xiong, Jiale Ma, Wentao Zhao, Yang Li, Junchi Yan*

43. **BOPO: Neural Combinatorial Optimization via Best-anchored and Objective-guided Preference Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=FLy6yXdrlW), [code](https://github.com/L-Z-7/BOPO) ⭐ 15 | 🐛 0 | 🌐 Java | 📅 2026-03-01

    *Zijun Liao, Jinbiao Chen, Debing Wang, Zizhen Zhang, Jiahai Wang*

44. **Towards Efficient Constraint Handling in Neural Solvers for Routing Problems** ICLR, 2026. [paper](https://openreview.net/forum?id=raDFGuQxvD), [code](https://github.com/jieyibi/CaR-constraint) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-02-20

    *Jieyi Bi, Zhiguang Cao, Jianan Zhou, Wen Song, Yaoxin Wu, Jie Zhang, Yining Ma, Cathy Wu*

45. **Generalizable Heuristic Generation Through LLMs with Meta-Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2505.20881), [code](https://github.com/yiding-s/MoH) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2026-08-23

    *Yiding Shi, Jianan Zhou, Wen Song, Jieyi Bi, Yaoxin Wu, Zhiguang Cao, Jie Zhang*

46. **FrontierCO: Real-World and Large-Scale Evaluation of Machine Learning Solvers for Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=BVprkacwFY), [code](https://github.com/sunnweiwei/FrontierCO) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2026-05-17

47. **⭐Generation as search operator for test-time scaling of diffusion-based combinatorial optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=9JM03CQwzC), [code](https://github.com/Thinklab-SJTU/GenSCO) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-07-11

    *Yang Li, Lvda Chen, Haonan Wang, Runzhong Wang, Junchi Yan*

48. **MARCO: A Memory-Augmented Reinforcement Framework for Combinatorial Optimization** IJCAI, 2024. [paper](https://www.ijcai.org/proceedings/2024/0766.pdf), [code](https://github.com/TheLeprechaun25/MARCO) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-10-08

    *Andoni I. Garmendia, Quentin Cappart, Josu Ceberio, Alexander Mendiburu*

49. **⭐MaskCO: Masked Generation Drives Effective Representation Learning and Exploiting for Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=psUjNnLhl9), [code](https://github.com/Thinklab-SJTU/MaskCO) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-07-11

    *Lvda Chen, Yang Li, Junchi Yan*

50. **Learning to Insert for Constructive Neural Vehicle Routing Solver** NeurIPS, 2025. [paper](https://openreview.net/forum?id=SXr3Dynctm), [code](https://github.com/CIAM-Group/L2C_Insert) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-10-24

    *Fu Luo, Xi Lin, Mengyuan Zhong, Fei Liu, Zhenkun Wang, Jianyong Sun, Qingfu Zhang*

51. **Neural Improvement Heuristics for Graph Combinatorial Optimization Problems** TNNLS, 2023. [journal](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10271315\&casa_token=Hqn_wH2HAjEAAAAA:rTd6KVaoKVjrFWASa-Ma0vC6CBvsmMUHnoWik2DyD56NbnfNOqBG5qZTBLR5hqf9vpCotivB_BU\&tag=1), [code](https://github.com/TheLeprechaun25/neural-improvement-heuristics) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-10-10

    *Andoni I. Garmendia, Josu Ceberio, Alexander Mendiburu*

52. **Improving Generalization of Neural Combinatorial Optimization for Vehicle Routing Problems via Test-Time Projection Learning** NeurIPS, 2025. [paper](https://openreview.net/forum?id=QPJjiNCRq1), [code](https://github.com/CIAM-Group/TTPL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-10-22

    *Yuanyao Chen, Rongsheng Chen, Fu Luo, Zhenkun Wang*

53. **Projecting Latent RL Actions: Towards Generalizable and Scalable Graph Combinatorial Optimization** Arxiv, 2026. [paper](https://arxiv.org/abs/2605.19721), [code](https://github.com/terranovafr/LaGCO-RL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-07-31

    *Franco Terranova, Guillermo Bernardez, Albert Cabellos-Aparicio, Nina Miolane, Abdelkader Lahmadi*

54. **⭐StruDiCO: Structured Denoising Diffusion with Gradient-free Inference-stage Boosting for Memory and Time Efficient Combinatorial Optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=P69X3V4WwH), [code](https://github.com/yuuuuwang/StruDiCO) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-11-20

    *Yu Wang, Yang Li, Junchi Yan, Yi Chang*

55. **Bridging Synthetic and Real Routing Problems via LLM-Guided Instance Generation and Progressive Adaptation** AAAI, 2026. [paper](https://arxiv.org/abs/2511.10233), [code](https://github.com/HenryZhu1029/EvoReal) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-02-05

    *Jianghan Zhu, Yaoxin Wu, Zhuoyi Lin, Zhengyuan Zhang, Haiyan Yin, Zhiguang Cao, Senthilnath Jayavelu, Xiaoli Li*

56. **Beyond Simple Graphs: Neural Multi-Objective Routing on Multigraphs** ICLR, 2026. [paper](https://arxiv.org/abs/2506.22095), [code](https://github.com/filiprydin/GMS) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-11

    *Filip Rydin, Attila Lischka, Jiaming Wu, Morteza Haghir Chehreghani, Balazs Kulcsar*

57. **Learning Combinatorial Optimization Algorithms over Graphs.** NeurIPS, 2017. [paper](https://arxiv.org/abs/1704.01665)

    *Hanjun Dai, Elias B Khalil, Yuyu Zhang, Bistra Dilkina, Le Song*

58. **Learning Heuristics for the TSP by Policy Gradient** CPAIOR, 2018. [paper](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_12), [code](https://github.com/MichelDeudon/encode-attend-navigate)

    *Michel DeudonPierre CournutAlexandre Lacoste*

59. **Attention, Learn to Solve Routing Problems!** ICLR, 2019. [paper](https://arxiv.org/abs/1803.08475)

    *Wouter Kool, Herke Van Hoof, Max Welling*

60. **Learning to Solve NP-Complete Problems: A Graph Neural Network for Decision TSP.** AAAI, 2019. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/4399)

    *Marcelo Prates, Pedro HC Avelar, Henrique Lemos, Luis C Lamb, Moshe Y. Vardi*

61. **Generalize a Small Pre-trained Model to Arbitrarily Large TSP Instances.** Arxiv, 2020. [paper](https://arxiv.org/abs/2012.10658)

    *Zhang-Hua Fu, Kai-Bin Qiu, Hongyuan Zha*

62. **A Reinforcement Learning Approach for Optimizing Multiple Traveling Salesman Problems over Graphs** KBS, 2020. [journal](https://www.sciencedirect.com/science/article/pii/S0950705120304445)

    *Yujiao Hu, Yuan Yao, Wee Sun Lee*

63. **Deep Reinforcement Learning for Combinatorial Optimization: Covering Salesman Problems.** IEEE Trans Cybern, 2021. [journal](https://arxiv.org/abs/2102.05875)

    *Kaiwen Li, Tao Zhang, Rui Wang Yuheng Wang, Yi Han*

64. **The Transformer Network for the Traveling Salesman Problem** IPAM, 2021. [paper](http://helper.ipam.ucla.edu/publications/dlc2021/dlc2021_16703.pdf)

    *Xavier Bresson，Thomas Laurent*

65. **Learning Improvement Heuristics for Solving Routing Problems** TNNLS, 2021. [journal](https://ieeexplore.ieee.org/abstract/document/9393606?casa_token=mFeyLmrOGfIAAAAA:nmAkjUaTSooYurWHuWGYNoguV453anw9Enyv45xG5jb2oCps6QE4A1CFe1EmFmTzbON6cL5maw)

    *Yaoxin Wu, Wen Song, Zhiguang Cao, Jie Zhang, Andrew Lim*

66. **Reversible Action Design for Combinatorial Optimization with Reinforcement Learning** Arxiv, 2021. [paper](https://arxiv.org/abs/2102.07210)

    *Fan Yao, Renqin Cai, Hongning Wang*

67. **Solving Dynamic Traveling Salesman Problems with Deep Reinforcement Learning.** TNNLS, 2021. [journal](https://ieeexplore.ieee.org/document/9537638)

    *Zizhen Zhang, Hong Liu, Meng Chu Zhou, Jiahai Wang*

68. **ScheduleNet: Learn to Solve Multi-agent Scheduling Problems with Reinforcement Learning** Arxiv, 2021. [paper](https://arxiv.org/abs/2106.03051)

    *Junyoung Park, Sanjar Bakhtiyar, Jinkyoo Park*

69. **DAN: Decentralized Attention-based Neural Network to Solve the MinMax Multiple Traveling Salesman Problem** Arxiv, 2021. [paper](https://arxiv.org/abs/2109.04205)

    *Yuhong Cao, Zhanhong Sun, Guillaume Sartoretti*

70. **Reinforcement Learning for Route Optimization with Robustness Guarantees** IJCAI, 2021. [paper](https://www.ijcai.org/proceedings/2021/0357.pdf)

    *Tobias Jacobs, Francesco Alesiani, Gulcin Ermis*

71. **Learning to Sparsify Travelling Salesman Problem Instances** CPAIOR, 2021. [paper](https://dx.doi.org/10.1007/978-3-030-78230-6_26)

    *James Fitzpatrick, Deepak Ajwani, Paula Carroll*

72. **Graph Neural Network Guided Local Search for the Traveling Salesperson Problem** ICLR, 2022. [paper](https://openreview.net/forum?id=ar92oEosBIg)

    *Benjamin Hudson, Qingbiao Li, Matthew Malencia, Amanda Prorok*

73. **Preference Conditioned Neural Multi-objective Combinatorial Optimization** ICLR, 2022. [paper](https://openreview.net/forum?id=QuObT9BTWo)

    *Xi Lin, Zhiyuan Yang, Qingfu Zhang*

74. **DIMES: A Differentiable Meta Solver for Combinatorial Optimization Problems** NeurIPS, 2022. [paper](https://openreview.net/forum?id=9u05zr0nhx)

    *Ruizhong Qiu, Zhiqing Sun, Yiming Yang*

75. **Generalization of Neural Combinatorial Solvers Through the Lens of Adversarial Robustness** ICLR, 2022. [paper](https://openreview.net/forum?id=vJZ7dPIjip3)

    *Simon Geisler, Johanna Sommer, Jan Schuchardt, Aleksandar Bojchevski, Stephan Günnemann*

76. **Learning to CROSS exchange to solve min-max vehicle routing problems** ICLR, 2023. [paper](https://openreview.net/forum?id=ZcnzsHC10Y)

    *Minjun Kim, Junyoung Park, Jinkyoo Park*

77. **Generalize Learned Heuristics to Solve Large-scale Vehicle Routing Problems in Real-time** ICLR, 2023. [paper](https://openreview.net/forum?id=6ZajpxqTlQ)

    *Qingchun Hou, Jingwei Yang, Yiqiang Su, Xiaoqing Wang, Yuming Deng*

78. **Select and Optimize: Learning to solve large-scale TSP instances** AISTATS, 2023. [paper](https://proceedings.mlr.press/v206/cheng23a.html)

    *Hanni Cheng, Haosi Zheng, Ya Cong, Weihao Jiang, Shiliang Pu*

79. **Multi-View Graph Contrastive Learning for Solving Vehicle Routing Problems** UAI, 2023. [paper](https://openreview.net/pdf?id=Z-mRKVaxVU3)

    *Yuan Jiang, Zhiguang Cao, Yaoxin Wu, Jie Zhang*

80. **Revisiting Sampling for Combinatorial Optimization** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/23661)

    *Haoran, Goshvadi Katayoon, Nova Azade, Schuurmans Dale Sun, Dai Hanjun.*

81. **Meta-SAGE: Scale Meta-Learning Scheduled Adaptation with Guided Exploration for Mitigating Scale Shift on Combinatorial Optimization** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25138)

    *Jiwoo Son, Minsu Kim, Hyeonah Kim, Jinkyoo Park*

82. **Winner Takes It All: Training Performant RL Populations for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=v6VpqGcGAR)

    *Nathan Grinsztajn, Daniel Furelos-Blanco, Shikha Surana, Cl{'e}ment Bonnet, Thomas D Barrett*

83. **Optimizing Solution-Samplers for Combinatorial Problems: The Landscape of Policy-Gradient Methods** NeurIPS, 2023. [paper](https://openreview.net/forum?id=mmTy1iyU5G), [code](https://openreview.net/attachment?id=mmTy1iyU5G\&name=supplementary_material)

    *Constantine Caramanis, Dimitris Fotakis, Alkis Kalavasis, Vasilis Kontonis, Christos Tzamos*

84. **Combinatorial Optimization with Policy Adaptation using Latent Space Search** NeurIPS, 2023. [paper](https://openreview.net/forum?id=vpMBqdt9Hl)

    *Felix Chalumeau, Shikha Surana, Cl{'e}ment Bonnet, Nathan Grinsztajn, Arnu Pretorius, Alexandre Laterre, Thomas D Barrett*

85. **Unsupervised Learning for Solving the Travelling Salesman Problem** NeurIPS, 2023. [paper](https://openreview.net/forum?id=lAEc7aIW20)

    *Yimeng Min, Yiwei Bai, Carla P Gomes*

86. **Ensemble-based Deep Reinforcement Learning for Vehicle Routing Problems under Distribution Shift** NeurIPS, 2023. [paper](https://openreview.net/forum?id=HoBbZ1vPAh)

    *Yuan Jiang, Zhiguang Cao, Yaoxin Wu, Wen Song, Jie Zhang*

87. **Neural Combinatorial Optimization for Robust Routing Problem with Uncertain Travel Times** NeurIPS, 2024. [paper](https://openreview.net/pdf?id=DoewNm2uT3)

    *Pei Xiao, Zizhen Zhang, Jinbiao Chen, Jiahai Wang, Zhenzhen Zhang*

88. **Learning to Handle Complex Constraints for Vehicle Routing Problems** NeurIPS, 2024. [paper](https://openreview.net/forum?id=Ktx95ZuRjP)

    *Jieyi Bi, Yining Ma, Jianan Zhou, Wen Song, Zhiguang Cao, Yaoxin Wu, Jie Zhang*

89. **Rethinking Neural Multi-Objective Combinatorial Optimization via Neat Weight Embedding** ICLR, 2025. [paper](https://openreview.net/forum?id=GM7cmQfk2F)

    *Jinbiao Chen, Zhiguang Cao, Jiahai Wang, Yaoxin Wu, Hanzhang Qin, Zizhen Zhang, Yue-Jiao Gong*

90. **Neural Multi-Objective Combinatorial Optimization via Graph-Image Multimodal Fusion** ICLR, 2025. [paper](https://openreview.net/forum?id=4sJ2FYE65U)

    *Jinbiao Chen, Jiahai Wang, Zhiguang Cao, Yaoxin Wu*

91. **Boosting Neural Combinatorial Optimization for Large-Scale Vehicle Routing Problems** ICLR, 2025. [paper](https://openreview.net/forum?id=TbTJJNjumY)

    *Fu Luo, Xi Lin, Yaoxin Wu, Zhenkun Wang, Tong Xialiang, Mingxuan Yuan, Qingfu Zhang*

92. **Efficient and Robust Neural Combinatorial Optimization via Wasserstein-Based Coresets** ICLR, 2025. [paper](https://openreview.net/forum?id=F57HPKZ6KD)

    *Xu Wang, Fuyou Miao, Wenjie Liu, Yan Xiong*

93. **Neural Solver Selection for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=e0OFWfvLCO)

    *Chengrui Gao, Haopu Shang, Ke Xue, Chao Qian*

94. **Differentiable extensions with rounding guarantees for combinatorial optimization over permutations** NeurIPS, 2025. [paper](https://openreview.net/forum?id=aAxk0cw6GW)

    *Robert R Nerem, Zhishang Luo, Akbar Rafiey, Yusu Wang*

95. **Complexity Scaling Laws for Neural Models using Combinatorial Optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=EdKl4PulMX)

    *Lowell Weissman, Michael Krumdick, A. Lynn Abbott*

96. **Solving the Asymmetric Traveling Salesman Problem via Trace-Guided Cost Augmentation** NeurIPS, 2025. [paper](https://openreview.net/forum?id=CNxrp7u5gV)

    *Zhen Zhang, Javen Qinfeng Shi, Wee Sun Lee*

97. **Neural Combinatorial Optimization for Time-Dependent Traveling Salesman Problem** NeurIPS, 2025. [paper](https://openreview.net/forum?id=UXTR6ZYV1x)

    *Ruixiao Yang, Chuchu Fan*

98. **DRAGON: LLM-Driven Decomposition and Reconstruction Agents for Large-Scale Combinatorial Optimization** AAMAS, 2026. [paper](https://arxiv.org/abs/2601.06502)

    *Shengkai Chen, Zhiguang Cao, Jianan Zhou, Yaoxin Wu, Senthilnath Jayavelu, Zhuoyi Lin, Xiaoli Li, Shili Xiang*

99. **⭐Native Adaptive Solution Expansion for Diffusion-based Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=084SvT55yk)

    *Yu Wang, Yang Li, Jiale Ma, Junchi Yan, Yi Chang*

100. **ViTSP: A Vision Language Models Guided Framework for Solving Large-Scale Traveling Salesman Problems** ICLR, 2026. [paper](https://arxiv.org/abs/2509.23465), [code](https://github.itap.purdue.edu/uSMART/ViTSP_ICLR2026)

     *Zhuoli Yin, Yi Ding, Reem Khir, Hua Cai*

```
*Shengyu Feng, Weiwei Sun, Shanda Li, Ameet Talwalkar, Yiming Yang*
```

101. **Beyond the Heatmap: A Rigorous Evaluation of Component Impact in MCTS-Based TSP Solvers** ICLR, 2026. [paper](https://openreview.net/forum?id=H6PLJnnK6e), [code](https://github.com/LOGO-CUHKSZ/beyond-heatmap-mcts-tsp) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-03-01

```
*Xuanhao Pan, Chenguang Wang, Chaolong Ying, Ye XUE, Tianshu Yu*
```

### [Job Shop Scheduling Problem](#content)

1. **Learning to Dispatch for Job Shop Scheduling via Deep Reinforcement Learning.** NeurIPS, 2020. [paper](https://arxiv.org/abs/2010.12367), [code](https://github.com/zcajiayin/L2D) ⭐ 389 | 🐛 6 | 🌐 Python | 📅 2022-08-31

   *Cong Zhang, Wen Song, Zhiguang Cao, Jie Zhang, Puay Siew Tan, Chi Xu*

2. **DeepACO: Neural-enhanced Ant Systems for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=cd5D1DD923), [code](https://github.com/henry-yeh/DeepACO) ⭐ 197 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-29

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Helan Liang, Yong Li*

3. **Large Language Models as End-to-end Combinatorial Optimization Solvers** NeurIPS, 2025. [paper](https://neurips.cc/virtual/2025/loc/san-diego/poster/115835), [code](https://github.com/Summer142857/LLMCoSolver) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2025-10-24

   *Xia Jiang, Yaoxin Wu, Minshuo Li, Zhiguang Cao, Yingqian Zhang*

4. **ReSched: Rethinking Flexible Job Shop Scheduling from a Transformer-based Architecture with Simplified States** ICLR, 2026. [paper](https://iclr.cc/virtual/2026/poster/10007089), [code](https://github.com/XiangjieXiao/ReSched) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-03-25

   *Xiangjie Xiao, Zhiguang Cao, Cong Zhang, Wen Song*

5. **BOPO: Neural Combinatorial Optimization via Best-anchored and Objective-guided Preference Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=FLy6yXdrlW), [code](https://github.com/L-Z-7/BOPO) ⭐ 15 | 🐛 0 | 🌐 Java | 📅 2026-03-01

   *Zijun Liao, Jinbiao Chen, Debing Wang, Zizhen Zhang, Jiahai Wang*

6. **Multi-Action Self-Improvement for Neural Combinatorial Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2510.12273), [code](https://github.com/LTluttmann/macsim) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2025-11-20

   *Laurin Luttmann, Lin Xie*

7. **Applicability of Neural Combinatorial Optimization: A Critical View** TELO, 2024. [journal](https://dl.acm.org/doi/pdf/10.1145/3647644), [code](https://github.com/TheLeprechaun25/Applicability-NCO) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-02-08

   *Andoni I. Garmendia, Josu Ceberio, Alexander Mendiburu*

8. **Smart Manufacturing Scheduling With Edge Computing Using Multiclass Deep Q Network** Transactions on Industrial Informatics, 2019. [journal](https://ieeexplore.ieee.org/document/8676376)

   *Chun-Cheng Lin, Der-Jiunn Deng, Yen-Ling Chih, Hsin-Ting Chiu*

9. **Multi-Agent Reinforcement Learning for Job Shop Scheduling in Flexible Manufacturing Systems** International Conference on Artificial Intelligence for Industries (AI4I), 2019. [paper](https://ieeexplore.ieee.org/document/9027776)

   *Schirin Baer, Jupiter Bakakeu, Richard Meyes, Tobias Meisen*

10. **ScheduleNet: Learn to Solve Multi-agent Scheduling Problems with Reinforcement Learning** Arxiv, 2021. [paper](https://arxiv.org/abs/2106.03051)

    *Junyoung Park, Sanjar Bakhtiyar, Jinkyoo Park*

11. **Dynamic job-shop scheduling in smart manufacturing using deep reinforcement learning** Computer Networks, 2021. [journal](https://www.sciencedirect.com/science/article/pii/S1389128621001031)

    *Libing Wang, Xin Hu, Yin Wang, Sujie Xu, Shijun Ma, Kexin Yang, Zhijun Liu, Weidong Wang*

12. **Learning to schedule job-shop problems: Representation and policy learning using graph neural network and reinforcement learning.** International Journal of Production Research, 2021. [journal](https://arxiv.org/abs/2106.01086)

    *Junyoung Park, Jaehyeong Chun, Sang Hun Kim, Youngkook Kim, Jinkyoo Park*

13. **Explainable reinforcement learning in production control of job shop manufacturing system.** International Journal of Production Research, 2021. [journal](https://www.tandfonline.com/doi/abs/10.1080/00207543.2021.1972179?journalCode=tprs20)

    *Andreas Kuhnle, Marvin Carl May, Louis Sch?fer, Gisela Lanza*

14. **Winner Takes It All: Training Performant RL Populations for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=v6VpqGcGAR)

    *Nathan Grinsztajn, Daniel Furelos-Blanco, Shikha Surana, Cl{'e}ment Bonnet, Thomas D Barrett*

15. **Combinatorial Optimization with Policy Adaptation using Latent Space Search** NeurIPS, 2023. [paper](https://openreview.net/forum?id=vpMBqdt9Hl)

    *Felix Chalumeau, Shikha Surana, Cl{'e}ment Bonnet, Nathan Grinsztajn, Arnu Pretorius, Alexandre Laterre, Thomas D Barrett*

16. **Neural DAG Scheduling via One-Shot Priority Sampling** ICLR, 2023. [paper](https://openreview.net/forum?id=WL8FlAugqQ)

    *Wonseok Jeon, Mukul Gagrani, Burak Bartan, Weiliang Will Zeng, Harris Teague, Piero Zappi, Christopher Lott*

17. **Robust Scheduling with GFlowNets** ICLR, 2023. [paper](https://openreview.net/forum?id=ZBUthI6wK9h)

    *David W Zhang, Corrado Rainone, Markus Peschl, Roberto Bondesan*

18. **Continual Task Allocation in Meta-Policy Network via Sparse Prompting** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24080)

    *Yijun, Tianyi Zhou, Jing Jiang, Guodong Long Yang, Yuhui Shi.*

19. **Neural Multi-Objective Combinatorial Optimization for Flexible Job Shop Scheduling Problems** ICLR, 2026. [paper](https://openreview.net/forum?id=YAgOaYedLQ)

    *Igor G. Smit, Yaoxin Wu, Pavel Troubil, Yingqian Zhang, Wim P.M. Nuijten*

### [Flow Shop Problem](#content)

1. **PARCO: Parallel AutoRegressive Models for Multi-Agent Combinatorial Optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=9F2Cmgo17M), [code](https://github.com/ai4co/parco) ⭐ 57 | 🐛 2 | 🌐 Python | 📅 2025-12-03

   *Federico Berto, Chuanbo Hua, Laurin Luttmann, Jiwoo Son, Junyoung Park, Kyuree Ahn, Changhyun Kwon, Lin Xie, Jinkyoo Park*

2. **Preference Optimization for Combinatorial Optimization Problems** ICML, 2025. [paper](https://openreview.net/forum?id=Jwe5FJ8QGx), [code](https://github.com/MingjunPan/Preference-Optimization-for-Combinatorial-Optimization-Problems) ⭐ 29 | 🐛 3 | 🌐 Python | 📅 2025-06-06

   *Mingjun Pan, Guanquan Lin, You-Wei Luo, Bin Zhu, Zhien Dai, Lijun Sun, Chun Yuan*

3. **Multi-Action Self-Improvement for Neural Combinatorial Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2510.12273), [code](https://github.com/LTluttmann/macsim) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2025-11-20

   *Laurin Luttmann, Lin Xie*

### [Sorting & Ranking](#content)

1. **Fast Differentiable Sorting and Ranking** ICML, 2020. [paper](http://proceedings.mlr.press/v119/blondel20a/blondel20a.pdf), [code](https://github.com/google-research/fast-soft-sort/) ⚠️ Archived

   *Mathieu Blondel Olivier Teboul Quentin Berthet Josip Djolonga*

2. **Optimizing Rank-Based Metrics With Blackbox Differentiation** CVPR, 2020. [paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rolinek_Optimizing_Rank-Based_Metrics_With_Blackbox_Differentiation_CVPR_2020_paper.pdf), [code](https://github.com/martius-lab/blackbox-backprop) ⭐ 355 | 🐛 3 | 🌐 Python | 📅 2021-12-21

   *Marin Vlastelica, Anselm Paulus, Vít Musil, Georg Martius, Michal Rolínek*

3. **Stochastic Optimization of Sorting Networks via Continuous Relaxations** ICLR, 2019. [paper](https://openreview.net/forum?id=H1eSS3CcKX), [code](https://github.com/ermongroup/neuralsort) ⭐ 151 | 🐛 6 | 🌐 Python | 📅 2023-03-24

   *Aditya Grover, Eric Wang, Aaron Zweig, Stefano Ermon*

4. **PiRank-Scalable Learning To Rank via Differentiable Sorting** NeurIPS, 2022. [paper](https://openreview.net/forum?id=dL8p6rLFTS3), [code](https://github.com/ermongroup/pirank) ⭐ 62 | 🐛 3 | 🌐 Python | 📅 2023-03-24

   *Robin Marcel Edwin Swezey, Aditya Grover, Bruno Charron, Stefano Ermon*

5. **SoftSort: A Continuous Relaxation for the argsort Operator** ICML, 2020. [paper](http://proceedings.mlr.press/v119/prillo20a/prillo20a.pdf), [code](https://github.com/sprillo/softsort) ⭐ 53 | 🐛 5 | 🌐 Python | 📅 2023-03-24

   *Sebastian Prillo, Julian Martin Eisenschlos*

6. **Decision-Focused Learning: Through the Lens of Learning to Rank** ICML, 2022. [paper](https://proceedings.mlr.press/v162/mandi22a.html), [code](https://github.com/jayman91/ltr-predopt) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2022-07-31

   *Jayanta Mandi, Vı́ctor Bucarey, Maxime Mulamba Ke Tchomba, Tias Guns*

7. **Neural Improvement Heuristics for Graph Combinatorial Optimization Problems** TNNLS, 2023. [journal](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10271315\&casa_token=Hqn_wH2HAjEAAAAA:rTd6KVaoKVjrFWASa-Ma0vC6CBvsmMUHnoWik2DyD56NbnfNOqBG5qZTBLR5hqf9vpCotivB_BU\&tag=1), [code](https://github.com/TheLeprechaun25/neural-improvement-heuristics) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-10-10

   *Andoni I. Garmendia, Josu Ceberio, Alexander Mendiburu*

8. **Applicability of Neural Combinatorial Optimization: A Critical View** TELO, 2024. [journal](https://dl.acm.org/doi/pdf/10.1145/3647644), [code](https://github.com/TheLeprechaun25/Applicability-NCO) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-02-08

   *Andoni I. Garmendia, Josu Ceberio, Alexander Mendiburu*

9. **Ranking via sinkhorn propagation** Arxiv, 2011. [paper](https://arxiv.org/abs/1106.1925#)

   *Ryan Prescott Adams, Richard S. Zemel*

10. **Predict+optimise with ranking objectives: exhaustively learning linear functions** IJCAI, 2019. [paper](https://dl.acm.org/doi/abs/10.5555/3367032.3367186)

    *Emir Demirovic, Peter J. Stuckey, James Bailey, Jeffrey Chan, Christopher Leckie, Kotagiri Ramamohanarao, Tias Guns*

11. **Differentiable Ranking and Sorting using Optimal Transport** NeurIPS, 2019. [paper](https://papers.nips.cc/paper/2019/hash/d8c24ca8f23c562a5600876ca2a550ce-Abstract.html)

    *Marco Cuturi, Olivier Teboul, Jean-Philippe Vert*

12. **differentiable top k with optimal transport** NeurIPS, 2020. [paper](https://proceedings.neurips.cc/paper/2020/hash/ec24a54d62ce57ba93a531b460fa8d18-Abstract.html)

    *Yujia Xie, Hanjun Dai, Minshuo Chen, Bo Dai, Tuo Zhao, Hongyuan Zha, Wei Wei, Tomas Pfister*

13. **Automatic Loss Function Search for Predict-Then-Optimize Problems with Strong Ranking Property** ICLR, 2022. [paper](https://openreview.net/forum?id=hSktDu-h94), [code](https://github.com/Microsoft/AutoPredOptConnector)

    *Boshi Wang, Jialin Yi, Hang Dong, Bo Qiao, Chuan Luo, Qingwei Lin*

### [Graph Matching](#content)

1. **⭐Learning Combinatorial Embedding Networks for Deep Graph Matching.** ICCV, 2019. [paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Learning_Combinatorial_Embedding_Networks_for_Deep_Graph_Matching_ICCV_2019_paper.pdf), [code](https://github.com/Thinklab-SJTU/ThinkMatch) ⭐ 881 | 🐛 3 | 🌐 Python | 📅 2026-08-13

   *Runzhong Wang, Junchi Yan, Xiaokang Yang*

2. **⭐Learning deep graph matching with channel-independent embedding and Hungarian attention.** ICLR, 2020. [paper](https://openreview.net/forum?id=rJgBd2NYPH), [code](https://github.com/Thinklab-SJTU/ThinkMatch) ⭐ 881 | 🐛 3 | 🌐 Python | 📅 2026-08-13

   *Tianshu Yu, Runzhong Wang, Junchi Yan, Baoxin Li*

3. **⭐Graduated Assignment for Joint Multi-Graph Matching and Clustering with Application to Unsupervised Graph Matching Network Learning.** NeurIPS, 2020. [paper](https://papers.NeurIPS.cc/paper/2020/file/e6384711491713d29bc63fc5eeb5ba4f-Paper.pdf), [code](https://github.com/Thinklab-SJTU/ThinkMatch) ⭐ 881 | 🐛 3 | 🌐 Python | 📅 2026-08-13

   *Runzhong Wang, Junchi Yan, Xiaokang Yang*

4. **⭐Combinatorial Learning of Robust Deep Graph Matching: An Embedding Based Approach.** TPAMI, 2020. [paper](https://doi.org/10.1109/TPAMI.2020.3005590), [code](https://github.com/Thinklab-SJTU/ThinkMatch) ⭐ 881 | 🐛 3 | 🌐 Python | 📅 2026-08-13

   *Runzhong Wang, Junchi Yan, Xiaokang Yang*

5. **⭐Neural Graph Matching Network: Learning Lawler's Quadratic Assignment Problem with Extension to Hypergraph and Multiple-graph Matching.** TPAMI, 2021. [paper](https://arxiv.org/abs/1911.11308), [code](https://github.com/Thinklab-SJTU/ThinkMatch) ⭐ 881 | 🐛 3 | 🌐 Python | 📅 2026-08-13

   *Runzhong Wang, Junchi Yan, Xiaokang Yang*

6. **LVM-Med: Learning Large-Scale Self-Supervised Vision Models for Medical Imaging via Second-order Graph Matching** NeurIPS, 2023. [paper](https://openreview.net/forum?id=xE7oH5iVGK), [code](https://github.com/duyhominhnguyen/LVM-Med) ⭐ 216 | 🐛 5 | 🌐 Python | 📅 2025-03-18

   *Duy MH Nguyen, Hoang Nguyen, Nghiem T Diep, Tan N Pham, Tri Cao, Binh T Nguyen, Paul Swoboda, Nhat Ho, Shadi Albarqouni, Pengtao Xie, others*

7. **⭐LinSATNet: The Positive Linear Satisfiability Neural Networks** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25110), [code](https://github.com/Thinklab-SJTU/LinSATNet) ⭐ 93 | 🐛 1 | 🌐 Python | 📅 2024-04-12

   *Runzhong Wang, Yunhao Zhang, Ziao Guo, Tianyi Chen, Xiaokang Yang, Junchi Yan*

8. **Deep Graph Matching via Blackbox Differentiation of Combinatorial Solvers.** ECCV, 2020. [paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730409.pdf), [code](https://github.com/martius-lab/blackbox-deep-graph-matching) ⭐ 88 | 🐛 2 | 🌐 Python | 📅 2021-01-11

   *Michal Rolinek, Paul Swoboda, Dominik Zietlow, Anselm Paulus, Vit Musil, Georg Martius*

9. **Revised Note on Learning Algorithms for Quadratic Assignment with Graph Neural Networks** Arxiv, 2017. [paper](https://arxiv.org/pdf/1706.07450.pdf), [code](https://github.com/alexnowakvila/QAP_pt) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2019-12-05

   *Alex Nowak, Soledad Villar, S. Afonso Bandeira, Joan Bruna*

10. **⭐Appearance and Structure Aware Robust Deep Visual Graph Matching: Attack, Defense and Beyond** CVPR, 2022. [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Ren_Appearance_and_Structure_Aware_Robust_Deep_Visual_Graph_Matching_Attack_CVPR_2022_paper.pdf), [code](https://github.com/Thinklab-SJTU/RobustMatch) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2022-03-29

    *Qibing Ren, Qingquan Bao, Runzhong Wang, Junchi Yan*

11. **⭐Self-supervised Learning of Visual Graph Matching** ECCV, 2022. [paper](https://link.springer.com/chapter/10.1007/978-3-031-20050-2_22), [code](https://github.com/Thinklab-SJTU/ThinkMatch-SCGM) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2022-07-12

    *Chang Liu, Shaofeng Zhang, Xiaokang Yang, Junchi Yan*

12. **⭐Revocable Deep Reinforcement Learning with Affinity Regularization for Outlier-Robust Graph Matching.** ICLR, 2023. [paper](https://openreview.net/forum?id=QjQibO3scV_), [code](https://github.com/Thinklab-SJTU/RGM) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2023-02-13

    *Chang Liu, Zetian Jiang, Runzhong Wang, Junchi Yan, Lingxiao Huang, Pinyan Lu*

13. **Learning to Prune Instances of Steiner Tree Problem in Grap** INOC, 2024. [paper](https://openproceedings.org/2024/conf/inoc/INOC_31.pdf), [code](https://github.com/dajwani/alenex22) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-01-28

    *Jiwei Zhang, Dena Tayebi, Saurabh Ray, Deepak Ajwani*

14. **Deep Learning of Graph Matching.** CVPR, 2018. [paper](https://openaccess.thecvf.com/content_cvpr_2018/html/Zanfir_Deep_Learning_of_CVPR_2018_paper.html)

    *Andrei Zanfir, Cristian Sminchisescu*

15. **Deep Graphical Feature Learning for the Feature Matching Problem.** ICCV, 2019. [paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Deep_Graphical_Feature_Learning_for_the_Feature_Matching_Problem_ICCV_2019_paper.pdf)

    *Zhen Zhang, Wee Sun Lee*

16. **GLMNet: Graph Learning-Matching Networks for Feature Matching.** Arxiv, 2019. [paper](https://arxiv.org/abs/1911.07681)

    *Bo Jiang, Pengfei Sun, Jin Tang, Bin Luo*

17. **Deep Graph Matching Consensus.** ICLR, 2020. [paper](http://arxiv.org/abs/2001.09621)

    *Matthias Fey, Jan E. Lenssen, Christopher Morris, Jonathan Masci, Nils M. Kriege*

18. **⭐Deep Latent Graph Matching** ICML, 2021. [paper](http://proceedings.mlr.press/v139/yu21d/yu21d.pdf)

    *Tianshu Yu, Runzhong Wang, Junchi Yan, Baoxin Li*

19. **IA-GM: A Deep Bidirectional Learning Method for Graph Matching** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16461/16268)

    *Kaixuan Zhao, Shikui Tu, Lei Xu*

20. **Deep Graph Matching under Quadratic Constraint** CVPR, 2021. [paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Gao_Deep_Graph_Matching_Under_Quadratic_Constraint_CVPR_2021_paper.pdf)

    *Quankai Gao, Fudong Wang, Nan Xue, Jin-Gang Yu, Gui-Song Xia*

21. **GAMnet: Robust Feature Matching via Graph Adversarial-Matching Network** MM, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3474085.3475669)

    *Bo Jiang, Pengfei Sun, Ziyan Zhang, Jin Tang, Bin Luo*

22. **Hypergraph Neural Networks for Hypergraph Matching** ICCV, 2021. [paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Liao_Hypergraph_Neural_Networks_for_Hypergraph_Matching_ICCV_2021_paper.pdf)

    *Xiaowei Liao, Yong Xu, Haibin Ling*

23. **Learning to Match Features with Seeded Graph Matching Network** ICCV, 2021. [paper](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Learning_To_Match_Features_With_Seeded_Graph_Matching_Network_ICCV_2021_paper.html)

    *Hongkai Chen, Zixin Luo, Jiahui Zhang, Lei Zhou, Xuyang Bai, Zeyu Hu, Chiew-Lan Tai, Long Quan*

24. **SeedGNN: Graph Neural Network for Supervised Seeded Graph Matching** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24282)

    *Liren Yu, Jiaming Xu, Xiaojun Lin*

25. **D2Match: Leveraging Deep Learning and Degeneracy for Subgraph Matching** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24358)

    *Xuan Liu, Lin Zhang, Jiaqi Sun, Yujiu Yang, Haiqing Yang*

26. **Improving Graph Matching with Positional Reconstruction Encoder-Decoder Network** NeurIPS, 2023. [paper](https://openreview.net/forum?id=28RTu9MOT6)

    *Yixiao Zhou, Ruiqi Jia, Hongxiang Lin, Hefeng Quan, Yumeng Zhao, Xiaoqing Lyu*

### [Quadratic Assignment Problem](#content)

1. **⭐Neural Graph Matching Network: Learning Lawler's Quadratic Assignment Problem with Extension to Hypergraph and Multiple-graph Matching.** TPAMI, 2021. [paper](https://arxiv.org/abs/1911.11308), [code](https://github.com/Thinklab-SJTU/ThinkMatch) ⭐ 881 | 🐛 3 | 🌐 Python | 📅 2026-08-13

   *Runzhong Wang, Junchi Yan, Xiaokang Yang*

2. **Revised Note on Learning Algorithms for Quadratic Assignment with Graph Neural Networks** Arxiv, 2017. [paper](https://arxiv.org/pdf/1706.07450.pdf), [code](https://github.com/alexnowakvila/QAP_pt) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2019-12-05

   *Alex Nowak, Soledad Villar, S. Afonso Bandeira, Joan Bruna*

3. **⭐Revocable Deep Reinforcement Learning with Affinity Regularization for Outlier-Robust Graph Matching.** ICLR, 2023. [paper](https://openreview.net/forum?id=QjQibO3scV_), [code](https://github.com/Thinklab-SJTU/RGM) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2023-02-13

   *Chang Liu, Zetian Jiang, Runzhong Wang, Junchi Yan, Lingxiao Huang, Pinyan Lu*

4. **⭐Towards Quantum Machine Learning for Constrained Combinatorial Optimization: a Quantum QAP Solver** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24148)

   *Xinyu Ye, Ge Yan, Junchi Yan*

5. **Differentiable extensions with rounding guarantees for combinatorial optimization over permutations** NeurIPS, 2025. [paper](https://openreview.net/forum?id=aAxk0cw6GW)

   *Robert R Nerem, Zhishang Luo, Akbar Rafiey, Yusu Wang*

### [Portfolio Optimization](#content)

1. **⭐LinSATNet: The Positive Linear Satisfiability Neural Networks** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25110), [code](https://github.com/Thinklab-SJTU/LinSATNet) ⭐ 93 | 🐛 1 | 🌐 Python | 📅 2024-04-12

   *Runzhong Wang, Yunhao Zhang, Ziao Guo, Tianyi Chen, Xiaokang Yang, Junchi Yan*

2. **⭐Towards One-shot Neural Combinatorial Solvers: Theoretical and Empirical Notes on the Cardinality-Constrained Case** ICLR, 2023. [paper](https://openreview.net/forum?id=h21yJhdzbwz), [code](https://github.com/Thinklab-SJTU/One-Shot-Cardinality-NN-Solver) ⭐ 43 | 🐛 1 | 🌐 Python | 📅 2024-09-27

   *Runzhong Wang, Li Shen, Yiting Chen, Junchi Yan, Xiaokang Yang, Dacheng Tao*

3. **Integrating prediction in mean-variance portfolio optimization** Quantitative Finance, 2023. [paper](https://arxiv.org/pdf/2102.09287.pdf)

   *Andrew Butler, Roy H Kwon*

### [Maximal Cut](#content)

1. **Distributed Constrained Combinatorial Optimization leveraging Hypergraph Neural Networks** Nature Machine Intelligence, 2024. [paper](https://arxiv.org/abs/2311.09375), [code](https://github.com/nasheydari/HypOp) ⭐ 93 | 🐛 1 | 🌐 Python | 📅 2024-10-04

   *Nasimeh Heydaribeni, Xinrui Zhan, Ruisi Zhang, Tina Eliassi-Rad, Farinaz Koushanfar*

2. **Let the Flows Tell: Solving Graph Combinatorial Optimization Problems with GFlowNets** NeurlPS, 2023. [paper](https://arxiv.org/abs/2305.17010), [code](https://github.com/zdhNarsil/GFlowNet-CombOpt) ⭐ 69 | 🐛 4 | 🌐 Python | 📅 2023-05-30

   *Dinghuai Zhang, Hanjun Dai, Nikolay Malkin, Aaron Courville, Yoshua Bengio, Ling Pan*

3. **A Diffusion Model Framework for Unsupervised Neural Combinatorial Optimization** ICML, 2024. [paper](https://arxiv.org/abs/2406.01661), [code](https://github.com/ml-jku/DIffUCO) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2025-10-09

   *Sebastian Sanokowski, Sepp Hochreiter, Sebastian Lehner*

4. **DISCS: A Benchmark for Discrete Sampling** NeurlPS, 2023. [paper](https://openreview.net/forum?id=oi1MUMk5NF), [code](https://github.com/google-research/discs) ⚠️ Archived

   *Katayoon Goshvadi, Haoran Sun, Xingchao Liu, Azade Nova, Ruqi Zhang, Will Sussman Grathwohl, Dale Schuurmans, Hanjun Dai*

5. **⭐ML4CO-Bench-101: Benchmark Machine Learning for Classic Combinatorial Problems on Graphs** NeurIPS, 2025. [paper](https://openreview.net/forum?id=ye4ntB1Kzi), [code](https://github.com/Thinklab-SJTU/ML4CO-Bench-101) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2025-11-17

   *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

6. **⭐COExpander: Adaptive Solution Expansion for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=KMaBXMWsBM), [code](https://github.com/Thinklab-SJTU/COExpander) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2025-06-28

   *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

7. **Optimization by Parallel Quasi-Quantum Annealing with Gradient-Based Sampling** ICLR, 2025. [paper](https://openreview.net/forum?id=9EfBeXaXf0), [code](https://github.com/Yuma-Ichikawa/QQA4CO) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-08-29

   *Yuma Ichikawa, Yamato Arai*

8. **LeNSE: Learning To Navigate Subgraph Embeddings for Large-Scale Combinatorial Optimisation** ICML, 2022. [paper](https://proceedings.mlr.press/v162/ireland22a.html), [code](https://github.com/davidireland3/LeNSE) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2022-11-26

   *David Ireland, G. Montana*

9. **Learning to Solve Combinatorial Graph Partitioning Problems via Efficient Exploration** Arxiv, 2022. [paper](https://arxiv.org/abs/2205.14105), [code](https://github.com/tomdbar/ecord) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2022-06-18

   *Thomas D Barrett, Christopher WF Parsonson, Alexandre Laterre*

10. **Variational Annealing on Graphs for Combinatorial Optimization** NeurlPS, 2023. [paper](https://openreview.net/forum?id=SLx7paoaTU), [code](https://github.com/ml-jku/VAG-CO) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-11-22

    *Sebastian Sanokowski, Wilhelm Franz Berghammer, Sepp Hochreiter, Sebastian Lehner*

11. **MARCO: A Memory-Augmented Reinforcement Framework for Combinatorial Optimization** IJCAI, 2024. [paper](https://www.ijcai.org/proceedings/2024/0766.pdf), [code](https://github.com/TheLeprechaun25/MARCO) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-10-08

    *Andoni I. Garmendia, Quentin Cappart, Josu Ceberio, Alexander Mendiburu*

12. **Regularized Langevin Dynamics for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=bbJ0QCujU4), [code](https://github.com/Shengyu-Feng/RLD4CO) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-06-15

    *Shengyu Feng, Yiming Yang*

13. **Efficient Combinatorial Optimization via Heat Diffusion** NeurIPS, 2024. [paper](https://openreview.net/forum?id=psDrko9v1D), [code](https://github.com/AwakerMhy/HeO) ⭐ 8 | 🐛 1 | 🌐 Roff | 📅 2025-03-20

    *Hengyuan Ma, Wenlian Lu, Jianfeng Feng*

14. **Neural Improvement Heuristics for Graph Combinatorial Optimization Problems** TNNLS, 2023. [journal](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10271315\&casa_token=Hqn_wH2HAjEAAAAA:rTd6KVaoKVjrFWASa-Ma0vC6CBvsmMUHnoWik2DyD56NbnfNOqBG5qZTBLR5hqf9vpCotivB_BU\&tag=1), [code](https://github.com/TheLeprechaun25/neural-improvement-heuristics) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-10-10

    *Andoni I. Garmendia, Josu Ceberio, Alexander Mendiburu*

15. **Projecting Latent RL Actions: Towards Generalizable and Scalable Graph Combinatorial Optimization** Arxiv, 2026. [paper](https://arxiv.org/abs/2605.19721), [code](https://github.com/terranovafr/LaGCO-RL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-07-31

    *Franco Terranova, Guillermo Bernardez, Albert Cabellos-Aparicio, Nina Miolane, Abdelkader Lahmadi*

16. **Learning to Explore and Exploit with GNNs for Unsupervised Combinatorial Optimization** ICLR, 2025. [paper](https://openreview.net/forum?id=vaJ4FObpXN), [code](https://github.com/utkuumur/X2GNN) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2025-02-28

    *Utku Umur Acikalin, Aaron M. Ferber, Carla P. Gomes*

17. **Learning Combinatorial Optimization Algorithms over Graphs.** NeurIPS, 2017. [paper](https://arxiv.org/abs/1704.01665)

    *Hanjun Dai, Elias B Khalil, Yuyu Zhang, Bistra Dilkina, Le Song*

18. **Exploratory Combinatorial Optimization with Reinforcement Learning.** AAAI, 2020. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5723)

    *Thomas LBarrett, William Clements, Jakob Foerster, Alex Lvovsky*

19. **Erdos Goes Neural: an Unsupervised Learning Framework for Combinatorial Optimization on Graphs.** NeurIPS, 2020. [paper](https://static.aminer.cn/upload/pdf/575/1127/1864/5eede0b791e0116a23aafe7b_1.pdf)

    *Nikolaos Karalias, Andreas Loukas*

20. **Reversible Action Design for Combinatorial Optimization with Reinforcement Learning** Arxiv, 2021. [paper](https://arxiv.org/abs/2102.07210)

    *Fan Yao, Renqin Cai, Hongning Wang*

21. **Revisiting Sampling for Combinatorial Optimization** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/23661)

    *Haoran, Goshvadi Katayoon, Nova Azade, Schuurmans Dale Sun, Dai Hanjun.*

22. **Optimizing Solution-Samplers for Combinatorial Problems: The Landscape of Policy-Gradient Methods** NeurIPS, 2023. [paper](https://openreview.net/forum?id=mmTy1iyU5G), [code](https://openreview.net/attachment?id=mmTy1iyU5G\&name=supplementary_material)

    *Constantine Caramanis, Dimitris Fotakis, Alkis Kalavasis, Vasilis Kontonis, Christos Tzamos*

23. **Controlling Continuous Relaxation for Combinatorial Optimization** NeurlPS, 2024. [paper](https://openreview.net/pdf?id=ykACV1IhjD)

    *Yuma Ichikawa*

24. **Scalable Discrete Diffusion Samplers: Combinatorial Optimization and Statistical Physics** ICLR, 2025. [paper](https://openreview.net/pdf?id=peNgxpbdxB)

    *Sebastian Sanokowski, Wilhelm Franz Berghammer, Haoyu Peter Wang, Martin Ennemoser, Sepp Hochreiter, Sebastian Lehner*

### [Vehicle Routing Problem](#content)

1. **Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model** ICML, 2024. [paper](https://openreview.net/forum?id=BwAkaxqiLB), [code](https://github.com/FeiLiu36/EoH) ⭐ 356 | 🐛 6 | 🌐 Python | 📅 2026-08-06

   *Fei Liu, Xialiang Tong, Mingxuan Yuan, Xi Lin, Fu Luo, Zhenkun Wang, Zhichao Lu, Qingfu Zhang*

2. **ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution** NeurIPS, 2024. [paper](https://openreview.net/forum?id=483IPG0HWL), [code](https://github.com/ai4co/reevo) ⭐ 294 | 🐛 0 | 🌐 Python | 📅 2026-01-24

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Federico Berto, Chuanbo Hua, Haeyeon Kim, Jinkyoo Park, Guojie Song*

3. **DeepACO: Neural-enhanced Ant Systems for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=cd5D1DD923), [code](https://github.com/henry-yeh/DeepACO) ⭐ 197 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-29

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Helan Liang, Yong Li*

4. **Learning to Perform Local Rewriting for Combinatorial Optimization.** NeurIPS, 2019. [paper](https://arxiv.org/abs/1810.00337), [code](https://github.com/facebookresearch/neural-rewriter) ⚠️ Archived

   *Xinyun Chen, Yuandong Tian*

5. **GLOP: Learning Global Partition and Local Construction for Solving Large-Scale Routing Problems in Real-Time** AAAI, 2024. [paper](https://arxiv.org/abs/2312.08224), [code](https://github.com/henry-yeh/GLOP) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2025-01-25

   *Haoran Ye, Jiarui Wang, Helan Liang, Zhiguang Cao, Yong Li, Fanzhang Li*

6. **Neural Combinatorial Optimization with Heavy Decoder: Toward Large Scale Generalization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=RBI4oAbdpm), [code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/LEHD) ⭐ 101 | 🐛 0 | 🌐 Python | 📅 2025-05-28

   *Fu Luo, Xi Lin, Fei Liu, Qingfu Zhang, Zhenkun Wang*

7. **UDC: A Unified Neural Divide-and-Conquer Framework for Large-Scale Combinatorial Optimization Problems** NeurIPS, 2024. [paper](https://openreview.net/pdf?id=dCgbyvmlwL), [code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/UDC-Large-scale-CO-master) ⭐ 101 | 🐛 0 | 🌐 Python | 📅 2025-05-28

   *Zhi Zheng, Changliang Zhou, Tong Xialiang, Mingxuan Yuan, Zhenkun Wang*

8. **Large Language Models as End-to-end Combinatorial Optimization Solvers** NeurIPS, 2025. [paper](https://neurips.cc/virtual/2025/loc/san-diego/poster/115835), [code](https://github.com/Summer142857/LLMCoSolver) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2025-10-24

   *Xia Jiang, Yaoxin Wu, Minshuo Li, Zhiguang Cao, Yingqian Zhang*

9. **MVMoE: Multi-Task Vehicle Routing Solver with Mixture-of-Experts** ICML, 2024. [paper](https://openreview.net/forum?id=lsQnneYa8p), [code](https://github.com/RoyalSkye/Routing-MVMoE) ⭐ 82 | 🐛 1 | 🌐 Python | 📅 2025-06-03

   *Jianan Zhou, Zhiguang Cao, Yaoxin Wu, Wen Song, Yining Ma, Jie Zhang, Xu Chi*

10. **Learning Generalizable Models for Vehicle Routing Problems via Knowledge Distillation** NeurIPS, 2022. [paper](https://openreview.net/forum?id=sOVNpUEgKMp), [code](https://github.com/jieyibi/AMDKD) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2025-10-30

    *Jieyi Bi, Yining Ma, Jiahai Wang, Zhiguang Cao, Jinbiao Chen, Yuan Sun, Yeow Meng Chee*

11. **Towards Omni-generalizable Neural Methods for Vehicle Routing Problems** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25267), [code](https://github.com/RoyalSkye/Omni-VRP) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2025-06-03

    *Zhou Jianan, Yaoxin Wu, Wen Song, Zhiguang Cao, Jie Zhang*

12. **PARCO: Parallel AutoRegressive Models for Multi-Agent Combinatorial Optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=9F2Cmgo17M), [code](https://github.com/ai4co/parco) ⭐ 57 | 🐛 2 | 🌐 Python | 📅 2025-12-03

    *Federico Berto, Chuanbo Hua, Laurin Luttmann, Jiwoo Son, Junyoung Park, Kyuree Ahn, Changhyun Kwon, Lin Xie, Jinkyoo Park*

13. **Learning to Search Feasible and Infeasible Regions of Routing Problems with Flexible Neural k-Opt** NeurIPS, 2023. [paper](https://openreview.net/forum?id=q1JukwH2yP), [code](https://github.com/yining043/NeuOpt) ⭐ 56 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-07-24

    *Yining Ma, Zhiguang Cao, Yeow Meng Chee*

14. **Multi-Decoder Attention Model with Embedding Glimpse for Solving Vehicle Routing Problems.** AAAI, 2021. [paper](https://arxiv.org/abs/2012.10638), [code](https://github.com/liangxinedu/MDAM) ⭐ 54 | 🐛 2 | 🌐 Python | 📅 2021-07-22

    *Liang Xin, Wen Song, Zhiguang Cao, Jie Zhang*

15. **⭐ML4CO-Bench-101: Benchmark Machine Learning for Classic Combinatorial Problems on Graphs** NeurIPS, 2025. [paper](https://openreview.net/forum?id=ye4ntB1Kzi), [code](https://github.com/Thinklab-SJTU/ML4CO-Bench-101) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2025-11-17

    *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

16. **BQ-NCO: Bisimulation Quotienting for Efficient Neural Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=BRqlkTDvvm), [code](https://github.com/naver/bq-nco) ⭐ 45 | 🐛 3 | 🌐 Python | 📅 2023-11-17

    *Darko Drakulic, Sofia Michel, Florian Mai, Arnaud Sors, Jean-Marc Andreoli*

17. **Reinforcement Learning with Combinatorial Actions: An Application to Vehicle Routing** NeurIPS, 2020. [paper](https://papers.nips.cc/paper/2020/file/06a9d51e04213572ef0720dd27a84792-Paper.pdf), [code](https://github.com/google-research/tf-opt) ⭐ 44 | 🐛 1 | 🌐 C++ | 📅 2026-07-28

    *Arthur Delarue, Ross Anderson, Christian Tjandraatmadja*

18. **Simulation-guided Beam Search for Neural Combinatorial Optimization** NeurIPS, 2022. [paper](https://openreview.net/forum?id=tYAS1Rpys5), [code](https://github.com/yd-kwon/SGBS) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2022-10-02

    *Jinho Choo, Yeong-Dae Kwon, Jihoon Kim, Jeongwoo Jae, Andr{'e} Hottung, Kevin Tierney, Youngjune Gwon*

19. **RRNCO: Towards Real-World Routing with Neural Combinatorial Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2503.16159), [code](https://github.com/ai4co/real-routing-nco) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2026-02-27

    *Jiwoo Son, Zhikai Zhao, Federico Berto, Chuanbo Hua, Zhiguang Cao, Changhyun Kwon, Jinkyoo Park*

20. **Multiagent Environments for Vehicle Routing Problems** INFORMS Journal on Computing, 2026. [paper](https://pubsonline.informs.org/doi/10.1287/ijoc.2025.1211), [code](https://github.com/MAEnvs4VRP/maenvs4vrp) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2026-07-27

    *Ricardo Gama, Ricardo Cunha, Daniel Fuertes, Carlos R. del-Blanco, Hugo L. Fernandes*

21. **Sym-NCO: Leveraging Symmetricity for Neural Combinatorial Optimization** NeurIPS, 2022. [paper](https://openreview.net/forum?id=kHrE2vi5Rvs), [code](https://github.com/alstn12088/Sym-NCO) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2026-02-20

    *Minsu Kim, Junyoung Park, Jinkyoo Park*

22. **G-LNS: Generative Large Neighborhood Search for LLM-Based Automatic Heuristic Design** Arxiv, 2026. [paper](https://arxiv.org/abs/2602.08253), [code](https://github.com/ZBoyn/G-LNS) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2026-02-10

    *Baoyun Zhao, He Wang, Liang Zeng*

23. **Preference Optimization for Combinatorial Optimization Problems** ICML, 2025. [paper](https://openreview.net/forum?id=Jwe5FJ8QGx), [code](https://github.com/MingjunPan/Preference-Optimization-for-Combinatorial-Optimization-Problems) ⭐ 29 | 🐛 3 | 🌐 Python | 📅 2025-06-06

    *Mingjun Pan, Guanquan Lin, You-Wei Luo, Bin Zhu, Zhien Dai, Lijun Sun, Chun Yuan*

24. **EoH-S: Evolution of Heuristic Set using LLMs for Automated Heuristic Design** AAAI, 2026. [paper](https://arxiv.org/abs/2508.03082), [code](https://github.com/FeiLiu36/EoH-S) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-05-20

    *Fei Liu, Yilu Liu, Qingfu Zhang, Xialiang Tong, Mingxuan Yuan*

25. **Distilling Autoregressive Models to Obtain High-Performance Non-autoregressive Solvers for Vehicle Routing Problems with Faster Inference Speed** AAAI, 2024. [paper](https://arxiv.org/abs/2312.12469), [code](https://github.com/xybFight/GNARKD) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2024-03-28

    *Yubin Xiao, Di Wang, Boyang Li, Mingzhao Wang, Xuan Wu, Changliang Zhou, You Zhou*

26. **Efficient Meta Neural Heuristic for Multi-Objective Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=593fc38lhN), [code](https://github.com/bill-cjb/EMNH) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2023-10-25

    *Jinbiao Chen, Jiahai Wang, Zizhen Zhang, Zhiguang Cao, Te Ye, Siyuan Chen*

27. **Neural Multi-Objective Combinatorial Optimization with Diversity Enhancement** NeurIPS, 2023. [paper](https://openreview.net/forum?id=N4JkStI1fe), [code](https://github.com/bill-cjb/NHDE) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2023-10-25

    *Jinbiao Chen, Zizhen Zhang, Zhiguang Cao, Yaoxin Wu, Yining Ma, Te Ye, Jiahai Wang*

28. **⭐COExpander: Adaptive Solution Expansion for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=KMaBXMWsBM), [code](https://github.com/Thinklab-SJTU/COExpander) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2025-06-28

    *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

29. **Collaboration! Towards Robust Neural Methods for Routing Problems** NeurIPS, 2024. [paper](https://openreview.net/forum?id=YfQA78gEFA), [code](https://github.com/RoyalSkye/Routing-CNF) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2024-11-16

    *Jianan Zhou, Yaoxin Wu, Zhiguang Cao, Wen Song, Jie Zhang, Zhiqi Shen*

30. **Adversarial Generative Flow Network for Solving Vehicle Routing Problems** ICLR, 2025. [paper](https://openreview.net/forum?id=tBom4xOW1H), [code](https://github.com/ZHANG-NI/AGFN) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2025-10-06

    *Ni Zhang, Jingfeng Yang, Zhiguang Cao, Xu Chi*

31. **Rethinking Light Decoder-based Solvers for Vehicle Routing Problems** ICLR, 2025. [paper](https://openreview.net/forum?id=4pRwkYpa2u), [code](https://github.com/ziweileonhuang/reld-nco) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2025-04-20

    *Ziwei Huang, Jianan Zhou, Zhiguang Cao, Yixin Xu*

32. **An Agentic Framework with LLMs for Solving Complex Vehicle Routing Problems** ICLR, 2026. [paper](https://openreview.net/forum?id=BMOgYw4EhQ), [code](https://github.com/ZHANG-NI/AFL) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-03-03

    *Ni Zhang, Zhiguang Cao, Jianan Zhou, Cong Zhang, Yew-Soon Ong*

33. **Towards Efficient Constraint Handling in Neural Solvers for Routing Problems** ICLR, 2026. [paper](https://openreview.net/forum?id=raDFGuQxvD), [code](https://github.com/jieyibi/CaR-constraint) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-02-20

    *Jieyi Bi, Zhiguang Cao, Jianan Zhou, Wen Song, Yaoxin Wu, Jie Zhang, Yining Ma, Cathy Wu*

34. **Generalizable Heuristic Generation Through LLMs with Meta-Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2505.20881), [code](https://github.com/yiding-s/MoH) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2026-08-23

    *Yiding Shi, Jianan Zhou, Wen Song, Jieyi Bi, Yaoxin Wu, Zhiguang Cao, Jie Zhang*

35. **A Neural Column Generation Approach to the Vehicle Routing Problem with Two-Dimensional Loading and Last-In-First-Out Constraints** IJCAI, 2024. [paper](https://www.ijcai.org/proceedings/2024/0218.pdf), [code](https://github.com/xyfffff/NCG-for-2L-CVRP) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2024-08-10

    *Yifan Xia, Xiangyi Zhang*

36. **Multi-Action Self-Improvement for Neural Combinatorial Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2510.12273), [code](https://github.com/LTluttmann/macsim) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2025-11-20

    *Laurin Luttmann, Lin Xie*

37. **CaDA: Cross-Problem Routing Solver with Constraint-Aware Dual-Attention** ICML, 2025. [paper](https://openreview.net/forum?id=CS4RyQuTig), [code](https://github.com/CIAM-Group/CaDA) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2025-12-14

    *Han Li, Fei Liu, Zhi Zheng, Yu Zhang, Zhenkun Wang*

38. **Combination-of-Experts with Knowledge Sharing for Cross-Task Vehicle Routing Problems** ICLR, 2026. [paper](https://openreview.net/forum?id=lHBs9mbgwp), [code](https://github.com/yuzikang0/CoEKS) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-04-08

    *Zikang Yu, Jinbiao Chen, Jiahai Wang*

39. **⭐MaskCO: Masked Generation Drives Effective Representation Learning and Exploiting for Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=psUjNnLhl9), [code](https://github.com/Thinklab-SJTU/MaskCO) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-07-11

    *Lvda Chen, Yang Li, Junchi Yan*

40. **Learning to Insert for Constructive Neural Vehicle Routing Solver** NeurIPS, 2025. [paper](https://openreview.net/forum?id=SXr3Dynctm), [code](https://github.com/CIAM-Group/L2C_Insert) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-10-24

    *Fu Luo, Xi Lin, Mengyuan Zhong, Fei Liu, Zhenkun Wang, Jianyong Sun, Qingfu Zhang*

41. **Chain-of-Context Learning: Dynamic Constraint Understanding for Multi-Task VRPs** ICLR, 2026. [paper](https://openreview.net/forum?id=AhE6aSlz5g), [code](https://github.com/gshuangchun/CCL-MTLVRP) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-26

    *Shuangchun Gui, Suyu Liu, Xuehe Wang, Zhiguang Cao*

42. **RADAR: Learning to Route with Asymmetry-aware Distance Representations** ICLR, 2026. [paper](https://openreview.net/forum?id=lWdxX5s9T1), [code](https://github.com/yihang0410/RADAR) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-03-19

    *Hang Yi, Ziwei Huang, Yining Ma, Zhiguang Cao*

43. **Improving Generalization of Neural Combinatorial Optimization for Vehicle Routing Problems via Test-Time Projection Learning** NeurIPS, 2025. [paper](https://openreview.net/forum?id=QPJjiNCRq1), [code](https://github.com/CIAM-Group/TTPL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-10-22

    *Yuanyao Chen, Rongsheng Chen, Fu Luo, Zhenkun Wang*

44. **Refining Hybrid Genetic Search for CVRP via Reinforcement Learning-Finetuned LLM** ICLR, 2026. [paper](https://arxiv.org/abs/2510.11121), [code](https://github.com/zaodushi/RFTHGS) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-06-14

    *Rongjie Zhu, Cong Zhang, Zhiguang Cao*

45. **Rethinking Neural Combinatorial Optimization for Vehicle Routing Problems with Different Constraint Tightness Degrees** NeurIPS, 2025. [paper](https://openreview.net/forum?id=Lwn1rLB8t7), [code](https://github.com/CIAM-Group/Rethinking_Constraint_Tightness) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-10-25

    *Fu Luo, Yaoxin Wu, Zhi Zheng, Zhenkun Wang*

46. **Bridging Synthetic and Real Routing Problems via LLM-Guided Instance Generation and Progressive Adaptation** AAAI, 2026. [paper](https://arxiv.org/abs/2511.10233), [code](https://github.com/HenryZhu1029/EvoReal) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-02-05

    *Jianghan Zhu, Yaoxin Wu, Zhuoyi Lin, Zhengyuan Zhang, Haiyan Yin, Zhiguang Cao, Senthilnath Jayavelu, Xiaoli Li*

47. **Learning to Segment for Vehicle Routing Problems** ICLR, 2026. [paper](https://arxiv.org/abs/2507.01037), [code](https://github.com/mit-wu-lab/learning-to-segment) ⭐ 1 | 🐛 0 | 📅 2026-03-02

    *Wenbin Ouyang, Sirui Li, Yining Ma, Cathy Wu*

48. **Beyond Simple Graphs: Neural Multi-Objective Routing on Multigraphs** ICLR, 2026. [paper](https://arxiv.org/abs/2506.22095), [code](https://github.com/filiprydin/GMS) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-11

    *Filip Rydin, Attila Lischka, Jiaming Wu, Morteza Haghir Chehreghani, Balazs Kulcsar*

49. **Deep Reinforcement Learning for the Electric Vehicle Routing Problem with Time Windows.** Arxiv, 2020. [paper](https://arxiv.org/abs/2010.02068)

    *Bo Lin, Bissan Ghaddar, Jatin Nathwani*

50. **Efficiently Solving the Practical,Vehicle Routing Problem: A Novel Joint Learning Approach.** KDD, 2020. [paper](https://www.kdd.org/kdd2020/accepted-papers/view/efficiently-solving-the-practical-vehicle-routing-problem-a-novel-joint-lea)

    *Lu Duan, Yang Zhan, Haoyuan Hu, Yu Gong, Jiangwen Wei, Xiaodong Zhang, Yinghui Xu*

51. **A Learning-based Iterative Method for Solving Vehicle Routing Problems** ICLR, 2020. [paper](https://static.aminer.cn/upload/pdf/program/5e5e18dd93d709897ce3720b_0.pdf)

    *Hao Lu, Xingwen Zhang, Shuang Yang*

52. **Neural Large Neighborhood Search for the Capacitated Vehicle Routing Problem** Arxiv, 2020. [paper](https://arxiv.org/abs/1911.09539)

    *Andre Hottung, Kevin Tierney*

53. **Learning Improvement Heuristics for Solving Routing Problems** TNNLS, 2021. [journal](https://ieeexplore.ieee.org/abstract/document/9393606?casa_token=mFeyLmrOGfIAAAAA:nmAkjUaTSooYurWHuWGYNoguV453anw9Enyv45xG5jb2oCps6QE4A1CFe1EmFmTzbON6cL5maw)

    *Yaoxin Wu, Wen Song, Zhiguang Cao, Jie Zhang, Andrew Lim*

54. **Reinforcement Learning for Route Optimization with Robustness Guarantees** IJCAI, 2021. [paper](https://www.ijcai.org/proceedings/2021/0357.pdf)

    *Tobias Jacobs, Francesco Alesiani, Gulcin Ermis*

55. **Analytics and Machine Learning in Vehicle Routing Research** Arxiv, 2021. [paper](https://arxiv.org/abs/2102.10012)

    *Ruibin Bai, Xinan Chen, Zhi-Long Chen, Tianxiang Cui, Shuhui Gong, Wentao He, Xiaoping Jiang, Huan Jin, Jiahuan Jin, Graham Kendall, others*

56. **RP-DQN: An application of Q-Learning to Vehicle Routing Problems** Arxiv, 2021. [paper](https://arxiv.org/abs/2104.12226)

    *Ahmad Bdeir, Simon Boeder, Tim Dernedde, Kirill Tkachuk, Jonas K Falkner, Lars Schmidt-Thieme*

57. **Deep Policy Dynamic Programming for Vehicle Routing Problems** Arxiv, 2021. [paper](https://arxiv.org/abs/2102.11756)

    *Wouter Kool, Herke van Hoof, Joaquim Gromicho, Max Welling*

58. **Learning to Delegate for Large-scale Vehicle Routing** NeurIPS, 2021. [paper](https://proceedings.neurips.cc/paper/2021/hash/dc9fa5f217a1e57b8a6adeb065560b38-Abstract.html)

    *Sirui Li, Zhongxia Yan, Cathy Wu*

59. **Learning a Latent Search Space for Routing Problems using Variational Autoencoders** ICLR, 2021. [paper](https://openreview.net/forum?id=90JprVrJBO)

    *Andre Hottung, Bhanu Bhandari, Kevin Tierney*

60. **Preference Conditioned Neural Multi-objective Combinatorial Optimization** ICLR, 2022. [paper](https://openreview.net/forum?id=QuObT9BTWo)

    *Xi Lin, Zhiyuan Yang, Qingfu Zhang*

61. **Learning to CROSS exchange to solve min-max vehicle routing problems** ICLR, 2023. [paper](https://openreview.net/forum?id=ZcnzsHC10Y)

    *Minjun Kim, Junyoung Park, Jinkyoo Park*

62. **Generalize Learned Heuristics to Solve Large-scale Vehicle Routing Problems in Real-time** ICLR, 2023. [paper](https://openreview.net/forum?id=6ZajpxqTlQ)

    *Qingchun Hou, Jingwei Yang, Yiqiang Su, Xiaoqing Wang, Yuming Deng*

63. **Meta-SAGE: Scale Meta-Learning Scheduled Adaptation with Guided Exploration for Mitigating Scale Shift on Combinatorial Optimization** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25138)

    *Jiwoo Son, Minsu Kim, Hyeonah Kim, Jinkyoo Park*

64. **Winner Takes It All: Training Performant RL Populations for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=v6VpqGcGAR)

    *Nathan Grinsztajn, Daniel Furelos-Blanco, Shikha Surana, Cl{'e}ment Bonnet, Thomas D Barrett*

65. **Combinatorial Optimization with Policy Adaptation using Latent Space Search** NeurIPS, 2023. [paper](https://openreview.net/forum?id=vpMBqdt9Hl)

    *Felix Chalumeau, Shikha Surana, Cl{'e}ment Bonnet, Nathan Grinsztajn, Arnu Pretorius, Alexandre Laterre, Thomas D Barrett*

66. **Ensemble-based Deep Reinforcement Learning for Vehicle Routing Problems under Distribution Shift** NeurIPS, 2023. [paper](https://openreview.net/forum?id=HoBbZ1vPAh)

    *Yuan Jiang, Zhiguang Cao, Yaoxin Wu, Wen Song, Jie Zhang*

67. **Learning to Prune Electric Vehicle Routing Problems** LION, 2023. [paper](https://link.springer.com/chapter/10.1007/978-3-031-44505-7_26)

    *James Fitzpatrick, Deepak Ajwani, Paula Carroll*

68. **Neural Combinatorial Optimization for Robust Routing Problem with Uncertain Travel Times** NeurIPS, 2024. [paper](https://openreview.net/pdf?id=DoewNm2uT3)

    *Pei Xiao, Zizhen Zhang, Jinbiao Chen, Jiahai Wang, Zhenzhen Zhang*

69. **A Scalable Learning Approach for the Capacitated Vehicle Routing Problem** Computers and Operations Research, 2024. [journal](https://dx.doi.org/10.1016/j.cor.2024.106787)

    *James Fitzpatrick, Deepak Ajwani, Paula Carroll*

70. **DPN: Decoupling Partition and Navigation for Neural Solvers of Min-max Vehicle Routing Problems** ICML, 2024. [paper](https://openreview.net/forum?id=ar174skI9u)

    *Zhi Zheng, Shunyu Yao, Zhenkun Wang, Xialiang Tong, Mingxuan Yuan, Ke Tang*

71. **Rethinking Neural Multi-Objective Combinatorial Optimization via Neat Weight Embedding** ICLR, 2025. [paper](https://openreview.net/forum?id=GM7cmQfk2F)

    *Jinbiao Chen, Zhiguang Cao, Jiahai Wang, Yaoxin Wu, Hanzhang Qin, Zizhen Zhang, Yue-Jiao Gong*

72. **Boosting Neural Combinatorial Optimization for Large-Scale Vehicle Routing Problems** ICLR, 2025. [paper](https://openreview.net/forum?id=TbTJJNjumY)

    *Fu Luo, Xi Lin, Yaoxin Wu, Zhenkun Wang, Tong Xialiang, Mingxuan Yuan, Qingfu Zhang*

73. **Neural Solver Selection for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=e0OFWfvLCO)

    *Chengrui Gao, Haopu Shang, Ke Xue, Chao Qian*

74. **A Mixed-Curvature based Pre-training Paradigm for Multi-Task Vehicle Routing Solver** ICML, 2025. [paper](https://openreview.net/forum?id=JsPyLqCgks)

    *Suyu Liu, Zhiguang Cao, Shanshan Feng, Yew-Soon Ong*

75. **SHIELD: Multi-task Multi-distribution Vehicle Routing Solver with Sparsity and Hierarchy** ICML, 2025. [paper](https://openreview.net/forum?id=6DJEaz1cCj)

    *Yong Liang Goh, Zhiguang Cao, Yining Ma, Jianan Zhou, Mohammed Haroon Dupty, Wee Sun Lee*

76. **MTL-KD: Multi-Task Learning Via Knowledge Distillation for Generalizable Neural Vehicle Routing Solver** NeurIPS, 2025. [paper](https://openreview.net/forum?id=rlH3e7VlY8)

    *Yuepeng Zheng, Fu Luo, Zhenkun Wang, Yaoxin Wu, Yu Zhou*

77. **DRAGON: LLM-Driven Decomposition and Reconstruction Agents for Large-Scale Combinatorial Optimization** AAMAS, 2026. [paper](https://arxiv.org/abs/2601.06502)

    *Shengkai Chen, Zhiguang Cao, Jianan Zhou, Yaoxin Wu, Senthilnath Jayavelu, Zhuoyi Lin, Xiaoli Li, Shili Xiang*

78. **⭐Native Adaptive Solution Expansion for Diffusion-based Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=084SvT55yk)

    *Yu Wang, Yang Li, Jiale Ma, Junchi Yan, Yi Chang*

### [Maximum Independent Set](#content)

1. **DIFUSCO: Graph-based Diffusion Solvers for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=JV8Ff0lgVV), [code](https://github.com/Edward-Sun/DIFUSCO) ⭐ 265 | 🐛 2 | 🌐 Python | 📅 2024-09-10

   *Zhiqing Sun, Yiming Yang*

2. **Distributed Constrained Combinatorial Optimization leveraging Hypergraph Neural Networks** Nature Machine Intelligence, 2024. [paper](https://arxiv.org/abs/2311.09375), [code](https://github.com/nasheydari/HypOp) ⭐ 93 | 🐛 1 | 🌐 Python | 📅 2024-10-04

   *Nasimeh Heydaribeni, Xinrui Zhan, Ruisi Zhang, Tina Eliassi-Rad, Farinaz Koushanfar*

3. **Large Language Models as End-to-end Combinatorial Optimization Solvers** NeurIPS, 2025. [paper](https://neurips.cc/virtual/2025/loc/san-diego/poster/115835), [code](https://github.com/Summer142857/LLMCoSolver) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2025-10-24

   *Xia Jiang, Yaoxin Wu, Minshuo Li, Zhiguang Cao, Yingqian Zhang*

4. **⭐T2T: From Distribution Learning in Training to Gradient Search in Testing for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=JtF0ugNMv2), [code](https://github.com/Thinklab-SJTU/T2TCO) ⭐ 75 | 🐛 0 | 🌐 Python | 📅 2025-07-02

   *Yang Li, Jinpei Guo, Runzhong Wang, Junchi Yan*

5. **Let the Flows Tell: Solving Graph Combinatorial Optimization Problems with GFlowNets** NeurlPS, 2023. [paper](https://arxiv.org/abs/2305.17010), [code](https://github.com/zdhNarsil/GFlowNet-CombOpt) ⭐ 69 | 🐛 4 | 🌐 Python | 📅 2023-05-30

   *Dinghuai Zhang, Hanjun Dai, Nikolay Malkin, Aaron Courville, Yoshua Bengio, Ling Pan*

6. **A Diffusion Model Framework for Unsupervised Neural Combinatorial Optimization** ICML, 2024. [paper](https://arxiv.org/abs/2406.01661), [code](https://github.com/ml-jku/DIffUCO) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2025-10-09

   *Sebastian Sanokowski, Sepp Hochreiter, Sebastian Lehner*

7. **DISCS: A Benchmark for Discrete Sampling** NeurlPS, 2023. [paper](https://openreview.net/forum?id=oi1MUMk5NF), [code](https://github.com/google-research/discs) ⚠️ Archived

   *Katayoon Goshvadi, Haoran Sun, Xingchao Liu, Azade Nova, Ruqi Zhang, Will Sussman Grathwohl, Dale Schuurmans, Hanjun Dai*

8. **What's Wrong with Deep Learning in Tree Search for Combinatorial Optimization** ICLR, 2022. [paper](https://openreview.net/forum?id=mk0HzdqY7i1), [code](https://github.com/MaxiBoether/mis-benchmark-framework) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2024-02-03

   *Maximilian Bother, Otto Kissig, Martin Taraz, Sarel Cohen, Karen Seidel, Tobias Friedrich*

9. **⭐ML4CO-Bench-101: Benchmark Machine Learning for Classic Combinatorial Problems on Graphs** NeurIPS, 2025. [paper](https://openreview.net/forum?id=ye4ntB1Kzi), [code](https://github.com/Thinklab-SJTU/ML4CO-Bench-101) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2025-11-17

   *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

10. **⭐COExpander: Adaptive Solution Expansion for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=KMaBXMWsBM), [code](https://github.com/Thinklab-SJTU/COExpander) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2025-06-28

    *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

11. **Optimization by Parallel Quasi-Quantum Annealing with Gradient-Based Sampling** ICLR, 2025. [paper](https://openreview.net/forum?id=9EfBeXaXf0), [code](https://github.com/Yuma-Ichikawa/QQA4CO) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-08-29

    *Yuma Ichikawa, Yamato Arai*

12. **Continuous Parallel Relaxation for Finding Diverse Solutions in Combinatorial Optimization Problems** TMLR, 2025. [journal](https://openreview.net/forum?id=ix33zd5zCw), [code](https://github.com/Yuma-Ichikawa/QQA4CO) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-08-29

    *Yuma Ichikawa, Hiroaki Iwashita*

13. **⭐Fast T2T: Optimization Consistency Speeds Up Diffusion-Based Training-to-Testing Solving for Combinatorial Optimization** NeurIPS, 2024. [paper](https://openreview.net/pdf?id=xDrKZOZEOc), [code](https://github.com/Thinklab-SJTU/Fast-T2T) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2025-07-02

    *Yang Li, Jinpei Guo, Runzhong Wang, Hongyuan Zha, Junchi Yan*

14. **⭐ROCO: A General Framework for Evaluating Robustness of Combinatorial Optimization Solvers on Graphs** ICLR, 2023. [paper](https://openreview.net/forum?id=2r6YMqz4Mml), [code](https://github.com/Thinklab-SJTU/ROCO) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2024-10-23

    *Han Lu, Zenan Li, Runzhong Wang, Qibing Ren, Xijun Li, Mingxuan Yuan, Jia Zeng, Xiaokang Yang, Junchi Yan*

15. **FrontierCO: Real-World and Large-Scale Evaluation of Machine Learning Solvers for Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=BVprkacwFY), [code](https://github.com/sunnweiwei/FrontierCO) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2026-05-17

    *Shengyu Feng, Weiwei Sun, Shanda Li, Ameet Talwalkar, Yiming Yang*

16. **Variational Annealing on Graphs for Combinatorial Optimization** NeurlPS, 2023. [paper](https://openreview.net/forum?id=SLx7paoaTU), [code](https://github.com/ml-jku/VAG-CO) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-11-22

    *Sebastian Sanokowski, Wilhelm Franz Berghammer, Sepp Hochreiter, Sebastian Lehner*

17. **⭐Generation as search operator for test-time scaling of diffusion-based combinatorial optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=9JM03CQwzC), [code](https://github.com/Thinklab-SJTU/GenSCO) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-07-11

    *Yang Li, Lvda Chen, Haonan Wang, Runzhong Wang, Junchi Yan*

18. **Unsupervised Learning for Combinatorial Optimization Needs Meta Learning** ICLR, 2023. [paper](https://openreview.net/forum?id=-ENYHCE8zBp), [code](https://github.com/Graph-COM/Meta_CO) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-02-23

    *Haoyu Wang, Pan Li*

19. **MARCO: A Memory-Augmented Reinforcement Framework for Combinatorial Optimization** IJCAI, 2024. [paper](https://www.ijcai.org/proceedings/2024/0766.pdf), [code](https://github.com/TheLeprechaun25/MARCO) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-10-08

    *Andoni I. Garmendia, Quentin Cappart, Josu Ceberio, Alexander Mendiburu*

20. **Regularized Langevin Dynamics for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=bbJ0QCujU4), [code](https://github.com/Shengyu-Feng/RLD4CO) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-06-15

    *Shengyu Feng, Yiming Yang*

21. **Maximum Independent Set: Self-Training through Dynamic Programming** NeurlPS, 2023. [paper](https://openreview.net/forum?id=igE3Zbxvws), [code](https://github.com/LIONS-EPFL/dynamic-MIS) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-08-28

    *Lorenzo Brusca, Lars CPM Quaedvlieg, Stratis Skoulakis, Grigorios G Chrysos, Volkan Cevher*

22. **⭐MaskCO: Masked Generation Drives Effective Representation Learning and Exploiting for Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=psUjNnLhl9), [code](https://github.com/Thinklab-SJTU/MaskCO) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-07-11

    *Lvda Chen, Yang Li, Junchi Yan*

23. **Graph-based Deterministic Policy Gradient for Repetitive Combinatorial Optimization Problems** ICLR, 2023. [paper](https://openreview.net/forum?id=yHIIM9BgOo), [code](https://github.com/XzrTGMu/twin-nphard) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-03-08

    *Zhongyuan Zhao, Ananthram Swami, Santiago Segarra*

24. **⭐ConRep4CO: Contrastive Representation Learning of Combinatorial Optimization Instances across Types** ICLR, 2026. [paper](https://openreview.net/forum?id=OXRnvOOiAf), [code](https://github.com/Thinklab-SJTU/ConRep4CO) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-03-09

    *Ziao Guo, Yang Li, Shiyue Wang, Junchi Yan*

25. **⭐StruDiCO: Structured Denoising Diffusion with Gradient-free Inference-stage Boosting for Memory and Time Efficient Combinatorial Optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=P69X3V4WwH), [code](https://github.com/yuuuuwang/StruDiCO) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-11-20

    *Yu Wang, Yang Li, Junchi Yan, Yi Chang*

26. **Learning to Explore and Exploit with GNNs for Unsupervised Combinatorial Optimization** ICLR, 2025. [paper](https://openreview.net/forum?id=vaJ4FObpXN), [code](https://github.com/utkuumur/X2GNN) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2025-02-28

    *Utku Umur Acikalin, Aaron M. Ferber, Carla P. Gomes*

27. **Combinatorial Optimization with Graph Convolutional Networks and Guided Tree Search.** NeurIPS, 2018. [paper](https://arxiv.org/abs/1810.10659)

    *Zhuwen Li, Qifeng Chen, Vladlen Koltun*

28. **Learning What to Defer for Maximum Independent Sets** ICML, 2020. [paper](http://proceedings.mlr.press/v119/ahn20a.html)

    *Sungsoo Ahn, Younggyo Seo, Jinwoo Shin*

29. **Distributed Scheduling Using Graph Neural Networks** ICASSP, 2021. [paper](https://ieeexplore.ieee.org/abstract/document/9414098?casa_token=Q4coRBbINPMAAAAA:0T8L49Kyn9p4CoM20-FqINKCyk_Sm3ye5TemPT8GlG3C3wXXLvn1RGKeHgriiyZIcg_GFB4z1A)

    *Zhongyuan Zhao, Gunjan Verma, Chirag Rao, Ananthram Swami, Santiago Segarra*

30. **Solving Graph-based Public Good Games with Tree Search and Imitation Learning** NeurlPS, 2021. [paper](https://arxiv.org/abs/2106.06762)

    *Victor-Alexandru Darvariu, Stephen Hailes, Mirco Musolesi*

31. **NN-Baker: A Neural-network Infused Algorithmic Framework for Optimization Problems on Geometric Intersection Graphs** NeurlPS, 2021. [paper](https://papers.nips.cc/paper/2021/file/c236337b043acf93c7df397fdb9082b3-Paper.pdf)

    *Evan McCarty, Qi Zhao, Anastasios Sidiropoulos, Yusu Wang*

32. **Optimistic tree search strategies for black-box combinatorial optimization** NeurlPS, 2022. [paper](https://openreview.net/forum?id=JGLW4DvX11F)

    *Cedric Malherbe, Antoine Grosnit, Rasul Tutunov, Haitham Bou Ammar, Jun Wang*

33. **Revisiting Sampling for Combinatorial Optimization** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/23661)

    *Haoran, Goshvadi Katayoon, Nova Azade, Schuurmans Dale Sun, Dai Hanjun.*

34. **Controlling Continuous Relaxation for Combinatorial Optimization** NeurlPS, 2024. [paper](https://openreview.net/pdf?id=ykACV1IhjD)

    *Yuma Ichikawa*

35. **Efficient Combinatorial Optimization via Heat Diffusion** NeurlPS, 2024. [paper](https://openreview.net/pdf?id=psDrko9v1D)

    *Hengyuan Ma, Wenlian Lu, Jianfeng Feng*

36. **Scalable Discrete Diffusion Samplers: Combinatorial Optimization and Statistical Physics** ICLR, 2025. [paper](https://openreview.net/pdf?id=peNgxpbdxB)

    *Sebastian Sanokowski, Wilhelm Franz Berghammer, Haoyu Peter Wang, Martin Ennemoser, Sepp Hochreiter, Sebastian Lehner*

37. **Geometric Algorithms for Neural Combinatorial Optimization with Constraints** NeurIPS, 2025. [paper](https://openreview.net/forum?id=EPDLFWyNnF)

    *Nikolaos Karalias, Akbar Rafiey, Yifei Xu, Zhishang Luo, Behrooz Tahmasebi, Connie Jiang, Stefanie Jegelka*

38. **⭐Native Adaptive Solution Expansion for Diffusion-based Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=084SvT55yk)

    *Yu Wang, Yang Li, Jiale Ma, Junchi Yan, Yi Chang*

### [Generalization](#content)

1. **Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model** ICML, 2024. [paper](https://openreview.net/forum?id=BwAkaxqiLB), [code](https://github.com/FeiLiu36/EoH) ⭐ 356 | 🐛 6 | 🌐 Python | 📅 2026-08-06

   *Fei Liu, Xialiang Tong, Mingxuan Yuan, Xi Lin, Fu Luo, Zhenkun Wang, Zhichao Lu, Qingfu Zhang*

2. **ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution** NeurIPS, 2024. [paper](https://openreview.net/forum?id=483IPG0HWL), [code](https://github.com/ai4co/reevo) ⭐ 294 | 🐛 0 | 🌐 Python | 📅 2026-01-24

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Federico Berto, Chuanbo Hua, Haeyeon Kim, Jinkyoo Park, Guojie Song*

3. **Learning TSP Requires Rethinking Generalization** CP, 2021. [paper](https://arxiv.org/pdf/2006.07054.pdf), [code](https://github.com/chaitjo/learning-tsp) ⚠️ Archived

   *Chaitanya K. Joshi, Quentin Cappart, Louis-Martin Rousseau, Thomas Laurent*

4. **Towards Omni-generalizable Neural Methods for Vehicle Routing Problems** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25267), [code](https://github.com/RoyalSkye/Omni-VRP) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2025-06-03

   *Zhou Jianan, Yaoxin Wu, Wen Song, Zhiguang Cao, Jie Zhang*

5. **⭐ROCO: A General Framework for Evaluating Robustness of Combinatorial Optimization Solvers on Graphs** ICLR, 2023. [paper](https://openreview.net/forum?id=2r6YMqz4Mml), [code](https://github.com/Thinklab-SJTU/ROCO) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2024-10-23

   *Han Lu, Zenan Li, Runzhong Wang, Qibing Ren, Xijun Li, Mingxuan Yuan, Jia Zeng, Xiaokang Yang, Junchi Yan*

6. **Projecting Latent RL Actions: Towards Generalizable and Scalable Graph Combinatorial Optimization** Arxiv, 2026. [paper](https://arxiv.org/abs/2605.19721), [code](https://github.com/terranovafr/LaGCO-RL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-07-31

   *Franco Terranova, Guillermo Bernardez, Albert Cabellos-Aparicio, Nina Miolane, Abdelkader Lahmadi*

7. **It's Not What Machines Can Learn It's What We Cannot Teach** ICML, 2020. [paper](http://proceedings.mlr.press/v119/yehuda20a/yehuda20a.pdf)

   *Gal Yehuda, Moshe Gabel, Assaf Schuster*

8. **Generalization of Neural Combinatorial Solvers Through the Lens of Adversarial Robustness** ICLR, 2022. [paper](https://openreview.net/forum?id=vJZ7dPIjip3)

   *Simon Geisler, Johanna Sommer, Jan Schuchardt, Aleksandar Bojchevski, Stephan Günnemann*

9. **Learning for Robust Combinatorial Optimization: Algorithm and Application** INFOCOM, 2022. [journal](https://ieeexplore.ieee.org/abstract/document/9796715/)

   *Zhihui Shao, Jianyi Yang, Cong Shen, Shaolei Ren*

10. **GOAL: A Generalist Combinatorial Optimization Agent Learner** ICLR, 2025. [paper](https://openreview.net/forum?id=z2z9suDRjw)

    *Darko Drakulic, Sofia Michel, Jean-Marc Andreoli*

11. **OPTFM: A Scalable Multi-View Graph Transformer for Hierarchical Pre-Training in Combinatorial Optimization** NeurIPS, 2025. [paper](https://openreview.net/forum?id=24tuzE5KZc)

    *Hao Yuan, Wenli Ouyang, Changwen Zhang, Congrui Li, Yong Sun*

### [Orienteering Problem](#content)

1. **DeepACO: Neural-enhanced Ant Systems for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=cd5D1DD923), [code](https://github.com/henry-yeh/DeepACO) ⭐ 197 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-29

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Helan Liang, Yong Li*

2. **UDC: A Unified Neural Divide-and-Conquer Framework for Large-Scale Combinatorial Optimization Problems** NeurIPS, 2024. [paper](https://openreview.net/pdf?id=dCgbyvmlwL), [code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/UDC-Large-scale-CO-master) ⭐ 101 | 🐛 0 | 🌐 Python | 📅 2025-05-28

   *Zhi Zheng, Changliang Zhou, Tong Xialiang, Mingxuan Yuan, Zhenkun Wang*

3. **A reinforcement learning approach to the orienteering problem with time windows** Computers & Operations Research, 2021. [paper](https://arxiv.org/abs/2011.03647v2), [code](https://github.com/mustelideos/optw_rl) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2021-12-05

   *Ricardo Gama, Hugo L. Fernandes*

4. **Meta-SAGE: Scale Meta-Learning Scheduled Adaptation with Guided Exploration for Mitigating Scale Shift on Combinatorial Optimization** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25138)

   *Jiwoo Son, Minsu Kim, Hyeonah Kim, Jinkyoo Park*

### [Knapsack](#content)

1. **DeepACO: Neural-enhanced Ant Systems for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=cd5D1DD923), [code](https://github.com/henry-yeh/DeepACO) ⭐ 197 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-29

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Helan Liang, Yong Li*

2. **BQ-NCO: Bisimulation Quotienting for Efficient Neural Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=BRqlkTDvvm), [code](https://github.com/naver/bq-nco) ⭐ 45 | 🐛 3 | 🌐 Python | 📅 2023-11-17

   *Darko Drakulic, Sofia Michel, Florian Mai, Arnaud Sors, Jean-Marc Andreoli*

3. **Efficient Meta Neural Heuristic for Multi-Objective Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=593fc38lhN), [code](https://github.com/bill-cjb/EMNH) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2023-10-25

   *Jinbiao Chen, Jiahai Wang, Zizhen Zhang, Zhiguang Cao, Te Ye, Siyuan Chen*

4. **Neural Multi-Objective Combinatorial Optimization with Diversity Enhancement** NeurIPS, 2023. [paper](https://openreview.net/forum?id=N4JkStI1fe), [code](https://github.com/bill-cjb/NHDE) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2023-10-25

   *Jinbiao Chen, Zizhen Zhang, Zhiguang Cao, Yaoxin Wu, Yining Ma, Te Ye, Jiahai Wang*

5. **A Pointer Network Based Deep Learning Algorithm  for 0-1 Knapsack Problem** ICACI, 2018. [paper](https://ieeexplore.ieee.org/abstract/document/8377505)

   *Shenshen Gu, Hao Tao*

6. **An Investigation into Prediction + Optimisation for the Knapsack Problem** CPAIOR, 2019. [paper](https://link.springer.com/chapter/10.1007/978-3-030-19212-9_16)

   *Emir Demirovic, Peter J. Stuckey, James Bailey, Jeffrey Chan, Chris Leckie, Kotagiri Ramamohanarao, Tias Guns*

7. **A Novel Method to Solve Neural Knapsack Problems** ICML, 2021. [paper](http://proceedings.mlr.press/v139/li21m.html)

   *Duanshun Li, Jing Liu, Dongeun Lee, Ali Seyedmazloom, Giridhar Kaushik, Kookjin Lee, Noseong Park*

8. **Provably Good Solutions to the Knapsack Problem via Neural Networks of Bounded Size** AAAI, 2021. [paper](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.2021.0225)

   *Christoph Hertrich, Martin Skutella*

9. **Winner Takes It All: Training Performant RL Populations for Combinatorial Optimization** NeurIPS, 2023. [paper](https://openreview.net/forum?id=v6VpqGcGAR)

   *Nathan Grinsztajn, Daniel Furelos-Blanco, Shikha Surana, Cl{'e}ment Bonnet, Thomas D Barrett*

10. **Rethinking Neural Multi-Objective Combinatorial Optimization via Neat Weight Embedding** ICLR, 2025. [paper](https://openreview.net/forum?id=GM7cmQfk2F)

    *Jinbiao Chen, Zhiguang Cao, Jiahai Wang, Yaoxin Wu, Hanzhang Qin, Zizhen Zhang, Yue-Jiao Gong*

11. **Approximation algorithms for combinatorial optimization with predictions** ICLR, 2025. [paper](https://openreview.net/forum?id=AEFVa6VMu1)

    *Antonios Antoniadis, Marek Elias, Adam Polak, Moritz Venzin*

### [Boolean Satisfiability](#content)

1. **Learning a SAT solver from single-bit supervision.** Arxiv, 2018. [paper](https://arxiv.org/pdf/1903.04671), [code](https://github.com/dselsam/neurosat) ⭐ 296 | 🐛 0 | 🌐 Python | 📅 2019-03-12

   *Daniel Selsam, Benedikt Bünz Matthew Lamm, Leonardo de Moura Percy Liang, David L. Dill.*

2. **Distributed Constrained Combinatorial Optimization leveraging Hypergraph Neural Networks** Nature Machine Intelligence, 2024. [paper](https://arxiv.org/abs/2311.09375), [code](https://github.com/nasheydari/HypOp) ⭐ 93 | 🐛 1 | 🌐 Python | 📅 2024-10-04

   *Nasimeh Heydaribeni, Xinrui Zhan, Ruisi Zhang, Tina Eliassi-Rad, Farinaz Koushanfar*

3. **Let the Flows Tell: Solving Graph Combinatorial Optimization Problems with GFlowNets** NeurlPS, 2023. [paper](https://arxiv.org/abs/2305.17010), [code](https://github.com/zdhNarsil/GFlowNet-CombOpt) ⭐ 69 | 🐛 4 | 🌐 Python | 📅 2023-05-30

   *Dinghuai Zhang, Hanjun Dai, Nikolay Malkin, Aaron Courville, Yoshua Bengio, Ling Pan*

4. **G2SAT: Learning to Generate SAT Formulas.** NeurIPS, 2019. [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7138247/), [code](https://github.com/JiaxuanYou/G2SAT) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2020-06-25

   *Jiaxuan, Haoze Wu, Clark Barrett, Raghuram Ramanujan You, Jure Leskovec.*

5. **Learning Local Search Heuristics for Boolean Satisfiability.** NeurIPS, 2019. [paper](https://www.cs.cmu.edu/~eyolcu/papers/learning-local-search-heuristics-sat.pdf), [code](https://github.com/emreyolcu/sat) ⭐ 38 | 🐛 2 | 🌐 Python | 📅 2024-05-08

   *Emre Yolcu, Barnabas Poczos*

6. **⭐HardSATGEN: Understanding the Difficulty of Hard SAT Formula Generation and A Strong Structure-Hardness-Aware Baseline** KDD, 2023. [paper](https://dl.acm.org/doi/10.1145/3580305.3599837), [code](https://github.com/Thinklab-SJTU/HardSATGEN) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2023-06-16

   *Yang Li, Xinyan Chen, Wenxuan Guo, Xijun Li, Wanqian Luo, Junhua Huang, Hui-Ling Zhen, Mingxuan Yuan, Junchi Yan*

7. **NLocalSAT: Boosting Local Search with Solution Prediction.** Arxiv, 2020. [paper](https://arxiv.org/pdf/2001.09398), [code](https://github.com/myxxxsquared/NLocalSAT) ⭐ 18 | 🐛 2 | 🌐 C++ | 📅 2023-08-04

   *Wenjie, Zeyu Sun, Qihao Zhu, Ge Li, Shaowei Cai, Yingfei Xiong Zhang, Lu Zhang.*

8. **⭐UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP** ICLR, 2025. [paper](https://openreview.net/forum?id=yEwakMNIex), [code](https://github.com/Thinklab-SJTU/UniCO) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-06-20

   *Wenzheng Pan, Hao Xiong, Jiale Ma, Wentao Zhao, Yang Li, Junchi Yan*

9. **Learning to solve circuit-SAT: An unsupervised differentiable approach.** ICLR, 2019. [paper](https://openreview.net/pdf?id=BJxgz2R9t7), [code](https://github.com/johannaSommer/generalization-neural-co-solvers) ⭐ 13 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-11-20

   *Saeed, Sergiy Matusevych Amizadeh, Markus Weimer.*

10. **Efficient Combinatorial Optimization via Heat Diffusion** NeurIPS, 2024. [paper](https://openreview.net/forum?id=psDrko9v1D), [code](https://github.com/AwakerMhy/HeO) ⭐ 8 | 🐛 1 | 🌐 Roff | 📅 2025-03-20

    *Hengyuan Ma, Wenlian Lu, Jianfeng Feng*

11. **Augment with Care: Contrastive Learning for Combinatorial Problems.** ICML, 2022. [paper](https://proceedings.mlr.press/v162/duan22b.html), [code](https://github.com/h4duan/contrastive-sat) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2024-05-09

    *Haonan, Pashootan Vaezipoor, Max B. Paulus, Yangjun Ruan Duan, Chris J. Maddison*

12. **Online Bayesian Moment Matching based SAT Solver Heuristics.** ICML, 2020. [paper](http://proceedings.mlr.press/v119/duan20c/duan20c.pdf), [code](https://github.com/saeednj/BMMSAT) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2021-01-04

    *Haonan, Saeed Nejati, George Trimponias, Pascal Poupart Duan, Vijay Ganesh.*

13. **Learning Heuristics for Quantified Boolean Formulas through Reinforcement Learning.** Arxiv, 2019. [paper](https://arxiv.org/pdf/1807.08058), [code](https://github.com/lederg/learningqbf) ⭐ 0 | 🐛 1 | 📅 2020-02-15

    *Gil Lederman, Edward A. Lee Markus N. Rabe, Sanjit A. Seshia.*

14. **Graph neural networks and boolean satisfiability.** Arxiv, 2017. [paper](https://arxiv.org/pdf/1702.03592)

    *Benedikt Bünz, Matthew Lamm.*

15. **Machine learning-based restart policy for CDCL SAT solvers.** SAT, 2018. [paper](http://www.t-news.cn/Floc2018/FLoC2018-pages/proceedings_paper_477.pdf)

    *Jia Hui Liang, Minu Mathew Chanseok Oh, Chunxiao Li Ciza Thomas, Vijay Ganesh.*

16. **Improving SAT solver heuristics with graph networks and reinforcement learning.** Arxiv, 2019. [paper](https://arxiv.org/pdf/1909.11830)

    *Vitaly Kurin, Shimon Whiteson Saad Godil, Bryan Catanzaro.*

17. **Graph neural reasoning may fail in certifying boolean unsatisfiability.** Arxiv, 2019. [paper](https://arxiv.org/pdf/1909.11588)

    *Ziliang Chen, Zhanfu Yang.*

18. **Guiding high-performance SAT solvers with unsat-core predictions.** SAT, 2019. [paper](https://arxiv.org/pdf/1903.04671)

    *Daniel Selsam, Nikolaj Bjørner.*

19. **Enhancing SAT solvers with glue variable predictions.** Arxiv, 2020. [paper](https://arxiv.org/pdf/2007.02559)

    *Jesse Michael. Han*

20. **Can Q-Learning with Graph Networks Learn a Generalizable Branching Heuristic for a SAT Solver?** NeurIPS, 2020. [paper](http://www.cs.ox.ac.uk/people/shimon.whiteson/pubs/kurinnips20.pdf)

    *Shimon Whiteson*

21. **Learning Clause Deletion Heuristics with Reinforcement Learning.** AITP, 2020. [paper](http://aitp-conference.org/2020/abstract/paper_25.pdf)

    *Pashootan, Gil Lederman, Yuhuai Wu, Roger Grosse Vaezipoor, Fahiem Bacchus.*

22. **Classification of SAT problem instances by machine learning methods.** CEUR, 2020. [paper](http://ceur-ws.org/Vol-2650/paper11.pdf)

    *Márk, Zijian Győző Yang Danisovszky, Gábor Kusper.*

23. **Predicting Propositional Satisfiability via End-to-End Learning.** AAAI, 2020. [paper](https://ojs.aaai.org/index.php/AAAI/article/download/5733/5589)

    *Chris Cameron, Jason Hartford Rex Chen, Kevin Leyton-Brown.*

24. **Neural heuristics for SAT solving.** Arxiv, 2020. [paper](https://arxiv.org/pdf/2005.13406)

    *Sebastian, Michał Łuszczyk Jaszczur, Henryk Michalewski.*

25. **Optimistic tree search strategies for black-box combinatorial optimization** NeurlPS, 2022. [paper](https://openreview.net/forum?id=JGLW4DvX11F)

    *Cedric Malherbe, Antoine Grosnit, Rasul Tutunov, Haitham Bou Ammar, Jun Wang*

26. **Goal-Aware Neural SAT Solver.** IJCNN, 2022. [paper](https://ieeexplore.ieee.org/document/9892733)

    *Emils Ozolins, Andis Draguns Karlis Freivalds, Ronalds Zakovskis Eliza Gaile, Sergejs Kozlovics.*

27. **NeuroComb: Improving SAT Solving with Graph Neural Networks.** Arxiv, 2022. [paper](https://arxiv.org/abs/2110.14053)

    *Wenxi Wang, Mohit Tiwari Yang Hu, Kenneth McMillan Sarfraz Khurshid, Risto Miikkulainen.*

28. **On the Performance of Deep Generative Models of Realistic SAT Instances.** SAT, 2022. [paper](https://drops.dagstuhl.de/opus/volltexte/2022/16677/pdf/LIPIcs-SAT-2022-3.pdf)

    *Iván, Pablo Mesejo Garzón, Jesús Giráldez-Cru.*

29. **DeepSAT: An EDA-Driven Learning Framework for SAT.** Arxiv, 2022. [paper](http://arxiv.org/abs/2205.13745)

    *Min, Zhengyuan Shi, Qiuxia Lai, Sadaf Khan Li, Qiang Xu.*

30. **SATformer: Transformers for SAT Solving.** Arxiv, 2022. [paper](https://arxiv.org/abs/2209.00953)

    *Zhengyuan Shi, Sadaf Khan Min Li, Mingxuan Yuan Hui-Ling Zhen, Qiang Xu.*

31. **NSNet: A General Neural Probabilistic Framework for Satisfiability Problems** NeurIPS, 2022. [paper](https://arxiv.org/abs/2211.03880)

    *Zhaoyu Li, Xujie Si*

32. **Neural Set Function Extensions: Learning with Discrete Functions in High Dimensions** NeurIPS, 2022. [paper](https://arxiv.org/abs/2208.04055)

    *Nikolaos Karalias, Joshua Robinson, Andreas Loukas, Stefanie Jegelka*

33. **Generalization of Neural Combinatorial Solvers Through the Lens of Adversarial Robustness** ICLR, 2022. [paper](https://openreview.net/forum?id=vJZ7dPIjip3)

    *Simon Geisler, Johanna Sommer, Jan Schuchardt, Aleksandar Bojchevski, Stephan Günnemann*

34. **Efficient Combinatorial Optimization via Heat Diffusion** NeurlPS, 2024. [paper](https://openreview.net/pdf?id=psDrko9v1D)

    *Hengyuan Ma, Wenlian Lu, Jianfeng Feng*

### [Computing Resource Allocation](#content)

1. **Learning Scheduling Algorithms for Data Processing Clusters** SIGCOMM, 2019. [paper](https://static.aminer.cn/storage/pdf/arxiv/18/1810/1810.01963.pdf), [code](https://github.com/hongzimao/decima-sim) ⭐ 328 | 🐛 29 | 🌐 Python | 📅 2021-06-15

   *Hongzi Mao, Malte Schwarzkopf, Bojja Shaileshh Venkatakrishnan, Zili Meng, Mohammad Alizadeh*

2. **Learning to Perform Local Rewriting for Combinatorial Optimization.** NeurIPS, 2019. [paper](https://arxiv.org/abs/1810.00337), [code](https://github.com/facebookresearch/neural-rewriter) ⚠️ Archived

   *Xinyun Chen, Yuandong Tian*

3. **⭐A Bi-Level Framework for Learning to Solve Combinatorial Optimization on Graphs** NeurIPS, 2021. [paper](https://arxiv.org/abs/2106.04927), [code](https://github.com/Thinklab-SJTU/PPO-BiHyb) ⭐ 106 | 🐛 0 | 🌐 Python | 📅 2023-04-19

   *Runzhong Wang, Zhigang Hua, Gan Liu, Jiayi Zhang, Junchi Yan, Feng Qi, Shuang Yang, Jun Zhou, Xiaokang Yang*

4. **Projecting Latent RL Actions: Towards Generalizable and Scalable Graph Combinatorial Optimization** Arxiv, 2026. [paper](https://arxiv.org/abs/2605.19721), [code](https://github.com/terranovafr/LaGCO-RL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-07-31

   *Franco Terranova, Guillermo Bernardez, Albert Cabellos-Aparicio, Nina Miolane, Abdelkader Lahmadi*

5. **Resource Management with Deep Reinforcement Learning.** HotNets, 2016. [paper](https://dl.acm.org/doi/abs/10.1145/3005745.3005750)

   *Hongzi Mao, Mohammad Alizadeh, Ishai Menache, Srikanth Kandula*

6. **Smart Resource Allocation for Mobile Edge Computing: A Deep Reinforcement Learning Approach** IEEE Transactions on Emerging Topics in Computing, 2019. [Paper](https://ieeexplore.ieee.org/abstract/document/8657791)

   *Lei Zhao Jiadai, Nei Kato Jiajia Liu*

7. **A Two-stage Framework and Reinforcement Learning-based Optimization Algorithms for Complex Scheduling Problems** Arxiv, 2021. [paper](https://arxiv.org/abs/2103.05847)

   *Yongming He, Guohua Wu, Yingwu Chen, Witold Pedrycz*

### [Bin Packing Problem](#content)

1. **Online 3D Bin Packing with Constrained Deep Reinforcement Learning.** AAAI, 2021. [paper](https://arxiv.org/abs/2006.14978), [code](https://github.com/alexfrom0815/Online-3D-BPP-DRL) ⭐ 607 | 🐛 2 | 🌐 Python | 📅 2023-11-17

   *Hang Zhao, Qijin She, Chenyang Zhu, Yin Yang, Kai Xu*

2. **Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model** ICML, 2024. [paper](https://openreview.net/forum?id=BwAkaxqiLB), [code](https://github.com/FeiLiu36/EoH) ⭐ 356 | 🐛 6 | 🌐 Python | 📅 2026-08-06

   *Fei Liu, Xialiang Tong, Mingxuan Yuan, Xi Lin, Fu Luo, Zhenkun Wang, Zhichao Lu, Qingfu Zhang*

3. **ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution** NeurIPS, 2024. [paper](https://openreview.net/forum?id=483IPG0HWL), [code](https://github.com/ai4co/reevo) ⭐ 294 | 🐛 0 | 🌐 Python | 📅 2026-01-24

   *Haoran Ye, Jiarui Wang, Zhiguang Cao, Federico Berto, Chuanbo Hua, Haeyeon Kim, Jinkyoo Park, Guojie Song*

4. **TAP-Net: Transport-and-Pack using Reinforcement Learning.** TOG, 2020. [paper](https://dl.acm.org/doi/abs/10.1145/3414685.3417796), [code](https://github.com/Juzhan/TAP-Net) ⭐ 62 | 🐛 0 | 🌐 Python | 📅 2020-09-03

   *Ruizhen Hu, Juzhan Xu, Bin Chen, Minglun Gong, Hao Zhang, Hui Huang*

5. **PackIt: A Virtual Environment for Geometric Planning** ICML, 2020. [paper](http://proceedings.mlr.press/v119/goyal20b.html), [code](https://github.com/princeton-vl/PackIt) ⭐ 54 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2024-12-12

   *Ankit Goyal, Jia Deng*

6. **EoH-S: Evolution of Heuristic Set using LLMs for Automated Heuristic Design** AAAI, 2026. [paper](https://arxiv.org/abs/2508.03082), [code](https://github.com/FeiLiu36/EoH-S) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-05-20

   *Fei Liu, Yilu Liu, Qingfu Zhang, Xialiang Tong, Mingxuan Yuan*

7. **Generalizable Heuristic Generation Through LLMs with Meta-Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2505.20881), [code](https://github.com/yiding-s/MoH) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2026-08-23

   *Yiding Shi, Jianan Zhou, Wen Song, Jieyi Bi, Yaoxin Wu, Zhiguang Cao, Jie Zhang*

8. **A Neural Column Generation Approach to the Vehicle Routing Problem with Two-Dimensional Loading and Last-In-First-Out Constraints** IJCAI, 2024. [paper](https://www.ijcai.org/proceedings/2024/0218.pdf), [code](https://github.com/xyfffff/NCG-for-2L-CVRP) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2024-08-10

   *Yifan Xia, Xiangyi Zhang*

9. **Small Boxes Big Data: A Deep Learning Approach to Optimize Variable Sized Bin Packing** BigDataService, 2017. [paper](https://ieeexplore.ieee.org/abstract/document/7944923/?casa_token=mRzI_XBy3ycAAAAA:yD9Le2KBNq1TMpW_1etb0RF-oFVcLJj9Up0Z2qI6XJmA-UffxxSZRIx7RklaQED-yXwuwBC4M_w)

   *Feng Mao, Edgar Blanco, Mingang Fu, Rohit Jain, Anurag Gupta, Sebastien Mancel, Rong Yuan, Stephen Guo, Sai Kumar, Yayang Tian*

10. **Solving a New 3D Bin Packing Problem with Deep Reinforcement Learning Method** Arxiv, 2017. [paper](https://arxiv.org/abs/1708.05930)

    *Haoyuan Hu, Xiaodong Zhang, Xiaowei Yan, Longfei Wang, Yinghui Xu*

11. **Best Arm Identification in Multi-armed Bandits with Delayed Feedback** PMLR, 2018. [paper](http://proceedings.mlr.press/v84/grover18b.html)

    *Aditya Grover, Todor Markov, Peter Attia, Norman Jin, Nicolas Perkins, Bryan Cheong, Michael Chen, Zi Yang, Stephen Harris, William Chueh, others*

12. **Ranked Reward: Enabling Self-Play Reinforcement Learning for Combinatorial Optimization Alexandre** Arxiv, 2018. [paper](https://arxiv.org/abs/1807.01672)

    *Alexandre Laterre, Yunguan Fu, Mohamed Khalil Jabri, Alain-Sam Cohen, David Kas, Karl Hajjar, Torbjorn S Dahl, Amine Kerkeni, Karim Beguir*

13. **A Multi-task Selected Learning Approach for Solving 3D Bin Packing Problem.** AAMAS, 2019. [paper](https://arxiv.org/abs/1804.06896)

    *Lu Duan, Haoyuan Hu, Yu Qian, Yu Gong, Xiaodong Zhang, Yinghui Xu, Jiangwen Wei*

14. **A Data-Driven Approach for Multi-level Packing Problems in Manufacturing Industry** KDD, 2019. [paper](https://dl.acm.org/doi/abs/10.1145/3292500.3330708)

    *Lei Chen, Xialiang Tong, Mingxuan Yuan, Jia Zeng, Lei Chen*

15. **Solving Packing Problems by Conditional Query Learning** OpenReview, 2019. [paper](https://openreview.net/forum?id=BkgTwRNtPB)

    *Dongda Li, Changwei Ren, Zhaoquan Gu, Yuexuan Wang, Francis Lau*

16. **RePack: Dense Object Packing Using Deep CNN with Reinforcement Learning** CACS, 2019. [paper](https://ieeexplore.ieee.org/abstract/document/9024360/?casa_token=ScXezdDDiwMAAAAA:fglP_vbiQUJgLZcM7YZyqnDh_qA8jOjIh-zbH7ru0XSVBghh8OAxpThOU3BqhBeet4NlSrdHPcU)

    *Yu-Cheng Chu, Horng-Horng Lin*

17. **Reinforcement learning driven heuristic optimization** Arxiv, 2019. [paper](https://arxiv.org/pdf/1906.06639.pdf)

    *Qingpeng Cai, Will Hang, Azalia Mirhoseini, George Tucker, Jingtao Wang, Wei Wei*

18. **A Generalized Reinforcement Learning Algorithm for Online 3D Bin-Packing.** AAAI Workshop, 2020. [paper](https://arxiv.org/abs/2007.00463)

    *Richa Verma, Aniruddha Singhal, Harshad Khadilkar, Ansuma Basumatary, Siddharth Nayak, Harsh Vardhan Singh, Swagat Kumar, Rajesh Sinha*

19. **Robot Packing with Known Items and Nondeterministic Arrival Order.** TASAE, 2020. [paper](https://ieeexplore.ieee.org/abstract/document/9205914/)

    *Fan Wang, Kris Hauser*

20. **Simultaneous Planning for Item Picking and Placing by Deep Reinforcement Learning** IROS, 2020. [paper](http://ras.papercept.net/images/temp/IROS/files/0330.pdf)

    *Tatsuya Tanaka, Toshimitsu Kaneko, Masahiro Sekine, Voot Tangkaratt, Masashi Sugiyama*

21. **Monte Carlo Tree Search on Perfect Rectangle Packing Problem Instances** GECCO, 2020. [paper](https://dl.acm.org/doi/abs/10.1145/3377929.3398115)

    *Igor Pejic, Daan van den Berg*

22. **Learning Practically Feasible Policies for Online 3D Bin Packing** Arxiv, 2021. [paper](https://arxiv.org/abs/2108.13680)

    *Hang Zhao, Chenyang Zhu, Xin Xu, Hui Huang, Kai Xu*

23. **Attend2Pack: Bin Packing through Deep Reinforcement Learning with Attention** ICML Workshop, 2021. [paper](https://arxiv.org/abs/2107.04333)

    *Jingwei Zhang, Bin Zi, Xiaoyu Ge*

24. **Solving 3D bin packing problem via multimodal deep reinforcement learning** AAMAS, 2021. [paper](https://www.ifaamas.org/Proceedings/aamas2021/pdfs/p1548.pdf)

    *Yuan, Zhiguang Cao Jiang, Jie Zhang*

25. **Learning to Solve 3-D Bin Packing Problem via Deep Reinforcement Learning and Constraint Programming** IEEE transactions on cybernetics, 2021. [paper](https://ieeexplore.ieee.org/document/9606618/)

    *Yuan Jiang, Zhiguang Cao, Jie Zhang*

26. **Learning to Pack: A Data-Driven Tree Search Algorithm for Large-Scale 3D Bin Packing Problem** CIKM, 2021. [paper](https://dl.acm.org/doi/abs/10.1145/3459637.3481933)

    *Qianwen Zhu, Xihan Li, Zihan Zhang, Zhixing Luo, Xialiang Tong, Mingxuan Yuan, Jia Zeng*

27. **Learning Efficient Online 3D Bin Packing on Packing Configuration Trees.** ICLR, 2022. [paper](https://openreview.net/forum?id=bfuGjlCwAq)

    *Hang Zhao, Kai Xu*

28. **Improved Algorithms for Multi-period Multi-class Packing Problemswith Bandit Feedback** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24252)

    *Wonyoung Kim, Garud Iyengar, Assaf Zeevi*

29. **Adjustable Robust Reinforcement Learning for Online 3D Bin Packing** NeurIPS, 2023. [paper](https://openreview.net/forum?id=1mdTYi1jAW)

    *Yuxin Pan, Yize Chen, Fangzhen Lin*

30. **DRAGON: LLM-Driven Decomposition and Reconstruction Agents for Large-Scale Combinatorial Optimization** AAMAS, 2026. [paper](https://arxiv.org/abs/2601.06502)

    *Shengkai Chen, Zhiguang Cao, Jianan Zhou, Yaoxin Wu, Senthilnath Jayavelu, Zhuoyi Lin, Xiaoli Li, Shili Xiang*

### [Graph Edit Distance](#content)

1. **Graph Matching Networks for Learning the Similarity of Graph Structured Objects** ICML, 2019. [paper](https://arxiv.org/abs/1904.12787), [code](https://github.com/Lin-Yijie/Graph-Matching-Networks) ⭐ 320 | 🐛 5 | 🌐 Python | 📅 2026-06-16

   *Yujia Li, Chenjie Gu, Thomas Dullien, Oriol Vinyals, Pushmeet Kohli*

2. **SimGNN - A Neural Network Approach to Fast Graph Similarity Computation** WSDM, 2019. [paper](https://arxiv.org/abs/1808.05689), [code](https://github.com/yunshengb/SimGNN) ⭐ 154 | 🐛 19 | 🌐 Python | 📅 2019-09-27

   *Yunsheng Bai, Hao Ding, Song Bian, Ting Chen, Yizhou Sun, Wei Wang*

3. **⭐A Bi-Level Framework for Learning to Solve Combinatorial Optimization on Graphs** NeurIPS, 2021. [paper](https://arxiv.org/abs/2106.04927), [code](https://github.com/Thinklab-SJTU/PPO-BiHyb) ⭐ 106 | 🐛 0 | 🌐 Python | 📅 2023-04-19

   *Runzhong Wang, Zhigang Hua, Gan Liu, Jiayi Zhang, Junchi Yan, Feng Qi, Shuang Yang, Jun Zhou, Xiaokang Yang*

4. **Convolutional Embedding for Edit Distance** SIGIR, 2020. [paper](https://dl.acm.org/doi/abs/10.1145/3397271.3401045), [code](https://github.com/xinyandai/string-embed) ⭐ 63 | 🐛 1 | 🌐 Python | 📅 2023-05-03

   *Xinyan Dai, Xiao Yan, Kaiwen Zhou, Yuxuan Wang, Han Yang, James Cheng*

5. **Learning-Based Efficient Graph Similarity Computation via Multi-Scale Convolutional Set Matching** AAAI, 2020. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5720), [code](https://github.com/yunshengb/GraphSim) ⭐ 57 | 🐛 7 | 🌐 Python | 📅 2020-01-27

   *Yunsheng Bai, Hao Ding, Ken Gu, Yizhou Sun, Wei Wang*

6. **⭐Combinatorial Learning of Graph Edit Distance via Dynamic Embedding.** CVPR, 2021. [paper](https://arxiv.org/abs/2011.15039), [code](https://github.com/Thinklab-SJTU/GENN-Astar) ⭐ 28 | 🐛 3 | 🌐 Python | 📅 2022-08-29

   *Runzhong Wang, Tianqi Zhang, Tianshu Yu, Junchi Yan, Xiaokang Yang*

7. **Gelato: Graph Edit Distance via Autoregressive Neural Combinatorial Optimization** ICLR, 2026. [paper](https://openreview.net/forum?id=6ZTcLNmguc), [code](https://github.com/BorgwardtLab/Gelato) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-06-08

   *Paolo Pellizzoni, Till Hendrik Schulz, Karsten Borgwardt*

### [Hamiltonian Cycle Problem](#content)

1. **⭐A Bi-Level Framework for Learning to Solve Combinatorial Optimization on Graphs** NeurIPS, 2021. [paper](https://arxiv.org/abs/2106.04927), [code](https://github.com/Thinklab-SJTU/PPO-BiHyb) ⭐ 106 | 🐛 0 | 🌐 Python | 📅 2023-04-19

   *Runzhong Wang, Zhigang Hua, Gan Liu, Jiayi Zhang, Junchi Yan, Feng Qi, Shuang Yang, Jun Zhou, Xiaokang Yang*

2. **⭐UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP** ICLR, 2025. [paper](https://openreview.net/forum?id=yEwakMNIex), [code](https://github.com/Thinklab-SJTU/UniCO) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-06-20

   *Wenzheng Pan, Hao Xiong, Jiale Ma, Wentao Zhao, Yang Li, Junchi Yan*

3. **VSAL: A Vision Solver with Adaptive Layouts for Graph Property Detection** WWW, 2026. [paper](https://arxiv.org/abs/2602.13880), [code](https://github.com/Jiahao-Xie-86/VSAL) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-04-02

   *Jiahao Xie, Guangmo Tong*

### [Graph Coloring](#content)

1. **Optimization by Parallel Quasi-Quantum Annealing with Gradient-Based Sampling** ICLR, 2025. [paper](https://openreview.net/forum?id=9EfBeXaXf0), [code](https://github.com/Yuma-Ichikawa/QQA4CO) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-08-29

   *Yuma Ichikawa, Yamato Arai*

2. **Enhancing Column Generation by a Machine-Learning-Based Pricing Heuristic for Graph Coloring** AAAI, 2022. [paper](https://www.aaai.org/AAAI22Papers/AAAI-4026.ShenY.pdf), [code](https://github.com/Joey-Shen/MLPH.git) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2022-06-03

   *Yunzhuang, Yuan Sun, Xiaodong Li, Andrew Craig Eberhard Shen, Andreas T. Ernst.*

3. **Learning to Generate Columns with Application to Vertex Coloring** ICLR, 2023. [paper](https://openreview.net/forum?id=JHW30A4DXtO), [code](https://github.com/yuansuny/mlcg) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2023-02-23

   *Yuan Sun, Andreas T Ernst, Xiaodong Li, Jake Weiner*

4. **Deep Learning-based Hybrid Graph-Coloring Algorithm for Register Allocation.** Arxiv, 2019. [paper](https://arxiv.org/abs/1912.03700)

   *Dibyendu Das, Shahid Asghar Ahmad, Kumar Venkataramanan*

5. **Neural Models for Output-Space Invariance in Combinatorial Problems** ICLR, 2022. [paper](https://openreview.net/forum?id=ibrUkC-pbis)

   *Yatin Nandwani, Vidit Jain, Parag Singla, others*

### [Maximal Common Subgraph](#content)

1. **Fast Detection of Maximum Common Subgraph via Deep Q-Learning.** Arxiv, 2020. [paper](https://arxiv.org/abs/2002.03129)

   *Yunsheng Bai, Derek Xu, Alex Wang, Ken Gu, Xueqing Wu, Agustin Marinovic, Christopher Ro, Yizhou Sun, Wei Wang*

### [Influence Maximization](#content)

1. **⭐Towards One-shot Neural Combinatorial Solvers: Theoretical and Empirical Notes on the Cardinality-Constrained Case** ICLR, 2023. [paper](https://openreview.net/forum?id=h21yJhdzbwz), [code](https://github.com/Thinklab-SJTU/One-Shot-Cardinality-NN-Solver) ⭐ 43 | 🐛 1 | 🌐 Python | 📅 2024-09-27

   *Runzhong Wang, Li Shen, Yiting Chen, Junchi Yan, Xiaokang Yang, Dacheng Tao*

2. **LeNSE: Learning To Navigate Subgraph Embeddings for Large-Scale Combinatorial Optimisation** ICML, 2022. [paper](https://proceedings.mlr.press/v162/ireland22a.html), [code](https://github.com/davidireland3/LeNSE) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2022-11-26

   *David Ireland, G. Montana*

3. **Learning Heuristics over Large Graphs via Deep Reinforcement Learning.** NeurIPS, 2020. [paper](https://arxiv.org/abs/1903.03332)

   *Akash Mittal, Anuj Dhawan, Sahil Manchanda, Sourav Medya, Sayan Ranu, Ambuj Singh*

4. **Controlling Graph Dynamics with Reinforcement Learning and Graph Neural Networks.** ICML, 2021. [paper](https://arxiv.org/abs/2010.05313)

   *Eli A. Meirom, Haggai Maron, Shie Mannor, Gal Chechik*

5. **Deep Graph Representation Learning and Optimization for Influence Maximization** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24512)

   *Chen Ling, Junji Jiang, Junxiang Wang, My T. Thai, Lukas Xue, James Song, Meikang Qiu, Liang Zhao*

6. **Structure-Aware Cooperative Ensemble Evolutionary Optimization on Combinatorial Problems with Multimodal Large Language Models** NeurIPS, 2025. [paper](https://openreview.net/forum?id=zftxlb1AOo)

   *Jie Zhao, Kang Hao Cheong*

### [Max Clique](#content)

1. **A Diffusion Model Framework for Unsupervised Neural Combinatorial Optimization** ICML, 2024. [paper](https://arxiv.org/abs/2406.01661), [code](https://github.com/ml-jku/DIffUCO) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2025-10-09

   *Sebastian Sanokowski, Sepp Hochreiter, Sebastian Lehner*

2. **DISCS: A Benchmark for Discrete Sampling** NeurlPS, 2023. [paper](https://openreview.net/forum?id=oi1MUMk5NF), [code](https://github.com/google-research/discs) ⚠️ Archived

   *Katayoon Goshvadi, Haoran Sun, Xingchao Liu, Azade Nova, Ruqi Zhang, Will Sussman Grathwohl, Dale Schuurmans, Hanjun Dai*

3. **⭐ML4CO-Bench-101: Benchmark Machine Learning for Classic Combinatorial Problems on Graphs** NeurIPS, 2025. [paper](https://openreview.net/forum?id=ye4ntB1Kzi), [code](https://github.com/Thinklab-SJTU/ML4CO-Bench-101) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2025-11-17

   *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

4. **⭐COExpander: Adaptive Solution Expansion for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=KMaBXMWsBM), [code](https://github.com/Thinklab-SJTU/COExpander) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2025-06-28

   *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

5. **Variational Annealing on Graphs for Combinatorial Optimization** NeurlPS, 2023. [paper](https://openreview.net/forum?id=SLx7paoaTU), [code](https://github.com/ml-jku/VAG-CO) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-11-22

   *Sebastian Sanokowski, Wilhelm Franz Berghammer, Sepp Hochreiter, Sebastian Lehner*

6. **Regularized Langevin Dynamics for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=bbJ0QCujU4), [code](https://github.com/Shengyu-Feng/RLD4CO) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-06-15

   *Shengyu Feng, Yiming Yang*

7. **Can Hybrid Geometric Scattering Networks Help Solve the Maximum Clique Problem** NeurIPS, 2022. [paper](https://openreview.net/forum?id=uxc8hDSs_xh), [code](https://github.com/yimengmin/geometricscatteringmaximalclique) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-08-23

   *Yimeng Min, Frederik Wenkel, Michael Perlmutter, Guy Wolf*

8. **⭐ConRep4CO: Contrastive Representation Learning of Combinatorial Optimization Instances across Types** ICLR, 2026. [paper](https://openreview.net/forum?id=OXRnvOOiAf), [code](https://github.com/Thinklab-SJTU/ConRep4CO) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-03-09

   *Ziao Guo, Yang Li, Shiyue Wang, Junchi Yan*

9. **Learning fine-grained search space pruning and heuristics for combinatorial optimization.** Journal of Heuristics, 2023. [journal](https://dx.doi.org/10.1007/s10732-023-09512-z)

   *Juho Lauri, Sourav Dutta, Marco Grassia, Deepak Ajwani*

10. **Scalable Discrete Diffusion Samplers: Combinatorial Optimization and Statistical Physics** ICLR, 2025. [paper](https://openreview.net/pdf?id=peNgxpbdxB)

    *Sebastian Sanokowski, Wilhelm Franz Berghammer, Haoyu Peter Wang, Martin Ennemoser, Sepp Hochreiter, Sebastian Lehner*

11. **Approximation algorithms for combinatorial optimization with predictions** ICLR, 2025. [paper](https://openreview.net/forum?id=AEFVa6VMu1)

    *Antonios Antoniadis, Marek Elias, Adam Polak, Moritz Venzin*

### [Mixed Integer Programming](#content)

1. **Exact Combinatorial Optimization with Graph Convolutional Neural Networks** NeurlPS, 2019. [paper](https://arxiv.org/abs/1906.01629), [code](https://github.com/ds4dm/learn2branch) ⭐ 417 | 🐛 11 | 🌐 Python | 📅 2021-12-21

   *Maxime Gasse, Didier Chetelat, Nicola Ferroni, Laurent Charlin, Andrea Lodi*

2. **OptiMUS: Scalable Optimization Modeling with (MI)LP Solvers and Large Language Models** ICML, 2024. [paper](https://openreview.net/forum?id=YT1dtdLvSN), [code](https://github.com/teshnizi/OptiMUS) ⭐ 290 | 🐛 2 | 🌐 Python | 📅 2025-11-04

   *Ali AhmadiTeshnizi, Wenzhi Gao, Madeleine Udell*

3. **GNN-GBDT-Guided Fast Optimizing Framework for Large-scale Integer Programming** ICML, 2023. [paper](https://proceedings.mlr.press/v202/ye23e.html), [code](https://github.com/thuiar/GNN-GBDT-Guided-Fast-Optimizing-Framework) ⭐ 284 | 🐛 2 | 🌐 Python | 📅 2023-07-19

   *Huigen Ye, Hua Xu, Hongyan Wang, Chengming Wang, Yu Jiang*

4. **CombOptNet: Fit the Right NP-Hard Problem by Learning Integer Programming Constraints** Arxiv, 2021. [paper](https://openreview.net/forum?id=z4D7-PTxTb), [code](https://github.com/martius-lab/CombOptNet) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2022-04-28

   *Anselm Paulus, Michal Rolinek, Vit Musil, Brandon Amos, Georg Martius*

5. **A GNN-Guided Predict-and-Search Framework for Mixed-Integer Linear Programming** ICLR, 2023. [paper](https://openreview.net/forum?id=pHMpgT5xWaE), [code](https://github.com/sribdcn/Predict-and-Search_MILP_method) ⭐ 71 | 🐛 7 | 🌐 Python | 📅 2022-11-20

   *Qingyu Han, Linxin Yang, Qian Chen, Xiang Zhou, Dong Zhang, Akang Wang, Ruoyu Sun, Xiaodong Luo*

6. **Parameterizing Branch-and-Bound Search Trees to Learn Branching Policies** AAAI, 2021. [paper](https://www.aaai.org/AAAI21Papers/AAAI-9826.ZarpellonG.pdf), [code](https://github.com/ds4dm/branch-search-trees) ⭐ 68 | 🐛 5 | 🌐 Python | 📅 2021-07-19

   *Giulia Zarpellon, Jason Jo, Andrea Lodi, Yoshua Bengio*

7. **Learning Cut Selection for Mixed-Integer Linear Programming via Hierarchical Sequence Model** ICLR, 2023. [paper](https://openreview.net/forum?id=Zob4P9bRNcK), [code](https://github.com/MIRALab-USTC/L2O-HEM-Torch) ⭐ 67 | 🐛 3 | 🌐 Python | 📅 2023-05-12

   *Zhihai Wang, Xijun Li, Jie Wang, Yufei Kuang, Mingxuan Yuan, Jia Zeng, Yongdong Zhang, Feng Wu*

8. **Learning Cut Selection for Mixed-Integer Linear Programming via Hierarchical Sequence Model** ICLR, 2023. [paper](https://openreview.net/forum?id=Zob4P9bRNcK), [code](https://github.com/MIRALab-USTC/L2O-HEM-Torch) ⭐ 67 | 🐛 3 | 🌐 Python | 📅 2023-05-12

   *Zhihai Wang, Xijun Li, Jie Wang, Yufei Kuang, Mingxuan Yuan, Jia Zeng, Yongdong Zhang, Feng Wu*

9. **On Representing Mixed-Integer Linear Programs by Graph Neural Networks** ICLR, 2023. [paper](https://openreview.net/forum?id=4gc3MGZra1d), [code](https://github.com/liujl11git/GNN-MILP) ⭐ 61 | 🐛 1 | 🌐 Python | 📅 2023-08-11

   *Ziang Chen, Jialin Liu, Xinshang Wang, Wotao Yin*

10. **Hybrid Models for Learning to Branch** NeurlPS, 2020. [paper](https://arxiv.org/abs/2006.15212), [code](https://github.com/pg2455/Hybrid-learn2branch) ⭐ 50 | 🐛 1 | 🌐 Python | 📅 2021-05-31

    *Prateek Gupta, Maxime Gasse, Elias B Khalil, M Pawan Kumar, Andrea Lodi, Yoshua Bengio*

11. **Searching Large Neighborhoods for Integer Linear Programs with Contrastive Learning** ICML, 2023. [paper](https://proceedings.mlr.press/v202/huang23g.html), [code](https://github.com/facebookresearch/CL-LNS) ⚠️ Archived

    *Taoan Huang, Aaron M Ferber, Yuandong Tian, Bistra Dilkina, Benoit Steiner*

12. **Learning to Branch with Tree MDPs** Arxiv, 2022. [paper](https://arxiv.org/abs/2205.11107), [code](https://github.com/lascavana/rl2branch) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2024-10-04

    *Lara, F. Chen, Didier Ch'etelat, Maxime Gasse, Andrea Lodi, N. Yorke-Smith Scavuzzo, Karen Aardal.*

13. **Neur2BiLO: Neural Bilevel Optimization** NeurIPS, 2024. [paper](https://openreview.net/forum?id=esVleaqkRc), [code](https://github.com/khalil-research/Neur2BiLO) ⭐ 17 | 🐛 0 | 🌐 JetBrains MPS | 📅 2024-12-21

    *Justin Dumouchelle, Esther Julien, Jannis Kurtz, Elias B. Khalil*

14. **Learning to Search in Local Branching** AAAI, 2022. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/20294), [code](https://github.com/pandat8/ML4LB) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2026-01-25

    *Defeng Liu, Matteo Fischetti, Andrea Lodi*

15. **Large Language Model-driven Large Neighborhood Search for Large-Scale MILP Problems** ICML, 2025. [paper](https://openreview.net/forum?id=teUg2pMrF0), [code](https://github.com/thuiar/LLM-LNS) ⭐ 13 | 🐛 2 | 🌐 Python | 📅 2025-07-12

    *Huigen Ye, Hua Xu, An Yan, Yaoyang Cheng*

16. **Learning to Branch with Tree-aware Branching Transformers** Knowledge-Based Systems, 2022. [journal](https://www.sciencedirect.com/science/article/pii/S0950705122007298?via%3Dihub), [code](https://github.com/linjc16/TBranT) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2025-12-09

    *Jiacheng Lin, Jialin Zhu, Huangang Wang, Tao Zhang*

17. **Learning to Accelerate Approximate Methods for Solving Integer Programming via Early Fixing** Arxiv, 2022. [journal](https://arxiv.org/abs/2207.02087), [code](https://github.com/SCLBD/Accelerated-Lpbox-ADMM) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2022-07-06

    *Longkang Li, Baoyuan Wu.*

18. **Scalable Primal Heuristics Using Graph Neural Networks for Combinatorial Optimization** JAIR, 2024. [journal](https://www.jair.org/index.php/jair/article/view/14972), [code](https://github.com/furkancanturk/gnn4co) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-06-06

    *Furkan Canturk, Taha Varol, Reyhan Aydogan, Okan O Ozener*

19. **Towards General Algorithm Discovery for Combinatorial Optimization: Learning Symbolic Branching Policy from Bipartite Graph** ICML, 2024. [paper](https://openreview.net/forum?id=ULleq1Dtaw), [code](https://github.com/MIRALab-USTC/L2O-GS4CO) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-08-13

    *Yufei Kuang, Jie Wang, Yuyan Zhou, Xijun Li, Fangzhou Zhu, Jianye HAO, Feng Wu*

20. **Learning Cut Generating Functions for Integer Programming** NeurIPS, 2024. [paper](https://openreview.net/forum?id=8mZc259r8X), [code](https://github.com/Hongyu-Cheng/LearnCGF) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-05-22

    *Hongyu Cheng, Amitabh Basu*

21. **Sequential model-based optimization for general algorithm configuration** International conference on learning and intelligent optimization, 2011. [journal](https://link.springer.com/chapter/10.1007/978-3-642-25566-3_40)

    *Frank Hutter, Holger H Hoos, Kevin Leyton-Brown*

22. **Non-model-based Search Guidance for Set Partitioning Problems** AAAI, 2012. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI12/paper/view/5082)

    *Serdar Kadioglu, Yuri Malitsky, Meinolf Sellmann*

23. **A Aupervised Machine Learning Approach to Variable Branching in Branch-and-bound** Citeseer, 2014. [journal](https://citeseerx.ist.psu.edu/document?repid=rep1\&type=pdf\&doi=f35ba2bbc87dd31ae0a89d3ed9538fec9d15b4f0)

    *Alejandro Marcos Alvarez, Quentin Louveaux, Louis Wehenkel*

24. **Learning to Search in Branch-and-Bound Algorithms** NeurlPS, 2014. [paper](http://papers.nips.cc/paper/5495-learning-to-search-in-branch-and-bound-algorithms)

    *He He, Hal Daume III, Jason M Eisner*

25. **Learningto Branch in Mixed Integer Programming** AAAI, 2016. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/12514/11657)

    *E. B. Khalil, P. L. Bodic, L. Song, G. Nemhauser, B. Dilkina*

26. **Dash: Dynamic Approach for Switching Heuristics** European Journal of Operational Research, 2016. [journal](https://www.sciencedirect.com/science/article/pii/S0377221715007559)

    *Giovanni Di Liberto, Serdar Kadioglu, Kevin Leo, Yuri Malitsky*

27. **Learning When to Use a Decomposition** International conference on AI and OR techniques in constraint programming for combinatorial optimization problems, 2017. [journal](https://link.springer.com/chapter/10.1007/978-3-319-59776-8_16)

    *Markus Kruber, L{\u}bbecke Marco E, Parmentier Axel*

28. **Learning to Run Heuristics in Tree Search** IJCAI, 2017. [paper](https://www.ijcai.org/proceedings/2017/0092.pdf)

    *Elias B Khalil, Bistra Dilkina, George L Nemhauser, Shabbir Ahmed, Yufen Shao*

29. **Improving Learning to Branch via Reinforcement Learning** NeurIPS Workshop, 2020. [paper](https://openreview.net/forum?id=z4D7-PTxTb)

    *Haoran Sun, Wenbo Chen, Hui Li, Le Song*

30. **Reinforcement learning for variable selection in a branch and bound algorithm** International Conference on Integration of Constraint Programming, 2020. [journal](https://link.springer.com/chapter/10.1007/978-3-030-58942-4_12)

    *Marc Etheve, Zacharie Al{\`e}s, C{^o}me Bissuel, Olivier Juan, Safia Kedad-Sidhoum*

31. **Random sampling and machine learning to understand good decompositions** Annals of Operations Research, 2020. [journal](https://link.springer.com/article/10.1007/s10479-018-3067-9)

    *Saverio Basso, Alberto Ceselli, Andrea Tettamanzi*

32. **Reinforcement Learning for Integer Programming: Learning to Cut** ICML, 2020. [paper](http://proceedings.mlr.press/v119/tang20a.html)

    *Yunhao Tang, Shipra Agrawal, Yuri Faenza*

33. **Solving Mixed Integer Programs Using Neural Networks** Arxiv, 2020. [paper](https://arxiv.org/abs/2012.13349)

    *Vinod Nair, Sergey Bartunov, Felix Gimeno, Ingrid von Glehn, Pawel Lichocki, Ivan Lobov, Brendan O'Donoghue, Nicolas Sonnerat, Christian Tjandraatmadja, Pengming Wang, others*

34. **Learning Efficient Search Approximation in Mixed Integer Branch and Bound** Arxiv, 2020. [paper](https://arxiv.org/abs/2007.03948)

    *Kaan Yilmaz, Neil Yorke-Smith*

35. **Learning a Large Neighborhood Search Algorithm for Mixed Integer Programs** Arxiv, 2020. [paper](https://arxiv.org/abs/2107.10201)

    *Nicolas Sonnerat, Pengming Wang, Ira Ktena, Sergey Bartunov, Vinod Nair*

36. **A General Large Neighborhood Search Framework for Solving Integer Linear Programs** NeurlPS, 2020. [paper](https://arxiv.org/abs/2004.00422)

    *Jialin Song, Ravi Lanka, Yisong Yue, Bistra Dilkina*

37. **Neural Large Neighborhood Search** NeurlPS Workshop, 2020. [paper](https://openreview.net/forum?id=xEQhKANoVW)

    *Vinod Nair, Mohammad Alizadeh, others*

38. **Accelerating Primal Solution Findings for Mixed Integer Programs Based on Solution Prediction** AAAI, 2020. [paper](https://arxiv.org/abs/1906.09575)

    *Jian-Ya, Chao Zhang, Lei Shen, Shengyin Li, Bing Wang, Yinghui Xu Ding, Le Song*

39. **Reinforcement Learning for (Mixed) Integer Programming: Smart Feasibility Pump** ICML Workshop, 2021. [paper](https://arxiv.org/abs/2102.09663)

    *Meng Qi, Mengxin Wang, Zuo-Jun Shen*

40. **Learning to Select Cuts for Efficient Mixed-Integer Programming** Arxiv, 2021. [journal](https://arxiv.org/abs/2105.13645)

    *Zeren Huang, Kerong Wang, Furui Liu, Hui-ling Zhen, Weinan Zhang, Mingxuan Yuan, Jianye Hao, Yong Yu, Jun Wang*

41. **Confidence Threshold Neural Diving** NeurIPS ML4CO Competition Workshop, 2021. [paper](https://arxiv.org/abs/2202.07506)

    *Taehyun Yoon*

42. **Learning large neighborhood search policy for integer programming** NeurlPS, 2021. [paper](https://proceedings.neurips.cc/paper/2021/hash/fc9e62695def29ccdb9eb3fed5b4c8c8-Abstract.html)

    *Yaoxin Wu, Wen Song, Zhiguang Cao, Jie Zhang*

43. **Generative Deep Learning for Decision Making in Gas Networks** Arxiv, 2021. [paper](https://arxiv.org/abs/2102.02125)

    *Lovis Anderson, Mark Turner, Thorsten Koch*

44. **Offline Constraint Screening for Online Mixed-integer Optimization** Arxiv, 2021. [paper](https://arxiv.org/abs/2103.13074)

    *Asunción Jiménez-Cordero, Juan Miguel Morales, Salvador Pineda*

45. **Mixed Integer Programming versus Evolutionary Computation for Optimizing a Hard Real-World Staff Assignment Problem** ICAPS, 2021. [paper](https://ojs.aaai.org/index.php/ICAPS/article/view/3521)

    *Jannik Peters, Daniel Stephan, Isabel Amon, Hans Gawendowicz, Julius Lischeid, Lennart Salabarria, Jonas Umland, Felix Werner, Martin S Krejca, Ralf Rothenberger, others*

46. **Learning To Scale Mixed-Integer Programs** AAAI, 2021. [paper](https://www.aaai.org/AAAI21Papers/AAAI-7940.BertholdT.pdf)

    *Timo Berthold, Gregor Hendel*

47. **Learning Pseudo-Backdoors for Mixed Integer Programs** AAAI, 2021. [paper](https://arxiv.org/pdf/2106.05080.pdf)

    *Aaron Ferber, Jialin Song, Bistra Dilkina, Yisong Yue*

48. **Confidence Threshold Neural Diving** NeurIPS ML4CO Competition Workshop, 2021. [paper](https://arxiv.org/abs/2202.07506)

    *Taehyun Yoon*

49. **Learning Primal Heuristics for Mixed Integer Programs** IJCNN, 2021. [paper](https://arxiv.org/pdf/2107.00866.pdf)

    *Yunzhuang Shen, Yuan Sun, Andrew Eberhard, Xiaodong Li*

50. **Learning to Solve Large-scale Security-constrained Unit Commitment Problems** INFORMS Journal on Computing, 2021. [journal](https://pubsonline.informs.org/doi/abs/10.1287/ijoc.2020.0976)

    *{'A}linson S Xavier, Feng Qiu, Shabbir Ahmed*

51. **A Deep Reinforcement Learning Framework For Column Generation** Arxiv, 2022. [paper](https://arxiv.org/abs/2206.02568)

    *Cheng, Amine Mohamed Aboussalah, Elias Boutros Khalil, Juyoung Wang Chi, Zoha Sherkat-Masoumi.*

52. **Ranking Constraint Relaxations for Mixed Integer Programs Using a Machine Learning Approach** Arxiv, 2022. [journal](https://arxiv.org/abs/2207.00219)

    *Jake Weiner, Xiaodong Li Andreas T. Ernst, Yuan Sun.*

53. **Learning to Cut by Looking Ahead: Cutting Plane Selection via Imitation Learning** ICML, 2022. [paper](https://proceedings.mlr.press/v162/paulus22a.html)

    *Max B., Giulia Zarpellon, Andreas Krause, Laurent Charlin Paulus, Chris J. Maddison.*

54. **Lookback for Learning to Branch** Arxiv, 2022. [journal](https://arxiv.org/abs/2206.14987)

    *Prateek, Elias Boutros Khalil, Didier Chet'elat, Maxime Gasse, Yoshua Bengio, Andrea Lodi Gupta, M. Pawan Kumar.*

55. **Deep Reinforcement Learning for Exact Combinatorial Optimization: Learning to Branch** Arxiv, 2022. [paper](https://arxiv.org/abs/2206.06965)

    *Tianyu Zhang, Amin Banitalebi-Dehkordi, Yong Zhang*

56. **An Improved Reinforcement Learning Algorithm for Learning to Branch** Arxiv, 2022. [paper](https://arxiv.org/abs/2201.06213)

    *Qingyu Qu, Xijun Li, Yunfan Zhou, Jia Zeng, Mingxuan Yuan, Jie Wang, Jinhu Lv, Kexin Liu, Kun Mao*

57. **Learning to Use Local Cuts** Arxiv, 2022. [paper](https://arxiv.org/abs/2206.11618)

    *Timo Berthold, Matteo Francobaldi, Gregor Hendel*

58. **DOGE-Train: Discrete Optimization on GPU with End-to-end Training** Arxiv, 2022. [paper](https://arxiv.org/abs/2205.11638)

    *Ahmed Abbas, Paul Swoboda*

59. **Structural Analysis of Branch-and-Cut and the Learnability of Gomory Mixed Integer Cuts** NeurIPS, 2022. [paper](https://openreview.net/forum?id=e2gRdexoTZf)

    *Maria-Florina Balcan, Siddharth Prasad, Tuomas Sandholm, Ellen Vitercik*

60. **Constrained Discrete Black-Box Optimization using Mixed-Integer Programming** ICML, 2022. [paper](https://proceedings.mlr.press/v162/papalexopoulos22a.html)

    *Theodore, Christian Tjandraatmadja, Ross Anderson, Juan Pablo Vielma Papalexopoulos, Daving Belanger.*

61. **GNN\&GBDT-Guided Fast Optimizing Framework for Large-scale Integer Programming** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24107)

    *Huigen, Hua-Hui Xu, Hongyan Wang, Cheng . Wang Ye, YueYen Jiang.*

62. **Learning to Configure Separators in Branch-and-Cut** NeurIPS, 2023. [paper](https://openreview.net/forum?id=gf5xJVQS5p)

    *Sirui Li, Wenbin Ouyang, Max B Paulus, Cathy Wu*

63. **Learning to Dive in Branch and Bound** NeurIPS, 2023. [paper](https://openreview.net/forum?id=iPTF2hON1C)

    *Max B Paulus, Andreas Krause*

64. **A Deep Instance Generative Framework for MILP Solvers Under Limited Data Availability** NeurIPS, 2023. [paper](https://openreview.net/forum?id=AiEipk1X0c), [code](https://miralab-ustc.github.io/L2O-G2MILP)

    *Zijie Geng, Xijun Li, Jie Wang, Xiao Li, Yongdong Zhang, Feng Wu*

65. **Contrastive Predict-and-Search for Mixed Integer Linear Programs** ICML, 2024. [paper](https://openreview.net/forum?id=zatLnLvbs8)

    *Taoan Huang, Aaron M Ferber, Arman Zharmagambetov, Yuandong Tian, Bistra Dilkina*

66. **Sample Complexity of Algorithm Selection Using Neural Networks and Its Applications to Branch-and-Cut** NeurIPS, 2024. [paper](https://openreview.net/forum?id=uOvrwVW1yA)

    *Hongyu Cheng, Sammy Khalife, Barbara Fiedorowicz, Amitabh Basu*

67. **Rethinking the Capacity of Graph Neural Networks for Branching Strategy** NeurIPS, 2024. [paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/dff528ce3e1390c88f10bbf5e722a241-Abstract-Conference.html)

    *Ziang Chen, Jialin Liu, Xiaohan Chen, Xinshang Wang, Wotao Yin*

68. **MILP-StuDio: MILP Instance Generation via Block Structure Decomposition** NeurIPS, 2024. [paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/61a8faabae5704ce6f095e89856d7c79-Abstract-Conference.html)

    *Haoyang Liu, Jie Wang, Wanbo Zhang, Zijie Geng, Yufei Kuang, Xijun Li, Yongdong Zhang, Bin Li, Feng Wu*

69. **OptimAI: Optimization from Natural Language Using LLM-Powered AI Agents** arXiv, 2025. [paper](https://arxiv.org/abs/2504.16918)

    *Thind, Raghav and Sun, Youran and Liang, Ling and Yang, Haizhao*

70. **Don't Restart Just Reuse: Reoptimizing MILPs with Dynamic Parameters** ICML, 2025. [paper](https://openreview.net/forum?id=ZRGZ4OcfXV)

    *Sijia Zhang, Shuli Zeng, Shaoang Li, Feng Wu, Shaojie Tang, Xiangyang Li*

71. **A Markov Decision Process for Variable Selection in Branch & Bound** NeurIPS, 2025. [paper](https://openreview.net/forum?id=05Svr0k5C9)

    *Paul STRANG, Zacharie ALES, Côme Bissuel, Olivier Juan, Safia Kedad-Sidhoum, Emmanuel Rachelson*

72. **Dynamic Configuration for Cutting Plane Separators via Reinforcement Learning on Incremental Graph** NeurIPS, 2025. [paper](https://openreview.net/forum?id=iXjVis9Cwn)

    *Mingxuan Ye, Jie Wang, Fangzhou Zhu, Zhihai Wang, Yufei Kuang, Xijun Li, Weilin Luo, Jianye HAO, Feng Wu*

73. **Generalization Guarantees for Learning Score-Based Branch-and-Cut Policies in Integer Programming** NeurIPS, 2025. [paper](https://openreview.net/forum?id=v5ru9MGjsW)

    *Hongyu Cheng, Amitabh Basu*

74. **When GNNs meet symmetry in ILPs: an orbit-based feature augmentation approach** ICLR, 2025. [paper](https://openreview.net/forum?id=wVTJRnZ11Z)

    *Qian Chen, Lei Li, Qian Li, Jianghua Wu, Akang Wang, Ruoyu Sun, Xiaodong Luo, Tsung-Hui Chang, Qingjiang Shi*

### [Causal Discovery](#content)

1. **CUTS: Neural Causal Discovery from Irregular Time-Series Data** ICLR, 2023. [paper](https://openreview.net/forum?id=UG8bQcD3Emv), [code](https://github.com/jarrycyx/unn) ⭐ 165 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-09-26

   *Yuxiao Cheng, Runzhao Yang, Tingxiong Xiao, Zongren Li, Jinli Suo, Kunlun He, Qionghai Dai*

2. **Diffusion Models for Causal Discovery via Topological Ordering** ICLR, 2023. [paper](https://openreview.net/forum?id=Idusfje4-Wq), [code](https://github.com/vios-s/DiffAN) ⭐ 92 | 🐛 3 | 🌐 Python | 📅 2023-03-17

   *Pedro Sanchez, Xiao Liu, Alison Q O'Neil, Sotirios A Tsaftaris*

3. **Large-Scale Differentiable Causal Discovery of Factor Graphs** NeurIPS, 2022. [paper](https://openreview.net/forum?id=k713e8vXzwR), [code](https://github.com/Genentech/dcdfg) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2022-10-04

   *Romain Lopez, Jan-Christian H{"u}tter, Jonathan K Pritchard, Aviv Regev*

4. **Nonlinear Causal Discovery with Latent Confounders** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/23789), [code](https://github.com/chunlinli/defuse) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2023-02-09

   *David Kaltenpoth, Jilles Vreeken*

5. **Boosting Causal Discovery via Adaptive Sample Reweighting** ICLR, 2023. [paper](https://openreview.net/forum?id=LNpMtk15AS4), [code](https://github.com/anzhang314/ReScore) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2023-03-19

   *An Zhang, Fangfu Liu, Wenchang Ma, Zhibo Cai, Xiang Wang, Tat-seng Chua*

6. **DAGs with NO TEARS: Continuous Optimization for Structure Learning.** NeurIPS, 2018. [paper](https://arxiv.org/pdf/1803.01422.pdf)

   *Xun Zheng, Bryon Aragam, Pradeep Ravikumar, Eric Xing*

7. **Causal Discovery with Reinforcement Learning.** ICLR, 2020. [paper](https://arxiv.org/abs/1906.04477)

   *Shengyu Zhu, Ignavier Ng, Zhitang Chen*

8. **BayesDAG: Gradient-Based Posterior Inference for Causal Discovery** NeurIPS, 2023. [paper](https://openreview.net/forum?id=woptnU6fh1)

   *Yashas Annadani, Nick Pawlowski, Joel Jennings, Stefan Bauer, Cheng Zhang, Wenbo Gong*

9. **Sample Complexity Bounds for Score-Matching: Causal Discovery and Generative Modeling** NeurIPS, 2023. [paper](https://openreview.net/forum?id=uNnPWR66b8)

   *Zhenyu Zhu, Francesco Locatello, Volkan Cevher*

### [Game Theoretic Semantics](#content)

1. **First-Order Problem Solving through Neural MCTS based Reinforcement Learning.** Arxiv, 2021. [paper](https://arxiv.org/abs/2101.04167)

   *Ruiyang Xu, Prashank Kadam, Karl Lieberherr*

### [Differentiable Optimization](#content)

1. **Differentiation of Blackbox Combinatorial Solvers** ICLR, 2020. [paper](https://arxiv.org/pdf/1912.02175v2.pdf), [code](https://github.com/martius-lab/blackbox-backprop) ⭐ 355 | 🐛 3 | 🌐 Python | 📅 2021-12-21

   *Marin Vlastelica, Anselm Paulus, Vít Musil, Georg Martius, Michal Rolínek*

2. **Differentiation of blackbox combinatorial solvers** ICLR, 2020. [paper](https://openreview.net/forum?id=BkevoJSYPB), [code](https://github.com/martius-lab/blackbox-backprop) ⭐ 355 | 🐛 3 | 🌐 Python | 📅 2021-12-21

   *Marin Vlastelica Pogani, Anselm Paulus, Vit Musil, Georg Martius, Michal Rolinek*

3. **Differentiable Learning of Submodular Models** NeurIPS, 2017. [paper](https://papers.NeurIPS.cc/paper/2017/hash/192fc044e74dffea144f9ac5dc9f3395-Abstract.html), [code](https://github.com/josipd/torch-submod) ⭐ 57 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2017-11-07

   *Josip Djolonga, Andreas Krause*

4. **SurCo: Learning Linear Surrogates For Combinatorial Nonlinear Optimization Problems** ICML, 2023. [paper](https://arxiv.org/abs/2210.12547), [code](https://github.com/facebookresearch/SurCo) ⚠️ Archived

   *Aaron M Ferber, Taoan Huang, Daochen Zha, Martin Schubert, Benoit Steiner, Bistra Dilkina, Yuandong Tian*

5. **Backpropagation through Combinatorial Algorithms: Identity with Projection Works** ICLR, 2023. [paper](https://openreview.net/forum?id=JZMR727O29), [code](https://github.com/martius-lab/solver-differentiation-identity) ⭐ 13 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-09-29

   *Subham Sekhar Sahoo, Anselm Paulus, Marin Vlastelica, Vít Musil, Volodymyr Kuleshov, Georg Martius*

6. **MIPaaL: Mixed Integer Program as a Layer** AAAI, 2020. [paper](https://ojs.aaai.org//index.php/AAAI/article/view/5509), [code](https://github.com/amf272/MIPaaL/) ⭐ 4 | 🐛 1 | 📅 2019-11-21

   *Aaron Ferber, Bryan Wilder, Bistra Dilkina, Milind Tambe*

### [Car Dispatch](#content)

1. **Dispatch of autonomous vehicles for taxi services: A deep reinforcement learning approach** Transportation Research, 2020. [journal](https://www.sciencedirect.com/science/article/pii/S0968090X19312227)

   *Chao Mao, Yulin Liu, Zuo-Jun (Max) Shen*

### [Electronic Design Automation](#content)

1. **⭐On Joint Learning for Solving Placement and Routing in Chip Design** NeurIPS, 2021. [paper](https://arxiv.org/abs/2111.00234), [code](https://github.com/Thinklab-SJTU/EDA-AI) ⭐ 322 | 🐛 16 | 🌐 C | 📅 2025-11-23

   *Ruoyu Cheng, Junchi Yan*

2. **⭐The Policy-gradient Placement and Generative Routing Neural Networks for Chip Design** NeurIPS, 2022. [paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/a8b8c1ad51df1b93d9e3d1fca75debbf-Abstract-Conference.html), [code](https://github.com/Thinklab-SJTU/EDA-AI) ⭐ 322 | 🐛 16 | 🌐 C | 📅 2025-11-23

   *Ruoyu Cheng, Xianglong Lyu, Yang Li, Junjie Ye, Jianye Hao, Junchi Yan*

3. **HeuriGym: An Agentic Benchmark for LLM-Crafted Heuristics in Combinatorial Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2506.07972), [code](https://github.com/cornell-zhang/heurigym) ⭐ 94 | 🐛 2 | 🌐 Python | 📅 2026-04-25

   *Hongzheng Chen, Yingheng Wang, Yaohui Cai, Hins Hu, Jiajie Li, Shirley Huang, Chenhui Deng, Rongjian Liang, Shufeng Kong, Haoxing Ren, Samitha Samaranayake, Carla P. Gomes, Zhiru Zhang*

4. **Unsupervised Learning for Combinatorial Optimization with Principled Objective Relaxation** NeurIPS, 2022. [paper](https://openreview.net/forum?id=HjNn9oD_v47), [code](https://github.com/Graph-COM/CO_ProxyDesign) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2022-10-09

   *Haoyu Peter Wang, Nan Wu, Hang Yang, Cong Hao, Pan Li*

5. **A graph placement methodology for fast chip design** Nature, 2021. [journal](https://www.nature.com/articles/s41586-021-03544-w.pdf)

   *Azalia Mirhoseini, Anna Goldie, Mustafa Yazgan, Joe Wenjie Jiang, Ebrahim Songhori, Shen Wang, Young-Joon Lee, Eric Johnson, Omkar Pathak, Azade Nazi, Jiwoo Pak, Andy Tong, Kavya Srinivasa, William Hang, Emre Tuncer, Quoc V. Le, James Laudon, Richard Ho, Roger Carpenter, Jeff Dean*

6. **CktGNN: Circuit Graph Neural Network for Electronic Design Automation** ICLR, 2023. [paper](https://openreview.net/forum?id=NE2911Kq1sp)

   *Zehao Dong, Weidong Cao, Muhan Zhang, Dacheng Tao, Yixin Chen, Xuan Zhang*

7. **⭐HubRouter: Learning Global Routing via Hub Generation and Pin-hub Connection** NeurIPS, 2023. [paper](https://openreview.net/forum?id=f0Jj3C3Pnp)

   *Xingbo Du, Chonghua Wang, Ruizhe Zhong, Junchi Yan*

8. **Expertise Can Be Helpful for Reinforcement Learning-based Macro Placement** ICLR, 2026. [paper](https://openreview.net/forum?id=yqvNwfxRR6)

   *Chengrui Gao, Yunqi Shi, Ke Xue, Ruo-Tong Chen, Siyuan Xu, Mingxuan Yuan, Chao Qian, Zhi-Hua Zhou*

### [Conjunctive Query Containment](#content)

1. **It's Not What Machines Can Learn It's What We Cannot Teach** ICML, 2020. [paper](http://proceedings.mlr.press/v119/yehuda20a/yehuda20a.pdf)

   *Gal Yehuda, Moshe Gabel, Assaf Schuster*

### [Virtual Network Embedding](#content)

1. **Deep Reinforcement Based Optimization of Function Splitting in Virtualized Radio Access Networks** ICC, 2021. [paper](https://ieeexplore.ieee.org/document/9473703), [code](https://github.com/rubensolozabal/vnf_placement_optimization_rl) ⭐ 77 | 🐛 3 | 🌐 Python | 📅 2023-03-25

   *Fahri Wisnu Murti, Samad Ali, Matti Latva-aho*

2. **⭐GAL-VNE: Solving the VNE Problem with Global Reinforcement Learning and Local One-Shot Neural Prediction** KDD, 2023. [paper](https://dl.acm.org/doi/10.1145/3580305.3599358), [code](https://github.com/Thinklab-SJTU/GAL-VNE) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2024-05-04

   *Haoyu Geng, Runzhong Wang, Fei Wu, Junchi Yan*

3. **Virtual Network Embedding via Monte Carlo Tree Search** IEEE Trans. Cybern, 2017. [journal](https://ieeexplore.ieee.org/document/7859375)

   *Soroush Haeri, Ljiljana Trajković*

4. **A novel reinforcement learning algorithm for virtual network embedding** Neurocomputing, 2018. [journal](https://www.sciencedirect.com/science/article/abs/pii/S0925231218300420)

   *Haipeng Yao, Xu Chen, Maozhen Li, Peiying Zhang, Luyao Wang*

5. **NeuroViNE: A Neural Preprocessor for Your Virtual Network Embedding Algorithm** INFOCOM, 2018. [paper](https://ieeexplore.ieee.org/document/8486263)

   *Andreas Blenk, Patrick Kalmbach, Johannes Zerwas, Michael Jarschel, Stefan Schmid, Wolfgang Kellerer*

6. **A Virtual Network Embedding Algorithm Based On Double-Layer Reinforcement Learning** TCJ, 2019. [journal](https://ieeexplore.ieee.org/document/9514735)

   *Meng Li, MeiLian Lu*

7. **NFVdeep: Adaptive Online Service Function Chain Deployment with Deep Reinforcement Learning** IWQoS, 2019. [paper](https://ieeexplore.ieee.org/document/9068634)

   *Yikai Xiao, Qixia Zhang, Fangming Liu, Jia Wang, Miao Zhao, Zhongxing Zhang, Jiaxing Zhang*

8. **A Continuous-Decision Virtual Network Embedding Scheme Relying on Reinforcement Learning** IEEE TNSM, 2020. [journal](https://ieeexplore.ieee.org/document/8982091)

   *Haipeng Yao, Sihan Ma, Jingjing Wang, Peiying Zhang, Chunxiao Jiang, Song Guo*

9. **Automatic Virtual Network Embedding A Deep Reinforcement Learning Approach With Graph Convolutional Networks** J-SAC, 2020. [journal](https://ieeexplore.ieee.org/document/9060910)

   *Zhongxia Yan, Jingguo Ge, Yulei Wu, Liangxiong Li, Tong Li*

10. **A Q-learning-based approach for virtual network embedding in data center** NCA, 2020. [journal](https://link.springer.com/article/10.1007/s00521-019-04376-6)

    *Ying Yuan, Zejie Tian, Cong Wang, Fanghui Zheng, Yanxia Lv*

11. **Accelerating Virtual Network Embedding with Graph Neural Networks** CNSM, 2020. [journal](https://ieeexplore.ieee.org/document/9269128)

    *Farzad Habibi, Mahdi Dolati, Ahmad Khonsari, Majid Ghaderi*

12. **Dynamic Virtual Network Embedding Algorithm Based on Graph Convolution Neural Network and Reinforcement Learning** IoT-J, 2021. [journal](https://ieeexplore.ieee.org/document/9475485)

    *Peiying Zhang, Chao Wang, Neeraj Kumar, Weishan Zhang, Lei Liu*

13. **DRL-SFCP: Adaptive Service Function Chains Placement with Deep Reinforcement Learning** ICC, 2021. [paper](https://ieeexplore.ieee.org/document/9500964)

    *Tianfu Wang, Qilin Fan, Xiuhua Li, Xu Zhang, Qingyu Xiong, Shu Fu, Min Gao*

### [Predict+Optimize](#content)

1. **Differentiable Convex Optimization Layers** NeurIPS, 2019. [paper](https://dl.acm.org/doi/abs/10.5555/3454287.3455145), [code](https://github.com/cvxgrp/cvxpylayers) ⭐ 2,130 | 🐛 23 | 🌐 Python | 📅 2026-05-19

   *Akshay Agrawal, Stephen Boyd*

2. **OptNet: differentiable optimization as a layer in neural networks** ICML, 2017. [paper](https://dl.acm.org/doi/abs/10.5555/3305381.3305396), [code](https://github.com/locuslab/optnet) ⭐ 592 | 🐛 3 | 🌐 Python | 📅 2020-03-26

   *Brandon Amos, J. Zico Kolter*

3. **Implicit MLE: Backpropagating Through Discrete Exponential Family Distributions** NeurIPS, 2021. [paper](https://openreview.net/forum?id=lR4aaWCQgB), [code](https://github.com/uclnlp/torch-imle) ⭐ 260 | 🐛 0 | 🌐 Python | 📅 2023-10-29

   *Mathias Niepert, Pasquale Minervini, Luca Franceschi*

4. **Deep Declarative Networks** TPAMI, 2022. [paper](https://ieeexplore.ieee.org/document/9355027), [code](https://github.com/anucvml/ddn) ⭐ 253 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-06-18

   *Stephen Gould, Richard Hartley, Dylan Campbell*

5. **Smart Predict-and-Optimize for Hard Combinatorial Optimization Problems** AAAI, 2020. [paper](https://arxiv.org/abs/1911.10092), [code](https://github.com/JayMan91/aaai_predit_then_optimize) ⚠️ Archived

   *Jayanta Mandi, Emir Demirovic, Peter J. Stuckey, Tias Guns*

6. **Two-Stage Predict+Optimize for Mixed Integer Linear Programs with Unknown Parameters in Constraints** NeurIPS, 2023. [paper](https://openreview.net/forum?id=0tnhFpyWjb), [code](https://github.com/elizabethxyhu/neurips_two_stage_predict-optimize) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-03-25

   *Xinyi Hu, Jasper CH Lee, Jimmy HM Lee*

7. **Interior Point Solving for LP-based prediction+optimization** NeurIPS, 2020. [paper](https://proceedings.neurips.cc//paper/2020/hash/51311013e51adebc3c34d2cc591fefee-Abstract.html), [code](https://github.com/JayMan91/NeurIPSIntopt) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2024-05-16

   *Jayanta Mandi, Tias Guns*

8. **COPS: Combinatorial Optimization for Panoptic Segmentation: A Fully Differentiable Approach** NeurIPS, 2021. [paper](https://proceedings.neurips.cc/paper/2021/hash/83a368f54768f506b833130584455df4-Abstract.html), [code](https://github.com/aabbas90/COPS) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2022-06-30

   *Ahmed Abbas, Paul Swoboda*

9. **End-to-End Stochastic Optimization with Energy-Based Model** NeurIPS, 2022. [paper](https://openreview.net/forum?id=_sYOodxTMcF), [code](https://github.com/Lingkai-Kong/so-ebm) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-02-14

   *Lingkai Kong, Jiaming Cui, Yuchen Zhuang, Rui Feng, B. Aditya Prakash, Chao Zhang*

10. **A Surrogate Objective Framework for Prediction+Programming with Soft Constraints** NeurIPS, 2021. [paper](https://openreview.net/forum?id=9Sa2xh4mGR), [code](https://github.com/PredOptwithSoftConstraint/PredOptwithSoftConstraint) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2021-08-30

    *Kai Yan, Jie Yan, Chuan Luo, Liting Chen, Qingwei Lin, Dongmei Zhang*

11. **Contrastive Losses and Solution Caching for Predict-and-Optimize** IJCAI, 2021. [paper](https://www.ijcai.org/proceedings/2021/0390.pdf), [code](https://github.com/jayman91/ltr-predopt) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2022-07-31

    *Maxime Mulamba, Jayanta Mandi, Michelangelo Diligenti, Michele Lombardi, Victor Bucarey, Tias Guns*

12. **An Exact Symbolic Reduction of Linear Smart Predict+Optimize to Mixed Integer Linear Programming** ICML, 2022. [paper](https://proceedings.mlr.press/v162/jeong22a.html), [code](https://github.com/jihwan-jeong/xaddpy) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-03-14

    *Jihwan Jeong, Parth Jaggi, Andrew Butler, Scott Sanner*

13. **Predict+optimise with ranking objectives: exhaustively learning linear functions** IJCAI, 2019. [paper](https://dl.acm.org/doi/abs/10.5555/3367032.3367186)

    *Emir Demirovic, Peter J. Stuckey, James Bailey, Jeffrey Chan, Christopher Leckie, Kotagiri Ramamohanarao, Tias Guns*

14. **Melding the Data-Decisions Pipeline: Decision-Focused Learning for Combinatorial Optimization** AAAI, 2019. [paper](https://ojs.aaai.org//index.php/AAAI/article/view/3982)

    *Bryan Wilder, Bistra Dilkina, Milind Tambe*

15. **Automatically Learning Compact Quality-aware Surrogates for Optimization Problems** NeurIPS, 2020. [paper](https://openreview.net/forum?id=v8hzdOdOle)

    *Kai Wang, Bryan Wilder, Andrew Perrault, Milind Tambe*

16. **Predict+ Optimize for packing and covering LPs with unknown parameters in constraints** AAAI, 2023. [paper](https://dl.acm.org/doi/10.1609/aaai.v37i4.25513)

    *Xinyi Hu, Jasper C.H. Lee, Jimmy H.M. Lee*

### [Optimal Power Flow](#content)

1. **Predicting AC Optimal Power Flows: Combining Deep Learning and Lagrangian Dual Methods** AAAI, 2020. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5403), [code](https://github.com/AIPOpt-Lab-SU/lagrangian-dual-deep-learning) ⭐ 21 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2021-09-27

   *Ferdinando Fioretto, Terrence W\.K. Mak, Pascal Van Hentenryck*

2. **DeepOPF: A Deep Neural Network Approach for Security-Constrained DC Optimal Power Flow** SmartGridComm, 2019. [paper](https://ieeexplore.ieee.org/document/8909795)

   *Xiang Pan, Tianyu Zhao, Minghua Chen*

3. **Adversarially Robust Learning for Security-Constrained Optimal Power Flow** NeurIPS, 2021. [paper](https://proceedings.neurips.cc/paper/2021/hash/f0f07e680de407b0f12abf15bd520097-Abstract.html)

   *Priya Donti, Aayushya Agarwal, Neeraj Vijay Bedmutha, Larry Pileggi, J. Zico Kolter*

4. **Ensuring DNN Solution Feasibility for Optimization Problems with Linear Constraints** ICLR, 2023. [paper](https://openreview.net/forum?id=QVcDQJdFTG)

   *Tianyu Zhao, Xiang Pan, Minghua Chen, Steven Low*

### [Facility Location Problem](#content)

1. **⭐Towards One-shot Neural Combinatorial Solvers: Theoretical and Empirical Notes on the Cardinality-Constrained Case** ICLR, 2023. [paper](https://openreview.net/forum?id=h21yJhdzbwz), [code](https://github.com/Thinklab-SJTU/One-Shot-Cardinality-NN-Solver) ⭐ 43 | 🐛 1 | 🌐 Python | 📅 2024-09-27

   *Runzhong Wang, Li Shen, Yiting Chen, Junchi Yan, Xiaokang Yang, Dacheng Tao*

2. **Learning to Prune Instances of k-median and Related Problems.** ALENEX, 2022. [paper](https://dx.doi.org/10.1137/1.9781611977042.15), [code](https://github.com/dajwani/alenex22) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-01-28

   *Dena Tayebi, Saurabh Ray, Deepak Ajwani*

3. **Solving uncapacitated P-Median problem with reinforcement learning assisted by graph attention networks** Applied Intelligence, 2023. [paper](https://link.springer.com/article/10.1007/s10489-022-03453-z)

   *Chenguang Wang, Congying Han, Tiande Guo, Man Ding*

### [Combinatorial Drug Recommendation](#content)

1. **GAMENet: Graph Augmented MEmory Networks for Recommending Medication Combination** AAAI, 2019. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/3905), [code](https://github.com/sjy1203/GAMENet) ⭐ 152 | 🐛 17 | 🌐 Python | 📅 2018-11-11

   *Junyuan Shang, Cao Xiao, Tengfei Ma, Hongyan Li, Jimeng Sun*

2. **SafeDrug: Dual Molecular Graph Encoders for Recommending Effective and Safe Drug Combinations** IJCAI, 2021. [paper](https://www.ijcai.org/proceedings/2021/0514.pdf), [code](https://github.com/ycq091044/SafeDrug) ⭐ 98 | 🐛 3 | 🌐 Python | 📅 2023-08-01

   *Chaoqi Yang, Cao Xiao, Fenglong Ma, Lucas Glass, Jimeng Sun*

3. **⭐MoleRec: Combinatorial Drug Recommendation with Substructure-Aware Molecular Representation Learning** WWW, 2023. [paper](https://dl.acm.org/doi/10.1145/3543507.3583872), [code](https://github.com/yangnianzu0515/MoleRec) ⭐ 69 | 🐛 1 | 🌐 Python | 📅 2023-06-08

   *Nianzu Yang, Kaipeng Zeng, Qitian Wu, Junchi Yan*

4. **Debiased, Longitudinal and Coordinated Drug Recommendation through Multi-Visit Clinic Recordss** NeurIPS, 2022. [paper](https://openreview.net/forum?id=zVglD2W0EAS), [code](https://github.com/ssshddd/DrugRec) ⭐ 43 | 🐛 7 | 🌐 Python | 📅 2023-05-04

   *Hongda Sun, Shufang Xie, Shuqi Li, Yuhan Chen, Ji-Rong Wen, Rui Yan*

5. **Enhancing Activity Prediction Models in Drug Discovery with the Ability to Understand Human Language** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/24953)

   *Philipp Seidl, Andreu Vall, Sepp Hochreiter, Gunter Klambauer*

6. **Learning Subpocket Prototypes for Generalizable Structure-based Drug Design** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/25062)

   *Zaixin Zhang, Qi Liu*

7. **DECOMPDIFF: Diffusion Models with Decomposed Priors for Structure-Based Drug Design** ICML, 2023. [paper](https://icml.cc/virtual/2023/poster/23697)

   *Jiaqi Guan, Xiangxin Zhou, Yuwei Yang, Yu Bao, Jian-wei Peng, Jianzhu Ma, Q. Liu, Liang Wang, Quanquan Gu*

### [Stochastic Combinatorial Optimization](#content)

1. **Neur2SP- Neural Two-Stage Stochastic Programming** NeurIPS, 2022. [paper](https://openreview.net/forum?id=HQDvPsdXS-F), [code](https://github.com/khalil-research/Neur2SP) ⭐ 57 | 🐛 1 | 🌐 Python | 📅 2023-03-08

   *Rahul Mihir Patel, Justin Dumouchelle, Elias Boutros Khalil, Merve Bodur*

2. **USCO-Solver: Solving Undetermined Stochastic Combinatorial Optimization Problems** NeurIPS, 2021. [paper](https://openreview.net/forum?id=P85jauwfNCV), [code](https://github.com/cdslabamotong/USCO-Solver) ⭐ 5 | 🐛 0 | 🌐 Roff | 📅 2022-10-10

   *Guangmo Tong*

3. **From Sequential to Parallel: Reformulating Dynamic Programming as GPU Kernels for Large-Scale Stochastic Combinatorial Optimization** ICLR, 2026. [paper](https://arxiv.org/abs/2602.05179), [code](https://github.com/Jingyi-poly/2-stage-IRP-GPU/tree/CVRPSD-split-GPU) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-05-12

   *Jingyi Zhao, Linxin Yang, Haohua Zhang, Qile He, Tian Ding*

4. **Learning fast optimizers for contextual stochastic integer programs** UAI, 2018. [paper](http://auai.org/uai2018/proceedings/papers/217.pdf)

   *V Nair, D Dvijotham, I Dunning, O Vinyals*

5. **A New Approach for Vehicle Routing with Stochastic Demand- Combining Route Assignment with Process Flexibility** OR, 2022. [journal](https://pubsonline.informs.org/doi/abs/10.1287/opre.2022.2304)

   *Kirby Ledvina, Hanzhang Qin, David Simchi-Levi, Yehua Wei*

6. **Learning to Optimize with Stochastic Dominance Constraints** AISTATS, 2023. [paper](https://proceedings.mlr.press/v206/dai23b.html)

   *Hanjun Dai, Yuan Xue, Niao He, Yixin Wang, Na Li, Dale Schuurmans, Bo Dai*

### [Vertex Cover](#content)

1. **Large Language Models as End-to-end Combinatorial Optimization Solvers** NeurIPS, 2025. [paper](https://neurips.cc/virtual/2025/loc/san-diego/poster/115835), [code](https://github.com/Summer142857/LLMCoSolver) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2025-10-24

   *Xia Jiang, Yaoxin Wu, Minshuo Li, Zhiguang Cao, Yingqian Zhang*

2. **⭐ML4CO-Bench-101: Benchmark Machine Learning for Classic Combinatorial Problems on Graphs** NeurIPS, 2025. [paper](https://openreview.net/forum?id=ye4ntB1Kzi), [code](https://github.com/Thinklab-SJTU/ML4CO-Bench-101) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2025-11-17

   *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

3. **⭐COExpander: Adaptive Solution Expansion for Combinatorial Optimization** ICML, 2025. [paper](https://openreview.net/forum?id=KMaBXMWsBM), [code](https://github.com/Thinklab-SJTU/COExpander) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2025-06-28

   *Jiale Ma, Wenzheng Pan, Yang Li, Junchi Yan*

4. **Projecting Latent RL Actions: Towards Generalizable and Scalable Graph Combinatorial Optimization** Arxiv, 2026. [paper](https://arxiv.org/abs/2605.19721), [code](https://github.com/terranovafr/LaGCO-RL) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-07-31

   *Franco Terranova, Guillermo Bernardez, Albert Cabellos-Aparicio, Nina Miolane, Abdelkader Lahmadi*

5. **⭐ConRep4CO: Contrastive Representation Learning of Combinatorial Optimization Instances across Types** ICLR, 2026. [paper](https://openreview.net/forum?id=OXRnvOOiAf), [code](https://github.com/Thinklab-SJTU/ConRep4CO) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-03-09

   *Ziao Guo, Yang Li, Shiyue Wang, Junchi Yan*

6. **Approximation algorithms for combinatorial optimization with predictions** ICLR, 2025. [paper](https://openreview.net/forum?id=AEFVa6VMu1)

   *Antonios Antoniadis, Marek Elias, Adam Polak, Moritz Venzin*

7. **Geometric Algorithms for Neural Combinatorial Optimization with Constraints** NeurIPS, 2025. [paper](https://openreview.net/forum?id=EPDLFWyNnF)

   *Nikolaos Karalias, Akbar Rafiey, Yifei Xu, Zhishang Luo, Behrooz Tahmasebi, Connie Jiang, Stefanie Jegelka*

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-03._
