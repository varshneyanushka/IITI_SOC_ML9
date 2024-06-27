# IITI_SOC_ML9
Grammer Auto correct

This Project is a Part of IITISoC'24

## PROJECT’s INTENT 
Building a model to take English sentences as input from the user and analyse them and identify the grammatical error's and rectify them and return sentence with correct grammar and also suggest's a impressive way of writing those sentences which have a better impact on reader.

## Features
- Error Detection: Identifies various types of grammatical errors such as punctuation mistakes, subject-verb agreement issues, incorrect word usage, etc.
- Performance: Achieves high accuracy in error detection and correction through fine-tuning on large-scale text corpora.

## Model used
### 1. T5 Large Model Trained on JFLEG 
The T5 (Text-To-Text Transfer Transformer) model is a transformer-based model introduced by Google Research, capable of performing a wide range of NLP tasks using a unified text-to-text framework. This particular instance of the T5 model is based on the "large" variant, which has 770M parameters.
Pretrained on JFLEG: The model was first pretrained on the JFLEG dataset, which is a benchmark dataset for grammatical error correction.

### 2. Facebook BART CNN
Fine-tuned on Facebook BART CNN: Subsequently, the model was fine-tuned on the Facebook BART CNN dataset, which is another corpus designed for improving grammatical error correction systems using news data.

## Model Training 
- Data Preparation: JFLEG dataset was used for initial pretraining, focusing on grammatical error detection and correction.
- Fine-tuning: The model was fine-tuned on the Facebook BART CNN dataset, which contains news articles, further enhancing its ability to correct errors in formal and journalistic text.

Our final code is as follows:\
https://colab.research.google.com/drive/1NcwPBNP96FExdc4dxDuji3l3rSzjljTK?usp=sharing

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





