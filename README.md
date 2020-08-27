# Singlish Manglish NLP Resources

## Getting started
1. Install [anaconda or miniconda](https://docs.anaconda.com/anaconda/install/)
2. Install the requirements `conda env create -f environment.yml`

## Masked Language Modelling
1. SingBERT models mask-filling- BERT [base](https://huggingface.co/zanelim/singbert) and [large](https://huggingface.co/zanelim/singbert-large-sg) models with pre-training finetuned on singlish corpus. Its efficacy of masked language modelling (filling up blanks or masks between words in a sentence) is demonstrated [here](masked_language_modelling/sing_bert.ipynb).

## Text Summarization
1. SingBERT models extractive summarization demonstrated [here](summarization/singbert_extractive_summarization.ipynb).

## Text Classification
1. Classification of the speaker/user of SMS messages from the [NUS SMS Corpus](https://github.com/kite1988/nus-sms-corpus), with the processed json data obtained from [Kaggle](https://www.kaggle.com/rtatman/the-national-university-of-singapore-sms-corpus) demonstrated [here](text_classification/sms_classification.ipynb)
