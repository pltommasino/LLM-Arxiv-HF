# LLM-Arxiv-HF

## PRESENTATION

The purpose of this project is to analyse how LLM works and how to train them. In particular: to download a dataset from HuggingFace, choose a pre-processing, choose 2 models, and fine-tune this task. One fine-tuning has to be done without using LoRa, while the other has to be done using LoRa and everything has to run within the Colab limits. This project was carried for Advanced Data Mining & Language Technology course in Sapienza.

## CODE

For the planned delivery, the project required only one file (in the `/code` folder): `main.ipynb`

This project have a very high computational cost, so it was split and run several times in order to obtain the results you will see. You can therefore see within each section, a new loading of the packages you have already encountered previously.

## DATA

As mentioned before, the dataset was downloaded from HuggingFace directly to the main file where you can see the work done. For further details see [HF dataset website](https://huggingface.co/datasets/taesiri/arxiv_qa)