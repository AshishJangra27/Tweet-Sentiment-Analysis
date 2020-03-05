This is a Sentimental Analysis project where I am using Natural Language Processing and Deep Learning to analyze the sentiment of tweets. It's trained on the Sentiment140 dataset with 1.6Million tweets.

I've imported the dataset from my google drive in the code. You can directly upload the Sentiment140 dataset on google cloud and proceed with the code. I've achieved a test accuracy of 84% of this by using a very basic LSTM based neural network. This model took almost 10 minutes to train on GPU so you can see how well you can go with a larger and deeper neural net. Your Colab might crass for the first time because it provides you only 12GB of ram and this model will take around 32GB so you need to upgrade the ram of the Colab after crashing the Colab. I'm taking a fixed length of tweets which is 25 so if any tweet is larger so we take last 25 words and if its lesser then 25 so we pad them with zero in the beginning.

Kindly let me know if you found any doubts in understanding or implementing the code.

LinkedIn: https://www.linkedin.com/in/ashish-jangra/ OR
Website: http://www.ashishjangra.com
