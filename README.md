# NER_200

This is a repository with material for evaluating the Hunflair NER corpora on BioBERT

It provides the following: 
* Pre-trained weights BioBERT-Base v1.1 (+ PubMED 1M) 
* The NER corpora from HunFlair converted to a format compatible with BioBERT 
* Fine-tuned models where Hunflair corpora and BioBERT-Base v1.1 (+ PubMED 1M) has been used
* Results from ... ... 
* A filestructure and jupyter notebook adapted to be run on Google Colab

## Background

**BioBERT**
Please see the paper and git repository for description of BioBERT
* [BioBERT: a pre-trained biomedical language representation model for biomedical text mining](http://doi.org/10.1093/bioinformatics/btz682).
* [DMIS-Lab BioBERT](https://github.com/dmis-lab/biobert/blob/master/README.md)

**HunFlair**
Please see the paper and git repository for description of HunFlair
* [HunFlair: An Easy-to-Use Tool for State-of-the-Art Biomedical Named Entity Recognition](https://arxiv.org/abs/2008.07347)
* [FlairNLP HunFlair](https://github.com/flairNLP/flair/blob/master/resources/docs/HUNFLAIR.md)


## Setup

1. Download this repository to your local machine.
2. Enter your Google Drive and create a folder called NER_200.
3. Copy the downloaded material and put it in the NER_200 folder.
4. Download the wanted verision of BioBERT [here](https://github.com/dmis-lab/biobert/blob/master/README.md#download). Our results was given by BioBERT-Base v1.1 (+ PubMED 1M). Please note BioBERT-Large is too large for a free verision of Google Colab
5. Make sure the files are named accordingly with X replaced with correct number (For BioBERT-Base v1.1 (+ PubMed _**1M**_ ) : X = '1000000')
* bert_config.json 
* model.ckpt-X.data-00000-of-00001
* model.ckpt-X.index
* model.ckpt-X.meta
* vocab.txt


## Fine tuning

After setup, you can finetune.
1. 


