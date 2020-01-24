# Proposals for Future Projects
<br/>
<br/>

## 1. Predictive model for song popularity/weeks on top 100 chart
### Description
This project will be a continuation of my previous project that looked into testing whether or not the month of a songs release affected a songs lifespan on a top 100 music chart. This time, I will attempt to leverage machine learning in order to create a model that will predict a songs "popularity".

### Approach
As a possible data source, the csv that was used in the Top 100 UK songs project could be used with significant feature enrichment. It may even prove beneficial to include more years of data as the previous project was limited to just 5 years. Scraping the Spotify API could be another source of data as it is already much more feature rich.

Taking in possible features such as artist, label, genre, month of release, country of origin, tempo, etc, my initial choice for a predictive model would be a regression model. A RandomForestRegressor model may be used as a base model to start.
<br/>
<br/>
<br/>
## 2. A Korean-English Translator
### Description
This project will aim to create a language translator using the power of machine learning.

### Approach
As a large amount of tranlated text will be required, a possible data source for this project would be song lyric translations. As K-Pop has risen in popularity internationally in recent years, I believe that song translations, official or otherwise, have reached a point where they can be reliably used for this project.

The model needed for this project remains to be seen. More research on which models fit this projects needs to be done. Deep learning and/or NLP may be used.
<br/>
<br/>
<br/>
## 3. Moneyball
### Description
This project will aim to create the best possible sports team using a limited budget.

### Approach
A possible data source for this project would be basketball-reference.com as it has all of the stats that are used in basketball.

A possible model for this project would be a regression model.
