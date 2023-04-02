# WeRateDogs-data-exploration
## By Hadil Jilani

## Dataset Description
The data presented is from WeRateDogs twitter account. It is about rating dogs based on their pictures. The dataset provided is composed of three datasets: the *twitter archive*, the *image predictions* and the *additional data* provided from the **twitter API**. The twitter archive contains data about tweets posted by the *WeRateDogs* twitter account. The data frame involves **metadata** about the tweet (id, timestamp, url & source), the **text of the tweet**, the **reply and retweet status**, the **ratings** and the **dog stages** (puppo, doggo, pupper and floofer) given by WeRateDogs. The image predictions table contains **predictions** made by a neural network based on the pictures of the dogs provided in the tweets. The additional data provided by the API contains the **favorite count** and **retweet count** for each tweet.

## Data Wrangling and Exploration
The data was gathered from different sources (manually downloaded, from API..). Then, we assessed the data and cleaned it to obtain one single tidy table.
The cleaned data was used in the exploratory part, provided with extracted insights and visualization.

## Files Description
This repo presents the following files:
* `twitter_archive_master.csv`: The twitter archive table.
* `image-predictions.tsv`: contains the predictions of the NN.
* `twitter_archive_master.csv`: the twitter archive dataset stored after wrangling, used in the analysis.
* `tweet_json.txt`: the additional data provided by twitter's API
* `wrangle_act.ipynb`: the notebook that contains the code for data gathering, wrangling and analysis.
* `wrangle_report.html`: report of the data cleaning process
* `act_report.html`: report of the insights extracted from the analysis.
