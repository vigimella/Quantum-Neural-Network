# QUIP
QUantum Image Processing

This repository enables the execution of a Deep Learning algorithm using a Quantum Neural Network.

## Usage

```bash
cd docker

./build_image.sh
```
To run container, run the following command

```bash

./run_contained.sh
```
To execute experiments, run the following command
```bash

python3 main.py -d dataset_name -i image_dimension -e num_epochs -b batch_size -r learning_rate -t trashold

```

Files such as plots, confusion matrix, training and validation results, and execution time are saved after execution in a folder called "exp_archive".
## Authors

- [@Vigimella](https://www.github.com/vigimella)
- [@FrancescoMercaldo](https://github.com/FrancescoMercaldo)
- [@Djack1010](https://github.com/Djack1010)

If you are using this repository, please cite our work by referring to our publications (BibTex format):

```commandline
@Article{app122312025,
    AUTHOR = {Mercaldo, Francesco and Ciaramella, Giovanni and Iadarola, Giacomo and Storto, Marco and Martinelli, Fabio and Santone, Antonella},
    TITLE = {Towards Explainable Quantum Machine Learning for Mobile Malware Detection and Classification},
    JOURNAL = {Applied Sciences},
    VOLUME = {12},
    YEAR = {2022},
    NUMBER = {23},
    ARTICLE-NUMBER = {12025},
    URL = {https://www.mdpi.com/2076-3417/12/23/12025},
    ISSN = {2076-3417},
    DOI = {10.3390/app122312025}
    }
```

## Contributing

The authors would like to thank the 'Trust, Security and Privacy' research group within the [Institute of Informatics and Telematics](https://www.iit.cnr.it/) (CNR - Pisa, Italy), that support their researches.

In this code we built a Quantum Neural Network (QNN). It is similar to the approach used in [Farhi et al](https://arxiv.org/pdf/1802.06002.pdf)

In addition we were inspired by [MNIST classification](https://colab.research.google.com/github/tensorflow/quantum/blob/master/docs/tutorials/mnist.ipynb#scrollTo=udLObUVeGfTs)
