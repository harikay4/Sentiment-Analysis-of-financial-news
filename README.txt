Sentiment Analysis of the financial news to predict the direction of the stock market and Volatility.

Required files to run the code:

It includes data files from Kaggle source https://www.kaggle.com/aaron7sun/stocknews

• News Data(Combined_News_DJIA.csv): Historical news headlines, consists of top 25 news headlines for a single day. This data was crawled from Reddit WorldNews Channel (/r/worldnews), which were ranked by reddit user’s votes. Data Range: 2008-08-08 to 2016-07-01
• Stock Data (Labels.csv): Historical Stock data was taken from Yahoo Finance. Dow Jones Indus- trial Average(DJIA) can be analysed to prove the concept. Data Range: 2008-08-08 to 2016-07-01

Download the data files from Kaggle or here.
This project also need downloading the pre-trained Word2Vec model by Google. Instructions to download are given at https://code.google.com/archive/p/word2vec/ or  use direct link https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit

Steps:

1) Download the required file as mentioned above
2) You need access to jupyter notebooks, you can use either local Anaconda environment or free cloud tool provided by Google https://colab.research.google.com/, which has free access to GPUs to run your code. This code has been run on Google colab for the convenience, so that code can be run without installing any python packages. 
3) Upload the required files to your personal space on Google colab or to local, which should be accessible by the jupyter notebooks. 
4) Open the code with jupyter notebooks, make sure you have access to the data files downloaded in the above section and path to the files are correct in the code. 
For example, this code expects the Labels.csv under 'content' dir on colab session, path is given as "/content/Labels.csv".
This is also same for "/content/Combined_News_DJIA.csv"
But this code expects the pre-trained word2Vec from google drive, to avoid multiple copies for multiple sessions and path is given as '/content/drive/My Drive/GoogleNews-vectors-negative300.bin'
Make sure to update the paths once you have got access to these files from notebooks.

4) Simply run the code to see the results
5) Tweak, sophisticate and increase the number of the epochs to see what happens.