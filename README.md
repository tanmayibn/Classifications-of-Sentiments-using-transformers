# Classifications-of-Sentiments-using-transformers
Refining BERT through fine-tuning within the PyTorch framework for the purpose of text sentiment classification.

## Objective:
Fine tuning BERT to classify sentiment of given text into POSITIVE or NEGATIVE.

## Dataset used:
Link to the [dataset](https://www.kaggle.com/amitkumardas/sentiment-train).

## Framework used:
Pytorch

## Method of fine-tuning
- Froze the pre-trained BERT model's architecture. 
- Added new layers to the BERT model
- Considered the class weights while deifing the loss function, stratified data while splitting into train, test and validation to handle the imbalance in the dataset.
- Used BERT tokenizer to process texts before fine-tuning.

## Result
![image](https://user-images.githubusercontent.com/47247696/147391497-cf842077-64d4-476f-bbca-580eaaa1b917.png)
