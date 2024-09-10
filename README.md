# Direction-based-BiTSE
This repository provides the implementation for the paper "Leveraging Boolean Directivity Embedding for Binaural Target Speaker Extraction" by Yichi Wang, Jie Zhang, Chengqian Jiang, Weitai Zhang, Zhongyi Ye, Lirong Dai.

# Dataset
We utilized the dataset generation method described in https://github.com/huangzj421/BinauralWSJ0Mix.

# BDE(Boolean Directivity Embedding) feature
The BDE feature is extracted in NBSS.py

# Spatiotemporal features
The spatiotemporal features(CDF, SDF, delta STFT proposed in our previous work "A Study of Multichannel Spatiotemporal Features and Knowledge Distillation on Robust Target Speaker Extraction" https://ieeexplore.ieee.org/document/10446870) are extracted in spatial_fea.py

# Model
For the backbone network, we used the NBC2 small available at https://github.com/audio-westlakeu/nbss.

#  Paradigm of the proposed BiTSE
![Alt text](images/framework.png)

# Results 
![Alt text](images/table1.png)
![Alt text](images/table2.png)
