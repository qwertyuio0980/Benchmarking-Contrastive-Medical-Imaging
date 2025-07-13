# Benchmarking-Contrastive-Medical-Imaging

This repository hosts the experimental code developed for my MSc thesis: Benchmarking Contrastive Learning for Multimodal Medical Imaging.

The code is used to benchmark three SOTA contrastive learning frameworks (SimCLR, MoCo, BYOL) for representation learning in breast cancer imaging. Experiments were conducted on publicly available breast imaging datasets (not redistributed here) and supports pretraining, fine-tuning, and evaluation of models for both multiclass classification and binary semantic segmentation tasks, leveraging both ultrasound and mammography data. The modular design of the pipeline allows easy integration of additional contrastive frameworks, datasets, or downstream tasks, enabling researchers to quickly extend and adapt the experiments for new use cases or domains.

## Contents

- `Thesis_Benchmarking_MartimSilva.ipynb`: The primary Jupyter Notebook containing the experimental code and analysis.
- `requirements.txt`: A list of all necessary Python dependencies to run the NoteBook file.

## Credits

In this repository two functions were used to support preprocessing of the INbreast dataset, these were adapted from:

- [pablogiaccaglia/Breast-Cancer-Segmentation-Datasets](https://github.com/pablogiaccaglia/Breast-Cancer-Segmentation-Datasets/blob/master/INbreast/refactorINbreast.py) by Pablo Giaccaglia
