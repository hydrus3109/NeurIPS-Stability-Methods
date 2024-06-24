# A Novel Review of Stability Techniques for Improved Privacy-Preserving Machine Learning

The source code for NeurIPS submission A Novel Review of Stability Techniques for Improved Privacy-Preserving Machine Learning.

## Description

This repository contains the source code and data used in the NeurIPS submission A Novel Review of Stability Techniques for Improved Privacy-Preserving Machine Learning. Code is organized into 5 sections, 4 containing code used to generate results in the paper, and a miscellaneous folder for other methods tested that don't make it into the paper. For more details, please see the full paper at https://arxiv.org/abs/2406.00073. Code notebooks are split into baselines and experimentation for both the Resenet20 and Linear Regression testing, with subfolders as necessary within each folder. You can find notebook correlating to each experiement in the fodlers by their name, with all notebooks in baseline folders as just experimentation playgrounds that can also be used to generate baseline results. The transformed data used for the linear regression section of the paper can be found in the following drive folder:

https://drive.google.com/drive/folders/1MlqWEfN_GFIue7iw-n6mz-AFzksqg4is?usp=sharing
## Getting Started

### Dependencies

* Pytorch
* Numpy
* Opacus(for some files)
* scipy
* PIL


### Executing programs

* All experiments and files can be run indepedently, either locally or though a service like Google Colab
* for experiements that Involve transformed data, download the data and load through its path
* Training results will save as Numpy files, which can then be loaded as comparison



## Authors

Aidan Gao, https://github.com/hydrus3109

Coleman Duplessie, https://github.com/ColemanDuPlessie



## Acknowledgments

This research was completed as part of the MIT PRIMES program. We were mentored by Dr. Hanshen Xiao, who created the PAC privacy framework, taught us the basics of privacy in machine learning, and introduced us to the state-of-the-art. Unless otherwise noted, all code here is our own.
