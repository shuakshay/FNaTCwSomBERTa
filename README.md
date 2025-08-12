# SomBERTa: Somali-Specific Language Model

This repository contains the official release of the model **"SomBERTa"** and associated downstream fine-tuning code and datasets introduced in the paper titled [**"Detection of Somali-written Fake News and Toxic Messages on the Social Media Using Transformer-based Language Models"**](https://arxiv.org/abs/2503.18117) published in *Findings of the Association for Computational Linguistics: ACL 2025*

SomBERTa is a monolingual BERT-based transformer language model trained on a diverse Somali corpus, fine-tuned for key downstream tasks such as fake news detection, toxicity classification, and news topic classification. This repository provides resources, datasets (if publicly allowed), code, and notebooks to replicate the pretraining and fine-tuning of SomBERTa.

##  Highlights

- First monolingual BERT-like model trained for the Somali language.
- Tasks supported: Fake News Classification, Toxicity Detection (Binary & Multiclass), News Topic Classification.
- Outperforms AfriBERTa, XLM-R, and other multilingual models in task-specific evaluations.

## Setup

For installing the necessary requirements, use the following bash snippet
```bash
$ git clone https://github.com/csebuetnlp/banglabert
$ cd banglabert/
$ conda create python==3.7.9 pytorch==1.8.1 torchvision==0.9.1 torchaudio==0.8.0 cudatoolkit=10.2 -c pytorch -p ./env
$ conda activate ./env # or source activate ./env (for older versions of anaconda)
$ bash setup.sh 
```
* Use the newly created environment for running the scripts in this repository.

## 📦 Requirements

Install the required packages with:

```bash
pip install -r requirements.txt

@article{somberta2025,
  title={Detection of Somali-written Fake News and Toxic Messages on Social Media Using Transformer-based Language Models},
  author={Mohamed, Muhidin A. and Ahmed, Shuab D. and others},
  year={2025},
  journal={Under Submission},
  url={https://github.com/shuakshay/FNaTCwSomBERTa}
}

