*To make it less overwhelming, here is a list of standard steps you can take depending on what you want to do:*
## If using prebuilt packages
- Perform standard data cleaning (remove links, remove \n \t)
- Run Vader/TextBlob or your preferred package 
---
## If training your own
- Preprocess
	- Stopwords
	- Punctuation
	- Stemming/Lemmatization
	- And any cleaning (ie. links, \n)
- Build feature matrix using CountVectorizer()
- Train and predict just like normal
