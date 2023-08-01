# GCRDN
This is a repository for releasing a PyTorch implementation of our work  [GCRDN: Global Context-Driven Residual Dense Network for Remote Sensing Image Super-Resolution](https://ieeexplore.ieee.org/abstract/document/10115440). **We also provide more than ten advanced models for experimental comparision.**

Please cite our paper if you find it is useful for your research.

```
@ARTICLE{10115440,
  author={Sui, Jialu and Ma, Xianping and Zhang, Xiaokang and Pun, Man-On},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={GCRDN: Global Context-Driven Residual Dense Network for Remote Sensing Image Superresolution}, 
  year={2023},
  volume={16},
  number={},
  pages={4457-4468},
  doi={10.1109/JSTARS.2023.3273081}}
```

# Usage

Training: python src/main.py

Testing: put pre-trained model into 'model' and python test.py

The project also contains serval methods except from gcrdn including rdn, nlsn, rcan, dbpn, edrn, esrt, swinir, transms and rrdb.

The code of gcrdn is presented at src/model/gcrdn/mymodel.py
