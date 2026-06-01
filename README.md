This repository provides the processed feature data used in our study. The datasets are organized for academic research, experimental reproducibility, and comparison with related incomplete multi-view clustering methods.

The datasets included in this repository are derived from publicly available benchmark datasets or commonly used processed multi-view datasets. This repository does not claim ownership of the original datasets. The original ownership, copyright, and usage restrictions remain with their respective creators, publishers, or distributors.

## Overview

This repository contains the following processed datasets:

| Dataset     | Description                                                                  | Original Source                                        |
| ----------- | ---------------------------------------------------------------------------- | ------------------------------------------------------ |
| USPS-MNIST  | A processed handwritten digit dataset derived from USPS and MNIST            | USPS and MNIST                                         |
| Prokaryotic | A processed multi-view prokaryotic species dataset                           | ProTraits / Multi-view LRSSC                           |
| ProteinFold | A processed protein fold prediction dataset used in multiple kernel learning | UCSD MKL Repository                                    |
| UCI-digit   | A processed handwritten digit feature dataset                                | UCI Multiple Features                                  |
| Handwritten | A processed handwritten numeral feature dataset                              | UCI Multiple Features / Handwritten numerals benchmark |
| BDGP        | A processed Drosophila embryo image feature dataset                          | Berkeley Drosophila Genome Project                     |
| CCV         | A processed consumer video feature dataset                                   | Columbia Consumer Video Database                       |

## Important Notes

The files provided in this repository are processed feature data used for experimental reproducibility.

## Dataset Sources

### 1. USPS-MNIST

The USPS-MNIST dataset used in this repository was constructed based on two publicly available handwritten digit datasets: USPS and MNIST.

The USPS dataset was originally introduced by Hull:

> Hull, J. J. A database for handwritten text recognition research. *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 16(5), 550–554, 1994. https://doi.org/10.1109/34.291440

The MNIST dataset was originally introduced by LeCun et al.:

> LeCun, Y., Bottou, L., Bengio, Y., and Haffner, P. Gradient-based learning applied to document recognition. *Proceedings of the IEEE*, 86(11), 2278–2324, 1998. https://doi.org/10.1109/5.726791

The USPS-MNIST data provided in this repository are processed feature data used in our experiments for academic research and reproducibility.

### 2. Prokaryotic

The Prokaryotic dataset is a processed multi-view dataset derived from prokaryotic species data. It has been used in multi-view clustering studies, where each species is represented by heterogeneous views, such as textual and genomic feature representations.

The original biological data are related to the ProTraits resource:

> Brbić, M., Piškorec, M., Vidulin, V., Kriško, A., Šmuc, T., and Supek, F. The landscape of microbial phenotypic traits and associated genes. *Nucleic Acids Research*, 44(21), 10074–10090, 2016. https://doi.org/10.1093/nar/gkw964

A commonly cited multi-view clustering source is:

> Brbić, M., and Kopriva, I. Multi-view Low-rank Sparse Subspace Clustering. *Pattern Recognition*, 73, 247–258, 2018. https://doi.org/10.1016/j.patcog.2017.08.024

The Prokaryotic data provided in this repository are processed feature data used for multi-view clustering experiments.

### 3. ProteinFold

The ProteinFold dataset is a protein fold prediction dataset used in multiple kernel learning and multi-view learning studies.

Original source: http://mkl.ucsd.edu/dataset/protein-fold-prediction/

A commonly cited related paper is:

> Ding, C. H. Q., and Dubchak, I. Multi-class protein fold recognition using support vector machines and neural networks. *Bioinformatics*, 17(4), 349–358, 2001. https://doi.org/10.1093/bioinformatics/17.4.349

The dataset has also been used in multiple kernel learning studies, such as:

> Gönen, M., and Alpaydın, E. Multiple kernel learning algorithms. *Journal of Machine Learning Research*, 12, 2211–2268, 2011.

The ProteinFold data provided in this repository are processed feature data used for experimental reproducibility.

### 4. UCI-digit

The UCI-digit dataset used in this repository is derived from the Multiple Features dataset in the UCI Machine Learning Repository. The original dataset contains handwritten numerals represented by multiple feature sets.

Original source: https://archive.ics.uci.edu/dataset/72/multiple+features

The processed UCI-digit data provided in this repository are used for multi-view clustering experiments.

### 5. Handwritten

The Handwritten dataset used in this repository is a processed handwritten numeral feature dataset. It is commonly used in multi-view clustering studies and is typically derived from handwritten digit feature representations, such as the UCI Multiple Features dataset.

Original source: https://archive.ics.uci.edu/dataset/72/multiple+features

The processed Handwritten data provided in this repository are used for multi-view clustering experiments.

### 6. BDGP

The BDGP dataset is derived from resources provided by the Berkeley Drosophila Genome Project. It has been widely used as a benchmark dataset in multi-view clustering studies.

Original source: https://www.fruitfly.org/

The BDGP data provided in this repository are processed feature data used for academic research and experimental reproducibility.

### 7. CCV

The CCV dataset used in this repository was derived from the Columbia Consumer Video Database. The original CCV database contains consumer videos collected from YouTube, together with annotations, standard training/testing partitions, and audio/visual feature representations.

Original source: https://www.ee.columbia.edu/ln/dvmm/CCV/

In this repository, we only provide the processed feature representations used in our experiments for academic research and reproducibility purposes.

## Data Availability Statement

The processed datasets used and analysed in our study are available in this GitHub repository. These datasets were derived from publicly available benchmark datasets or commonly used processed multi-view datasets, including USPS-MNIST, Prokaryotic, ProteinFold, UCI-digit, Handwritten, BDGP, and CCV.

Users of these processed datasets should cite the original dataset papers or source websites listed above. The processed data are provided for academic research and experimental reproducibility purposes only.


## License and Terms of Use

This repository is released for academic research and reproducibility purposes only.

The processed datasets in this repository are derived from or based on existing public benchmark datasets. The original ownership, copyright, and usage restrictions of the source datasets remain with their respective creators, publishers, or distributors.

Users are responsible for ensuring that their use of these datasets complies with the terms and conditions of the original data sources.

If any dataset provider requests modification or removal of related processed data, please contact the repository maintainer.

## Contact

For questions about the processed datasets in this repository, please contact the corresponding author of the paper.
