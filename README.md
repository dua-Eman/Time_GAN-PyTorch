# TimeGAN for Multivariate Time-Series
This project implements TimeGAN in PyTorch to generate synthetic household electricity consumption data.
## Acknowledgements
This repository contains a fully working implementation of **TimeGAN** applied to the **Household Electric Power Consumption** dataset. The project was developed and successfully executed by:

- **Dua Eman**
- **Rabia Ejaz**
- **Anila Khan**
  
as part of the **Big Data Analytics – CEP 2 Experimental Study**.

Special thanks to the supporting faculty and the online research community.
##  Project Overview
The goal of the project was to:
- Train TimeGAN on a large real-world time-series dataset  
- Evaluate the model using predictive & discriminative metrics  
- Visualize similarity using PCA and t-SNE  
- Provide a clean, reproducible codebase for future research
  
## Steps:
1. Load dataset
2. Preprocess & Normalize
3. Build sequences
4. Train TimeGAN
5. Generate synthetic data
6. Evaluate: Discriminative, Predictive, PCA, t-SNE

## Requirement
python >= 3.9.15

pytorch >= 1.13.1

cuda >= 11.7.1

numpy >= 1.23.4

pandas >= 1.5.3

matplotlib >= 3.6.2

## Reproducibility
This repository is fully plug-and-play
- Clone repository
- Upload dataset
- Run the notebook

## References

Original PyTorch Rebuild:
https://github.com/AlanDongMu/TimeGAN_PytorchRebuild.git

TimeGAN Paper:
"Time-series Generative Adversarial Networks" — Yoon et al., NeurIPS 2019
https://papers.nips.cc/paper/2019/file/c9efe5f26cd17ba6216bbe2a7d26d490-Paper.pdf
All results will regenerate identically.

**⭐ If you found this project useful, give the repo a star!**
