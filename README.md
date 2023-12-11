Project 
Name: Steam Market Analysis
Authors: Team G8: Egor Lukjanenko, Artur Kashnikov, Arkadi Statsenko
MOtivation: This project aims to analyze the Steam gaming market, focusing on understanding current market trends, genre popularity, and predicting the success of gaming projects. Steam, being a major platform for digital distribution of games, so analyzing market could be beneficial to developers and as well to enthusiasts, who want to be informed in current trends.
Guide to the repository:
  G8_report.pdf
  README.md - main current file explaining the project itself and being the guide for other files
  details.csv - dataset, which has been crawled from steamspy and contains different attributes (name	developer	publisher	positive	negative	min_owners	max_owners	average_forever	average_2weeks	median_forever	median_2weeks	ccu	price	initialprice	discount	genre	tags	languages)
  details_small.csv (not necessery file) - smaller version of details.csv dataset
  file.ipynb - jupiter notebook, containing code related to the datasets analyzes.
  prediction.ipynb - jupiter notebook, containig code related to the prediction models.
  steamproject.ipynb - jupiter notebook, containig code related to crawling information from website steamspy and therefore converting into datasets
  timestamps.csv - dataset, which has been crawled from the steamspy through the steamproject.ipynb and contains datetimes and game names (by their unique id-s).
  timestamps_small.csv (not necessery file) - smaller version of timestamps.csv dataset


Explain how it is possible to take the code and replicate the same analysis that the authors have done: Is is possible by just
downloading all the files in the reposetory (except for the README,poster, details_small.csv, timestamps_small.csv files) and follow the markups, written in the notebooks
