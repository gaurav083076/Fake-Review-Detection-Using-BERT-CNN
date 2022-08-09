# Fake-Review-Detection-Using-BERT_CNN
This repository contains the code for [**Fake Review Detection Using BERT-CNN**]

**Dataset links**

 Both Yelp Zip and Yelp Nyc can be downlaoded from the below drive link:

> https://drive.google.com/drive/folders/1hgb7l_ZMMkEV2AmQq_vETailCxdoc3h8?usp=sharing

In both Yelp Zip and Yelp Nyc  csv files required are:
1. metadata: contains label fake or real
2. reviewcontent: contains review 

This code contains pytorch implementation of BERT-CNN.
Google colab pro recommended.
Change runtime type to GPU.



1.  Upload the above datasets in google drive and change the directory path to dataset loaction in read_csv function.

2.  To run the code execute the provided notebook cell by cell.

3.  Model is saved with name 'bert-cnn-model1.pt' which can be used later. 
