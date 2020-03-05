# Tweet-Sentiment-Analysis
This is a Sentimental Analysis project where i am using Natural Language Processing and Deep Learning to analyse the sentiment of tweets. It's trained on Sentiment140 dataset with 1.6Million tweets.

I've imported the dataset from my google drive in the code. You can directly upload the Sentiment140 dataset on google cloud and proceed with the code. I've achived a test accuracy of 84% of this with using a very basic LSTM based neural network. This model took almost 10 minutes to train on GPU so you can see how well you can go with larger and deeper neural net. Your colab might crass for the first time because it provide you only 12GB of ram and this model will take arounf 32GB so you need to upgrade the ram of the colab after crashing the colab. I'm taking a fixed length of tweets which is 25 so if any tweet is larger so we take last 25 words and if its lesser then 25 so we pad them with zero in the beginning.

Kingly let me know if you found any doubt in the understanding or implimenting the code.

LinkedIn: https://www.linkedin.com/in/ashish-jangra/ OR
Website: http://www.ashishjangra.com
