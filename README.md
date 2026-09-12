# Retinal vessel segmentation

## Project overview
This repository contains the project developed for the **Computer Vision** Project Work exam during my Master's Degree.

The project was carried out in the **medical computer vision domain** and focused on the automatic analysis of retinal fundus images. The main objective was to develop a pipeline capable of:

- automatically **segmenting retinal blood vessels from fundus screening images**;
- **computing clinically relevant geometric metrics**: Vessel Tortuosity and Arteriolar-to-Venular Ratio (AVR).

These measurements can provide useful information for the **early detection of retinal vascular abnormalities and retinopathies**.

## Datasets
The available data consisted of three different retinal datasets, each characterized by different image properties, acquisition conditions and annotation characteristics.

A major challenge was the limited number of available images, which required careful consideration of preprocessing, data augmentation, training and evaluation strategies.

The developed pipeline therefore had to account for:

- different image characteristics across datasets;
- limited training samples;
- class imbalance between vessel and background pixels;
- fine and low-contrast vessels;
- noise and illumination variations;
- preservation of vessel topology for subsequent geometric analysis.

Note: dataset images and annotations are not included in this repository. Please refer to the original dataset sources and their respective licenses for access and usage conditions.

## Repository content
- *Segmentazione_vasi_retinici.ipynb*: the code developed for the project, including the image processing, vessel segmentation and geometric analysis steps.
- *Segmentazione_vasi_retinici.pdf*: the presentation I used to explain the project during the exam, including the approach, experiments and results.

## Note
This project has been developed as part of my Master's Degree. I am publishing the repository as part of my portfolio, only to show recruiters some of the computer vision work I have done during my studies.
**The content of this repository may not be copied, modified, redistributed, reused, or incorporated into other projects without my explicit prior consent.**

