# IITI_SOC_ML9
Grammer Auto correct

This Project is a Part of IITISoC'24

## PROJECT’s INTENT 
Building a model to take English sentences as input from the user and analyse them and identify the grammatical error's and rectify them and return sentence with correct grammar and also suggest's a impressive way of writing those sentences which have a better impact on reader.

## Features
- Error	Detection:	Identiﬁes	various	types	of grammatical	errors	such	as	punctuation	mistakes,subject-verb  agreement  issues,  incorrect  word usage, etc
- Performance:  Achieves  high  accuracy  in  error detection and correction through pre-trained ﬁne- tuning.
- Modiﬁcations:    Paraphrase    text,    Improved grammar  text,  Simpliﬁed  text,  Cohesivetext,  and Neutralized text.

## Previous methods used:
### 1.build and trained a transformer from  scratch with the datasets
first we tried building a transformer from scratch with the datasets but it was taking a lot time time to train and neither was giving good results.
### 2.Using already pretrained and fine-tuned models
next we tried to use some pretrained and fine-tuned models like - [pszemraj/flan-t5-large-grammar-synthesis](https://huggingface.co/pszemraj/flan-t5-large-grammar-synthesis),[vennify/t5-base-grammar-correction](https://huggingface.co/vennify/t5-base-grammar-correction),[grammarly/coedit-large](https://huggingface.co/grammarly/coedit-large) but these were quiete large to load and many times the RAM of the computer was crashing while using them on our local machine and even on google colab.
### 3.Fine-tuning pretrained models 
we researched about different pre-trained transformer and we found that for text-to-text genearation related work like reasoning ,translating and answering T5 was good but due to limitations of computer resources we used t5 small model for fine-tuning on the datasets.

 
## Model used
### 1. T5 Small Fine-tuned on grammarly coedit 
The T5 (Text-To-Text Transfer Transformer) model is a transformer-based model introduced by Google Research, capable of performing a wide range of NLP tasks using a unified text-to-text framework. This particular instance of the T5 model is based on the "small" variant, which has 60M parameters.
For ﬁne-tuning the coedit dataset was directly imported from hugging face , then data was preprocessed and padded. Then the tokenizer and model was imported from hugging face library and after ﬁne-tuning, the model was saved, for using it for future purposes.

### 2. T5 Small Fine- tuned on custom build dataset
The sentences were searched from various english books, There  were  exercise  regarding  ﬁnding  the  grammatical error in the sentences and then it was made into csv ﬁle and then used for training purposes.


Our final code is as follows:\
[https://colab.research.google.com/drive/1NcwPBNP96FExdc4dxDuji3l3rSzjljTK?usp=sharing](https://colab.research.google.com/github/varshneyanushka/IITI_SOC_ML9/blob/main/Mahabharat.ipynb)

[Powerpoint presentation link](https://github.com/varshneyanushka/IITI_SOC_ML9/blob/main/assets/iitisoc9.pptx)

## Sample Screenshots
!["C:\Users\Vikash kumar singh\Desktop\WhatsApp Image 2024-07-27 at 00.01.41_fa68e742.jpg"](https://github.com/varshneyanushka/IITI_SOC_ML9/blob/main/assets/WhatsApp%20Image%202024-07-27%20at%2000.01.41_fa68e742.jpg)



## Contributors
- [Shreeyut Maheswari](https://github.com/search?q=shreeyut1905&type=users)
- [Srikanth Chebolu](https://github.com/search?q=Srikanth1234567808&type=users) 
- [Piyush Tiwari](https://github.com/search?q=Piyush867583&type=users)
- [Vikash Kumar Singh](https://github.com/search?q=Vikas1177&type=users)

## Mentor
- [Anushka Varshney](https://github.com/search?q=varshneyanushka&type=users)

## Acknowledgments
- Google Research: For developing and releasing the T5 model architecture.
- JFLEG: For providing the datasets used for pretraining.

## Refrences
- [Numpy documentation](https://numpy.org/doc/)
- [Pandas documentaion](https://pandas.pydata.org/docs/)
- [Tensorflow documentataion](https://www.tensorflow.org/api_docs)
- [Pytorch documentation](https://pytorch.org/docs/stable/index.html)
- [Kaggle](https://www.kaggle.com/)
- [PyTorch implementation of the Transformer model in "Attention is All You Need" ](https://github.com/jadore801120/attention-is-all-you-need-pytorch.git)
- [Huggingface dataset- liweili c4_200m](https://huggingface.co/datasets/liweili/c4_200m)
- [Huggingface  fine-tuned version of flan-t5-large-grammar-synthesis  for grammar correction on an expanded version of the JFLEG dataset](https://huggingface.co/pszemraj/flan-t5-large-grammar-synthesis)
- [Github- Gramformer](https://github.com/PrithivirajDamodaran/Gramformer)
- [TextBlob: Simplified Text Processing](https://textblob.readthedocs.io/en/dev/)
- [Huggingface transformers model- t5](https://huggingface.co/docs/transformers/en/model_doc/t5)
- [Github- Facebook-bart-cnn](https://github.com/inferless/Facebook-bart-cnn)





