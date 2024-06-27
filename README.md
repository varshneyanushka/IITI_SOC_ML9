# IITI_SOC_ML9
Grammer Auto correct

This Project is a Part of IITISoC'24

## PROJECT’s INTENT 
Building a model to take English sentences as input from the user and analyse them and identify the grammatical error's and rectify them and return sentence with correct grammar and also suggest's a impressive way of writing those sentences which have a better impact on reader.

## Features
- Error Detection: Identifies various types of grammatical errors such as punctuation mistakes, subject-verb agreement issues, incorrect word usage, etc.
- Performance: Achieves high accuracy in error detection and correction through pre-trained fine-tuning.

## Model used
### 1. T5 Large Model Trained on JFLEG 
The T5 (Text-To-Text Transfer Transformer) model is a transformer-based model introduced by Google Research, capable of performing a wide range of NLP tasks using a unified text-to-text framework. This particular instance of the T5 model is based on the "large" variant, which has 770M parameters.
Pretrained on JFLEG: The model was first pretrained on the JFLEG dataset, which is a benchmark dataset for grammatical error correction.

### 2. Facebook BART CNN
Fine-tuned on Facebook BART CNN: Subsequently, the model was fine-tuned on the Facebook BART CNN dataset, which is another corpus designed for improving grammatical error correction systems using news data.


Our final code is as follows:\
[https://colab.research.google.com/drive/1NcwPBNP96FExdc4dxDuji3l3rSzjljTK?usp=sharing](https://colab.research.google.com/drive/1As1IXEm23E5vbUuXt_3Da984-ZmCyT8q?usp=sharing#scrollTo=RKfKyWYHRTc3)

## Sample Screenshots
![Screenshot (3)](https://github.com/varshneyanushka/IITI_SOC_ML9/assets/152094795/43dcd4e9-49d7-42b8-a7ea-133a18afd185)
![Screenshot (2)](https://github.com/varshneyanushka/IITI_SOC_ML9/assets/152094795/9f94572e-0fca-4449-8067-f84de88057d0)


## Contributors
- [Shreeyut Maheswari](https://github.com/search?q=shreeyut1905&type=users)
- [Srikanth Chebolu](https://github.com/search?q=Srikanth1234567808&type=users) 
- [Piyush Tiwari](https://github.com/search?q=Piyush867583&type=users)
- [Vikash Kumar Singh](https://github.com/search?q=Vikas1177&type=users)

## Mentor
- [Anushka Varshney](https://github.com/search?q=varshneyanushka&type=users)

## Acknowledgments
- Google Research: For developing and releasing the T5 model architecture.
- JFLEG and Facebook BART CNN: For providing the datasets used for pretraining and fine-tuning.

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





