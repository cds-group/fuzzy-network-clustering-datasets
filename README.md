
## Fuzzy clustering of networks

Network datasets and software links used in [1], for the evaluation of fuzzy clustering methods for graph clustering.

### Data description

#### Synthetic datasets
1. LFR networks: <br /> The [LFR](/LFR/) dataset was generated using the Lancichinetti–Fortunato–Radicchi (LFR) benchmark method with mixing parameters (μ) 0.1, 0.5 and 0.8. O.<br />
#classes = 3,  #graphs = 300 (100 with 0.1μ - class1, 100 with 0.5μ - class2 and 100 with 0.8μ),  #nodes = 100.
	
2. MREG networks: <br />
The [MREG](/MREG/) was generated using the Multiple Random Eigen Graphs (MREG) model defined in [4].<br />
#classes = 2,  #graphs = 200 (100 in each class, graphJE_1 to 100 - class1, graph_JE101 to 200 - class2),  #nodes = 100
   
#### Real-world datasets

1. FAO Climate Correlation networks  :<br />The  dataset  contains  140  networks  where each  network  represents  a  country.  Each graph is made up of 21 nodes which represent  variables  related  to  sustainability,  climate  change,  economic and production indicators (downloaded from the FAOSTAT database: https://www.fao.org/faostat/en/#data).[FAO_Climate_Corr_Indicators](/FAO_Climate_Corr_Indicators). See [README.txt](/FAO_Climate_Corr_Indicators/README.txt).


### Links to software

1. Distribution-based graph distance measures: https://github.com/cds-group/GraphDistances [2]
2. Autoencoder: https://github.com/leoguti85/GraphEmbs [3]
3. JointEmbedding (Matrix factorization): https://github.com/jesusdaniel/JEG [4]

### References
[1] Bombelli, I., Manipur, I., Ferraro, M.B. and Guarracino, M.R., On clustering ensembles of networks using a fuzzy approach, Submitted Manuscript

[2] Granata, I., Guarracino, M.R., Kalyagin, V.A., Maddalena, L., Manipur, I. and Pardalos, P.M., 2020. Model simplification for supervised classification of metabolic networks. Annals of Mathematics and Artificial Intelligence, 88(1), pp.91-104.
https://link.springer.com/article/10.1007/s10472-019-09640-y

[3] Gutiérrez-Gómez, L. and Delvenne, J.C., 2019. Unsupervised network embeddings with node identity awareness. Applied Network Science, 4(1), p.82. https://link.springer.com/article/10.1007/s41109-019-0197-1

[4] Wang, S., Arroyo, J., Vogelstein, J.T. and Priebe, C.E., 2019. Joint embedding of graphs. IEEE Transactions on Pattern Analysis and Machine Intelligence. https://ieeexplore.ieee.org/abstract/document/8889404

#### <sup>**</sup>For more graph related work visit our github page at [cds-group](https://github.com/cds-group/)
