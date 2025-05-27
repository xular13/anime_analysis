# Data Folder

This folder contains data samples and documentation for the Anime data analysis and machine learning project.

## 📁 Contents

- `animelist_sample.csv`: A sample of user anime list data.
- `anime_details_sample.csv`: A sample of anime metadata.
- `test_scrapping.ipynb`: Jupyter notebook demonstrating the data scraping and preprocessing workflow.

## 📄 Data Overview

### `animelist_sample.csv`

A sample from the dataset containing user anime list records. Each row represents a user's status for a particular anime.

**Key columns:**

- `user_id`: Anonymized unique identifier for a user.
- `anime_id`: Unique identifier for an anime.
- `status`: User's watching status (`completed`, `on_hold`, `dropped`, `plan_to_watch`, etc).
- `score`: User's rating for the anime (0 if not rated).
- `num_episodes_watched`: Number of episodes watched by the user.

### `anime_details_sample.csv`

A sample from the dataset containing anime metadata and attributes.

**Key columns:**

- `title`: Anime title.
- `main_picture`: JSON with image links for the anime.
- `alternative_titles`: JSON with alternate names (various languages).
- `start_date`, `end_date`: Dates when the anime aired.
- `synopsis`: Short description of the anime.
- `mean`: Mean user score.
- `rank`: Overall rank based on user ratings.
- `popularity`: Popularity rank.
- `num_list_users`, `num_scoring_users`: Number of users listing/scoring the anime.
- `nsfw`: NSFW rating.
- `genres`: List of genre tags.
- `media_type`: Type (e.g., `tv`, `ova`, `movie`).
- `status`: Airing status.
- `num_episodes`: Number of episodes.
- `start_season`: JSON with season and year.
- `source`: Original source type (e.g., manga, novel).
- `studios`: List of producing studios.
- `related_anime`: List of related anime (JSON).

## 🔗 Data Source & Collection

The datasets were **scraped from [MyAnimeList](https://myanimelist.net/)** using the process outlined in `test_scrapping.ipynb`.  
Due to size and licensing, only small samples are included here. For the full data, please refer to the scraping notebook and instructions below.

## 🛠️ How to Reproduce the Data

1. Open and run the `test_scrapping.ipynb` notebook.
2. Follow the instructions in the notebook to collect and preprocess the data from MyAnimeList using their public [API](https://myanimelist.net/apiconfig/references/api/v2) as well as the [Jikan](https://jikan.moe/) unofficial MyAnimeList API.
3. **Note:** The full dataset is large and is not distributed in this repository.

## ⚠️ Disclaimer & Usage

- All data is for **educational and research purposes only**.
- Do **not** use the data for commercial purposes.
- Respect [MyAnimeList’s Terms of Service](https://myanimelist.net/about/terms_of_use) when scraping or using their data.

## 📬 Questions

If you have questions about the data or how to reproduce it, see the main project README or open an issue.  
For inquiries about the full dataset used in this project, you can contact me at: `xular.13 [at] gmail [dot] com`.
