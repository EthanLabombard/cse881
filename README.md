The goal of this project is to develop a model that will be capable of predicting results for the 2026 FIFA World Cup using the results of previous World Cup matches. This project will involve scraping the publicly available match data; then cleaning, combining, and preprocessing this scraped data for preparation to use in model development. After the data has been prepped for evaluation, this project will advance by developing a predictive model that will take in certain statistics about the teams that are facing in each match and use this as input data on the model that we have trained. The predictive model is built on a Poisson regression framework, which estimates expected goals for each team based on FIFA ranking, GDP, and population, and derives win/draw/loss probabilities from the joint distribution over possible scorelines. This approach is then extended into a full tournament simulation using Monte Carlo methods to estimate championship probabilities for all 48 competing nations. After training this model, the model is capable of predicting match results with a high degree of success.

Repository Structure

├── data/              # Raw and processed datasets

├── Modeling/          # Modeling jupyter notebooks

├── Preprocessing/     # Preprocessing jupyter notebooks  

└── README.md
