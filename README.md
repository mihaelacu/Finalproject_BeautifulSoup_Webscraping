# finalproject Prediktivni model cijena stanova u Zagrebu

# Pomoću linearne regresije i DecisionTreeRegressora napravljen je prediktivni model koji na osnovu podataka o stanovima radi procjenu cijena stanova. Podaci su dobiveni pomoću scrapinga weba Oglasnik.hr. Kako bi se to postiglo bitno je poznavati HTML kod i sve elemente koda u HTML-u.

# Prerequisites
# Potrebno je bilo instalirati Beautiful Soup.
# Beautiful Soup je Python knjižnica koja izvalači podatke iz HTML-a i XML datoteka. 

# Installing
# Potrebno je dodati BeautifulSoup knjiznicu u Python u cmd prompt(pip install BeautifulSoup)
# nakon toga dodati u python file 

# *from bs4 import BeautifulSoup*
# *import requests*

# Za predikciju se najbolje pokazao DecisionTreeRegressor.
# *from sklearn.tree import DecisionTreeRegressor

# Define model. Specify a number for random_state to ensure same results each run
# data_model = DecisionTreeRegressor(random_state=1)

# Fit model
# data_model.fit(X, y)*
