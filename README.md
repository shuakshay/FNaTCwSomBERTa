# SomBERTa: Somali-Specific Language Model

This repository contains the official release of the model [**"SomBERTa"**](https://huggingface.co/shuakshay/SomBERTa) and its accompanying resources such as pre-training Somali corpus and fine-tuning datasets introduced in the paper titled [**"Detection of Somali-written Fake News and Toxic Messages on the Social Media Using Transformer-based Language Models"**](https://arxiv.org/abs/2503.18117) published in *Findings of the Association for Computational Linguistics: ACL 2025*. It contains two folders: data and code respectively housing the used pre-training and fine-tuning datasets, and their corresponding implementations.

Please note that the raw social media fake news and toxicity datasets are not included in the resource for privacy and ethical reasons. If you require these specific datasets for relevant Somali NLP research, please contact us at sltg@just.edu.so with a brief explanation of why you need it and how you would use it, then we will send you the relevant application forms.

##  Highlights

- First monolingual BERT-like model trained for the Somali language.
- Tasks benchmarked: Fake News Classification, Toxicity Detection (Binary & Multiclass), News Topic Classification.
- Outperforms AfriBERTa, XLM-R, and other multilingual models in task-specific evaluations.

## Setup

For installing the necessary requirements, use the following bash snippet
```bash
$ git clone https://github.com/shuakshay/FNaTCwSomBERTa
$ cd FNaTCwSomBERTa/
$ conda create python==3.7.9 pytorch==1.8.1 torchvision==0.9.1 torchaudio==0.8.0 cudatoolkit=10.2 -c pytorch -p ./env
$ conda activate ./env # or source activate ./env (for older versions of anaconda)
$ bash setup.sh 
```
* Use the newly created environment for running the scripts in this repository.

## Citation
If you use any of the datasets, model or code modules, please cite the following paper:
```
Mohamed, M.A., Ahmed, S.D., Isse, Y.A., Mohamed, H.M., Hassan, F.M. and Assowe, H.A., 2025. Detection of Somali-written Fake News and Toxic Messages on the Social Media Using Transformer-based Language Models. arXiv preprint arXiv:2503.18117.
```
