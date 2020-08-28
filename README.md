# MSA Data Phase 2  

<br>

---
### What you will learn
* Data exploration and preparation using the NLTK package
* Sentiment analysis using the TextBlob and Vader libraries (part of NLTK)
* Sentiment analysis using Recurrent Neural Network
* PowerBi basics
---
### How to set up project

For windows
```shell
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

For Mac 
```shell
python3 -m venv venv
source ./venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```  
Feel free to contact Karim if you run into problems with the code for Mac! :) <br>


---
### Resources
These are OPTIONAL resources which will help you understand the content better
* Datacamp tutorial <br>
https://www.datacamp.com/community/tutorials/text-analytics-beginners-nltk?utm_source=adwords_ppc&utm_campaignid=898687156&utm_adgroupid=48947256715&utm_device=c&utm_keyword=&utm_matchtype=b&utm_network=g&utm_adpostion=&utm_creative=332602034352&utm_targetid=dsa-429603003980&utm_loc_interest_ms=&utm_loc_physical_ms=1011036&gclid=EAIaIQobChMI-_uokLe96wIViA4rCh31dwslEAAYASAAEgK0DPD_BwE
* Tensorflow tutorial <br>
https://www.tensorflow.org/tutorials/text/text_classification_rnn
  
---
### Assessment
1. Compete in the Kaggle challenge here: https://www.kaggle.com/c/sentiment-analysis-msa-phase-2 <br>
You will have to build your own model for this challenge
2. Using the model you have built for the Kaggle challenge, run it on Reddit comments to obtain sentiments for them. We have scraped the Reddit data for you 
and you can find it in the "Reddit data" folder on this Github page. The file you will be using is called "comments.csv".
3. Use one of the prebuilt packages (Vader/TextBlob) to generate sentiments for the same Reddit data. Compare the results of your model against that
of the prebuilt packages and comment briefly on differences.
4. Generate a dashboard in PowerBi to visualize the Reddit comments as well as the predictions. Things you can consider are word clouds, most frequent
bigrams, sentence lengths, sentiments at posts level (Recall that the sentiment predictions are for individual comments to the Reddit posts). 
