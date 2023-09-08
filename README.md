# Sentiment-Analysis-using-R
Using R programming to analyse different types of sentiments portrayed by processing the data.  

### Term document matrix  

A table containing the frequency of words.  

> <img width="200" alt="Screenshot 2023-09-09 020536" src="https://github.com/16102/Sentiment-Analysis-using-R/assets/92366931/70f16d6c-c0ef-4310-b9f4-bf16d41fa19c">       <img width="200" src="https://github.com/16102/Sentiment-Analysis-using-R/assets/92366931/450fb098-c938-46dd-bf04-74e960f5bb31">


### Word cloud  

An image composed of keywords found within a body of text, where the size of each word indicates its count in that body of text.  

> <img width="128" alt="Screenshot 2023-09-09 021433" src="https://github.com/16102/Sentiment-Analysis-using-R/assets/92366931/da90cc32-e19a-4a06-8ce1-8e4d6776a3a3">  

### Emotion Classifier    

- Emotion classification is built on the NRC Word-Emotion Association Lexicon (aka EmoLex). 

- The get_nrc_sentiments function, returns a data frame with each row representing a sentence from the original file. The data frame columns (one column for each of the eight emotions, one column for positive sentiment valence and one for negative sentiment valence).

- Two plots charts are help visually analyze the emotions in this survey text. First, perform some data transformation and clean-up steps before plotting charts. The first plot shows the total number of instances of words in the text, associated with each of the eight emotions.

> ![emotion](https://github.com/16102/Sentiment-Analysis-using-R/assets/92366931/d2332f52-dda2-4d75-b8f4-f4e52fe3a08b)![survey](https://github.com/16102/Sentiment-Analysis-using-R/assets/92366931/1eed7c10-1bbc-4e52-ae51-d72c8ad1bdee)
