# Project: Steam Market Analysis

## Authors
- Team G8:
  - Egor Lukjanenko
  - Artur Kashnikov
  - Arkadi Statsenko

## Motivation
This project aims to analyze the Steam gaming market, focusing on understanding current market trends, genre popularity, and predicting the success of gaming projects. Steam, being a major platform for the digital distribution of games, makes analyzing the market beneficial to developers and enthusiasts who want to stay informed about current trends.

## Guide to the Repository

### PDF Files
- [`G8_report.pdf`](https://github.com/Artysuk/Steam-Project/blob/main/G8_report.pdf): Report which represents a detailed guide on the purposes, plans, and methodologies of the Steam Market Analysis project, providing a thorough overview of the project's scope and execution strategy.
- [`G8 poster.pdf`](https://github.com/Artysuk/Steam-Project/blob/main/G8_poster.pdf): Poster representing the project shortly.
### Markdown Files
- [`README.md`](https://github.com/Artysuk/Steam-Project/blob/main/README.md): Main file explaining the project and guiding other files.

### Jupyter Notebooks
- [`analyze.ipynb`](https://github.com/Artysuk/Steam-Project/blob/main/file.ipynb): Jupyter Notebook containing code related to dataset analysis.
- [`prediction.ipynb`](https://github.com/Artysuk/Steam-Project/blob/main/prediction.ipynb): Jupyter Notebook containing code related to prediction models.
- [`crawl.ipynb`](https://github.com/Artysuk/Steam-Project/blob/main/steamproject.ipynb): Jupyter Notebook containing code related to crawling information from SteamSpy and converting it into datasets.

### CSV Files
- [`details.csv`](https://github.com/Artysuk/Steam-Project/blob/main/details.csv): Dataset crawled from [SteamSpy](https://steamspy.com/), containing various attributes (first column - appid - Steam Application ID, "name" - game's name, "developer" - game's developer, "publisher" - game's publisher, "min_owners" - estimated minimal amount of purchases, "max_owners"- estimated maximum amount of purchases, "average_forever" - average playtime since March 2009 in minutes, "average_2weeks" - average playtime in the last two weeks in minutes, "median_2weeks" - median playtime since March 2009 in minutes, "ccu" - peak CCU (concurent users) yesterday, "price" - current US price in cents, "initialprice" - initial US price in cents, "discount" - current discount percent, "genre" - list of genres, "tags" - list of tags, "languages" - list of supported languages, [steamspy api](https://steamspy.com/api.php)).
- [`details_small.csv`](https://github.com/Artysuk/Steam-Project/blob/main/details_small.csv): Smaller version of `details.csv` dataset (not necessary).
- [`timestamps.csv`](https://github.com/Artysuk/Steam-Projecty/blob/main/timestamps.csv): Dataset crawled from SteamSpy via `steamproject.ipynb` from [SteamCharts](https://steamcharts.com/), containing user peaks at each month since July 2012 per game, NaN for dates before game was realesed, first column is appid - Steam Application ID.
- [`timestamps_small.csv`](https://github.com/Artysuk/Steam-Project/blob/main/timestamps_small.csv): Smaller version of `timestamps.csv` dataset (not necessary).

## Replicating the Analysis
To replicate the same analysis that the authors have done, download all the files in the repository (except for `README.md`, `details_small.csv`, `timestamps_small.csv`). Follow the instructions and markups written in the Jupyter Notebooks.
