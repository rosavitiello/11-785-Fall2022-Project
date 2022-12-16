# 11-785-Fall2022-Project
Introduction to Deep Learning Semester project on domain adaptation for accented speech

This GitHub Repo is structured into three folders: `dataloader`, `inference`, and `training`. Each of which contain Python notebook scripts which can be run to reproduce our experiments in speech emotion recognition, as outlined in our final report.

In `training` and `inference`, you will find four notebooks that run training and inference for the following models. Relevant dependencies must be installed:
* XLSR for SER
* HuBERT for SER
* Wav2Vec2.0 for SER
* Domain Adversarial Neural Network for SER

We have tested the above models on the following GPUs:
* 40 GB NVIDIA A6000
* 40 GB A100 Google Colab Instance
