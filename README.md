# Transformer Trainer example

Notebook example showing how to fine-tune Transformer models using the Transformer Trainer class.

## Usage

Install the conda environment with

    conda env create -f environment.yml

then log into the environment

    conda activate transformers-trainer

and run Jupyter notebooks with

    CUDA_VISIBLE_DEVICES=X jupyter notebook

where `X` is the number of the GPU you want to use for training.

## Index of contents

* `environment.yml`: anaconda environment file
* `transformers-multiclass.ipynb`: notebook showint the usage of Transformer Trainer for a multiclass problem
* `simplify_labels.ipynb`: notebook used to simplify the dataset from multilabel to multiclass
* `data`: folder with multilabel and multiclass versions of the dataset
