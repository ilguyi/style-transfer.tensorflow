# Style Transfer with TensorFlow

This repository is a collection of various style-transfer models.


## Getting Started

### Prerequisites
* TensorFlow 1.10
  * vgg_19 pre-trained models
* Python 3.6
* Python libraries:
  * numpy, matplotlib, PIL
* Jupyter notebook
* OS X and Linux (Not validated on Windows)


## Models

### A Neural Algorithm of Artistic Style
* [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)
  * L. Gatys, A. Ecker, M Bethge
* The first paper about the neural style transfer 
* `ipynb code` [model01/01_style_transfer.ipynb](https://nbviewer.jupyter.org/github/ilguyi/style-transfer.tensorflow/blob/master/model01/01_style_transfer.ipynb)

#### Results
##### Tubingen
<div align="center">
<img src='./input_data/tubingen.jpg' height='250px'>
<img src='./results/tubingen_shipwreck_sw_0.05_cs_512_ss_512_tv_0.0001.jpg' height='250px'>
<img src='./results/tubingen_Gogh_The_Starry_Night_sw_0.01_cs_512_ss_512_tv_0.0001.jpg' height='250px'>
<img src='./results/tubingen_Munch_The_Scream_sw_0.01_cs_512_ss_512_tv_1e-05.jpg' height='250px'>
<img src='./results/tubingen_seated-nude_sw_0.05_cs_512_ss_512_tv_0.0001.jpg' height='250px'>
<img src='./results/tubingen_woman-with-hat-matisse_sw_0.1_cs_512_ss_512_tv_0.0001.jpg' height='250px'>
</div>





## Author
* **Il Gu Yi**
