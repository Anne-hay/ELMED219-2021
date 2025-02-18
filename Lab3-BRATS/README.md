# Lab 3: BRATS and multimodal MRI

This lab will introduce multiparametric / multspectral MRI, the concepts of noise and contrast-to-noise ratio (CNR). It will also introduce **supervised learning** (tissue classification) of the head based on four-channel MRI recordings and manual delination of six different tissue types (or labels: AIR, GM, WM, CSF, MUS, FAT) using **K-nearest neighorhood (KNN) classification** in 4D feature space [1]. 

It will further introduce a multimodal dataset from the [BRATS](https://www.med.upenn.edu/cbica/brats2020/previous.html) (Multimodal Brain Tumor Segmentation) challenge provided by [TCIA](https://www.cancerimagingarchive.net) / [TCGA-GBM](https://wiki.cancerimagingarchive.net/display/Public/TCGA-GBM) (The Cancer Imaging Archieve / The Cancer Genome Atlas Glioblastoma Multiforme) and demonstrate **deep learning tumor segmentation** using [HD-GLIO](https://github.com/NeuroAI-HD/HD-GLIO) [2]. 

Finally, we introduce **unsupervised learning** (K-means clustering) of these multimodal MRI data using tools from `scikit-learn` to "dissect" the tumor region [3].


## Slides

## Slides and video recordings

[Slides-ELMED219-Lab3-BRATS-and-multimodal-MRI](https://docs.google.com/presentation/d/e/2PACX-1vTAsaZCQpvCk6zSlrYqzBVyNLIw-AV6vqM09_HB4ItVKDCeo8ckhsggU4plwgWeeQR5jMvt-LmeiJZq/pub?start=false&loop=false&delayms=3000)

[Video-ELMED219-Lab3-Lecture-Multimodal MRI](https://youtu.be/CegDkIi2JrI)

[Video-ELMED219-Lab3-Lab-Multimodal MRI](https://youtu.be/feSbu4dWdfE)

## Jupyter notebooks

- [1] [`ELMED219-Lab3-mri-multispectral-KNN-segm.ipynb`](https://nbviewer.jupyter.org/github/MMIV-ML/ELMED219-2021/blob/main/Lab3-BRATS/ELMED219-Lab3-mri-multispectral-KNN-segm.ipynb) 
- [2] [`ELED219-Lab3-glioma-segm-hd-glio-tcga-06-1802.ipynb`](https://nbviewer.jupyter.org/github/MMIV-ML/ELMED219-2021/blob/main/Lab3-BRATS/ELMED219-Lab3-glioma-segm-hd-glio-tcga-06-1802.ipynb)
- [3] [`ELMED219-Lab3-glioma-unsupervised-segm-K-means.ipynb`](https://nbviewer.jupyter.org/github/MMIV-ML/ELMED219-2021/blob/main/Lab3-BRATS/ELMED219-Lab3-glioma-unsupervised-segm-K-means.ipynb)

## Your turn! 

The notebooks have several small excerices and code completion challenges (with solutions) and encourage experiments with the ML models and their (hyper)parameters.
