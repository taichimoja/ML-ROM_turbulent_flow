# ML-ROM_turbulent_flow
This repository contains the simple source codes of "Convolutional neural network and long short-term memory based reduced order surrogate for minimal turbulent channel flow," [Physics of Fluids, 33, 025116](https://aip.scitation.org/doi/10.1063/5.0039845) (Preprint: [arxiv:2010.13351 \[physics.flu-dyn\]](https://arxiv.org/abs/2010.13351))

DNS             |  ML-ROM
:-------------------------:|:-------------------------:
![DNS_5_105_axis](https://user-images.githubusercontent.com/78074953/106081079-a69a9980-615b-11eb-9c0e-f6cbf5499e08.gif)  |  ![ROM_1536](https://user-images.githubusercontent.com/78074953/106082050-57edff00-615d-11eb-94b2-e7f0e8482cd6.gif)

<div style="text-align: center;">Flow fields computed by direct numerical simulation (DNS) and predicted by ML-ROM.</div>

# Information
Author: Taichi Nakamura ([Keio University](https://kflab.jp/ja/))

This repository contains

1. Sample-code_CNN-AE.ipynb
1. Sample-code_LSTM.ipynb

For citations, please use the reference below:

> T. Nakamura, K. Fukami, K. Hasegawa, Y. Nabae, K. Fukagata,  
"Convolutional neural network and long short-term memory based reduced order surrogate for minimal turbulent channel flow,"  
[Physics of Fluids, 33, 025116 (2021).](https://aip.scitation.org/doi/10.1063/5.0039845)  

Authors provide no guarantees for this code. Use as-is and for academic research use only; no commercial use allowed without permission. The code is written for educational clarity and not for speed.

# Requirements
* Python 3.x  
* keras  
* tensorflow
* sklearn
* numpy
* pandas
