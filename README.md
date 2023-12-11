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
- [`G8_report.pdf`](https://github.com/your_username/your_repository/blob/main/G8_report.pdf): Poster representing the project shortly.

### Markdown Files
- [`README.md`](https://github.com/your_username/your_repository/blob/main/README.md): Main file explaining the project and guiding other files.

### Jupyter Notebooks
- [`file.ipynb`](https://github.com/your_username/your_repository/blob/main/file.ipynb): Jupyter Notebook containing code related to dataset analysis.
- [`prediction.ipynb`](https://github.com/your_username/your_repository/blob/main/prediction.ipynb): Jupyter Notebook containing code related to prediction models.
- [`steamproject.ipynb`](https://github.com/your_username/your_repository/blob/main/steamproject.ipynb): Jupyter Notebook containing code related to crawling information from SteamSpy and converting it into datasets.

### CSV Files
- [`details.csv`](https://github.com/your_username/your_repository/blob/main/details.csv): Dataset crawled from SteamSpy, containing various attributes (name, developer, publisher, positive, negative, min_owners, max_owners, average_forever, average_2weeks, median_forever, median_2weeks, ccu, price, initialprice, discount, genre, tags, languages).
- [`details_small.csv`](https://github.com/your_username/your_repository/blob/main/details_small.csv): Smaller version of `details.csv` dataset (not necessary).
- [`timestamps.csv`](https://github.com/your_username/your_repository/blob/main/timestamps.csv): Dataset crawled from SteamSpy via `steamproject.ipynb`, containing datetimes and game names (by their unique IDs).
- [`timestamps_small.csv`](https://github.com/your_username/your_repository/blob/main/timestamps_small.csv): Smaller version of `timestamps.csv` dataset (not necessary).

## Replicating the Analysis
To replicate the same analysis that the authors have done, download all the files in the repository (except for `README.md`, `details_small.csv`, `timestamps_small.csv`). Follow the instructions and markups written in the Jupyter Notebooks.
