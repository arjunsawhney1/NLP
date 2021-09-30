# NLP
In this repo, I explore several facets of Natural Language Processing from pre-processing techniques to word embeddings and sentiment analysis

## Data
I use two different datasets for this project.

Amazon Reviews
https://www.kaggle.com/snap/amazon-fine-food-reviews/version/2
This dataset consists of reviews of fine foods from amazon. The data spans a period of more than 10 years, including all ~500,000 reviews up to October 2012. 
For the purposes of this demonstration, I use only 1000 rows

SMS Spam Collection
https://www.dt.fee.unicamp.br/~tiago/smsspamcollection/
The SMS Spam Collection v.1 is a public set of SMS labeled messages that have been collected for mobile phone spam research. 
It has one collection composed by 5,574 real and non-enconded messages, tagged according to being legitimate (ham) or spam. 
For the purposes of this demonstration, I use only 5000 rows

## Methods
### Pre-processing
- Remove all math elements
- Remove all HTML elements
- Remove all undesired unicode blocks (symbols)
- Remove all punctuation
- Remove all digits

### Further cleaning 
- Remove all stopwords
- Create vocabulary using CountVectorizer instance
- Correct uncorrect word spellings 
- Tokenize words
- Lemmatize words

### Embeddings
- Use either keywords or create n-grams for phrases
- Implemented bag-of-words frequency embedding 
- Word2Vec
