# SocialComQuant-Summer-School-2022
This repository includes (some of the) codes for the Social ComQuant Summer School 2022 Group 5 Project - "Sentiment Analysis & Topic Modeling of the Discussions about Potential Candidates for the Upcoming Presidential Election in Turkey"

1- [Data Collection](https://github.com/melihcanyardi/SocialComQuant-Summer-School-2022/blob/main/SCQ_Summer22-Data_Collection.ipynb): Data collection of the tweets between July 1st 2021 and July 25th 2022 (390 days) with specified keywords* regarding the potential candidates.

2- [Sentiment Analysis](https://github.com/melihcanyardi/SocialComQuant-Summer-School-2022/blob/main/SCQ_Summer22-Sentiment.ipynb): Adding sentiment labels and scores to the data collected using [Bert-base Turkish Sentiment Model](https://huggingface.co/savasy/bert-base-turkish-sentiment-cased).

3- [Analysis](https://github.com/melihcanyardi/SocialComQuant-Summer-School-2022/blob/main/SCQ_Summer22-Analysis.ipynb): (Correlation) analysis of the sentiment changes over time of each candidate.

*Queries
  - Kemal Kılıçdaroğlu: (kemal OR kilicdaroglu OR kilicdar OR "kemal kilicdaroglu") (aday OR adayi OR adaylik OR adayligi) lang:tr -is:retweet
  - Mansur Yavaş: mansur OR yavas OR "mansur yavas") (aday OR adayi OR adaylik OR adayligi) lang:tr -is:retweet
  - Ekrem İmamoğlu ekrem OR imamoglu OR "ekrem imamoglu") (aday OR adayi OR adaylik OR adayligi) lang:tr -is:retweet
