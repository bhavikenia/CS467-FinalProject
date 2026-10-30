# Metaphors and melodies
**Team JB: Jade Hao & Bhavi Kenia | NLP Project**

**About**

This project looks at whether wordplay and metaphor in song lyrics differ across genres and whether lyric style helps predict song popularity. Popularity is measured by Genius lyric-page views, which is a proxy for popularity, not streams.

**Data**

[5 Million Song Lyrics (Kaggle)](https://www.kaggle.com/datasets/nikhilnayak123/5-million-song-lyrics-dataset/code) 

**NOTE**
- There are two notebooks since the data was too big and not working on Jade computer
- 
*NLP_Update02_TeamJB.ipynb covers:*
Loading and filtering the data
Cleaning the lyrics (section headers, Embed artifacts, duplicates)
Exploring genres, years, and views
Baseline theme labeling (love/relationships vs. struggle/identity)
Building a balanced sample for manual annotation of wordplay and metaphor
Automated linguistic features (vocabulary diversity, rhyme density, repetition, sentiment, etc.)
Baseline model predicting log(views) with artist-grouped cross-validation

*data_and_features_v2.ipynb* covers:
- Loading the 5 Million Song Lyrics dataset and filtering to English rap, pop, and country songs
- Cleaning the lyrics (section labels like [Chorus], duplicates, very short and very long texts)
- Exploring genres, lyric lengths, and views
- Baseline theme labeling (love/relationships vs. struggle/identity) using keyword lists
- Building a balanced sample for manual annotation of wordplay and metaphor
- Automated linguistic features (vocabulary diversity, repetition, sentiment)

Lyrics are not included in this repo. `annotation_songs.csv` lists the sampled songs by ID, title, artist, genre, and theme.
