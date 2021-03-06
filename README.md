
# Compression via Gradient Flow Preservation

[![Python 3.7](https://img.shields.io/badge/Python-3.7-3776AB.svg?logo=python)](https://www.python.org/) [![PyTorch 1.4](https://img.shields.io/badge/PyTorch-1.4-EE4C2C.svg?logo=pytorch)](https://pytorch.org/docs/1.4.0/) [![MIT](https://img.shields.io/badge/License-MIT-3DA639.svg?logo=open-source-initiative)](LICENSE)

This repository is the **official** implementation of [Winning the Lottery Ahead of Time: Efficient Early Network Pruning](https://proceedings.mlr.press/v162/rachwan22a.html) published at ICML 2022.

### Setup

- Install virtualenv

> `pip3 install virtualenv`

- Create environment

> `virtualenv -p python3 ~/virtualenvs/EarlyCroP`

- Activate environment

> `source ~/virtualenvs/EarlyCroP/bin/activate`

- Install requirements:

> `pip install -r requirements.txt`

- If you mean to run the 'Tiny-Imagenet' dataset: download and unpack in `/gitignored/data/`, then replace CIFAR10 with TINYIMAGENET below to run. Additional datasets can be added in a similar way (Imagewoof, imagenette, etc.)

### Image Classification
To reproduce Image Classification results refer to [Image Classification](https://github.com/johnrachwan123/Early-Cropression-via-Gradient-Flow-Preservation/tree/main/Image%20Classification)

### NLP
To reproduce NLP results on the PSMM network refer to the folder [NLP](NLP)

### Cite
Please cite our paper if you use our code in your own work:

```reference
@InProceedings{earlycrop,
  title = 	 {Winning the Lottery Ahead of Time: Efficient Early Network Pruning},
  author =       {Rachwan, John and Z{\"u}gner, Daniel and Charpentier, Bertrand and Geisler, Simon and Ayle, Morgane and G{\"u}nnemann, Stephan},
  booktitle = 	 {Proceedings of the 39th International Conference on Machine Learning},
  year = 	 {2022},
  volume = 	 {162},
  series = 	 {Proceedings of Machine Learning Research},
  publisher =    {PMLR},
  }
```

### Licence

[MIT Licence](LICENSE) 
