# Data Science eksamensprojekt
## Stock Exchange System


* Jörg Oertel - cph-jo130@cphbusiness.dk

**Please read the data story for further information about the project!**

## The structure of the project 

* [Stage 1](./documents/project_stages/STAGE_1.md)
* [Stage 2](./documents/project_stages/STAGE_2.md)
* [Data Story](./documents/project_stages/STAGE_1.md)

### **Stock predicter**
This module will be responsible for processing historical data and based on this give an idea of the development in the course. 
\
\
possible technologies  
* Linear regression
* LSTM, Long Short Term Memory - RNN, Recurrent Neural Network
* Python

possible data ressources
* Alpha Vantage
* Yahoo Finance

<br/>

### **Scraper** (not implementet)
Based on the user's interest in the stock market, it will be possible to enter search criterias to be able to find relevant articles on the topic. If the user is interested in the Tesla stock, it might be relevant to find articles about Elon Musk, Lithium Batteries or SpaceX. These articles are scraped from various sources on the Internet and stored in a database for further processing. 


possible technologies  
* Neo4j
* HBase
* Python

possible data ressources
* Twitter
* Wall Street Journal
* Investors
* CNBC
* MarketWatch

<br/>

### **Sentiment Analyzer**
Dette modul vil i sammenspil med scraper modulet analysere artikler og give en procent score på positive, negative eller neutral tone i artiklerne. På den måde kan vi afgøre om der er meget negativ eller positiv omtale omkring eksempelvis Tesla og om det kan have en betydning for aktienværdien.

possible technologies   
* NLP, Natural Language Processing - Kap. 21, Joel Grus
* Python

possible data ressources
* Own database of scraper results (that database is created but not implemnted here)

<br/>

### **Autotrader**(not implemented)
It would be a nice to have implemantation but it has the lowest priority throughout the project. The module is intended to handle stock trading via an API. Once the application has arrived at a recommendation around a stock, the autotrader will either buy or sell based on that recommendation. 

possible technologies  
* Alpaca API
* Python

<br/>

