# Overview
This repository contains code to reproduce the main results for the paper [Consistent Birdsong Syllable Segmentation Using Deep Semi-Supervised Learning](https://www.researchgate.net/publication/373723820_CONSISTENT_BIRDSONG_SYLLABLE_SEGMENTATION_USING_DEEP_SEMI-SUPERVISED_LEARNING#fullTextFileContent). All the main experiments are organized in one notebook, you can jump to the desired section if you use jupyter-lab instead of the jupyter-notebook (it shows the links to header of sections and you can select them instead of scrolling).

In this paper, we argue that to prevent inconsistencies in birdsong annotation we require unsupervised and fully automated annotation methods. However, to cluster the syllables, one first requires a robust segmentation. The prevalent segmentation approaches are based on thresholding methods, which are brittle and require extensive expertise. We proposed a data efficient pipeline based on deep semi-supervised learning that addresses most of the challenges in segmentation step. Moreover, this type of models can generalize and be used for the whole species of birds, and the same model works on any species without hyper-parameter tuning.

# Dataset
You need to download these datasets and have them locally. These are not ours, please cite them independently and see their licensing and manuals. Many thanks to the authors of these datasets and related works.

[Bengalese Finches](https://figshare.com/articles/dataset/Bengalese_Finch_song_repository/4805749)

[Canaries](https://datadryad.org/stash/dataset/doi:10.5061/dryad.xgxd254f4)

# External code
We used this code for some thresholding segmentation algorithms and data loading for Bengalese finches:

[evfuncs](https://github.com/NickleDave/evfuncs): 

# Disclaimer:
This code is only published for research and educational purposes. We are not publishing a software here, and the responsibility of using it is on yourself.
