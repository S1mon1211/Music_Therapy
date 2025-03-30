# Effect of Music Therapy on Mental Health
@Simon_Hua


## Project Overview
### Introduction
  Music’s role in mental health remains a compelling yet debated topic. While studies suggest music can alleviate stress and mood disorders, the impact of specific genres on mental conditions—such as anxiety, depression, and insomnia—is unclear. Conflicting theories persist: some emphasize engagement intensity over genre, while others link certain styles (e.g., classical, gospel) to therapeutic effects. Leveraging a dataset of 736 respondents, this study investigates three dimensions: 
  
  - Correlations between listening habits (frequency, context) and mental health scores;
  
  - Mutual effects of 16 music genres and 4 mental health problems (Gospel’s anxiety-reducing potential vs. Lofi’s depressive associations);
  
  - Personalized genre recommendations for mental health support.
  
  By bridging data-driven analysis with music therapy principles, this research aims to inform clinical practices and optimize music platforms’ therapeutic potential through context-aware, personalized interventions. 

### Output
  - To see Interactive Data Visualisations created by Plotly and corresponding insights, [**👉🔗CLICK HERE👈**](https://nbviewer.org/github/S1mon1211/Music_Therapy/blob/main/DataViz_and_Insights.ipynb)
  
### Goal
  - Investigate the relationship between different music-listening habits and mental conditions
  - Explore whether the preferred music genres postively or negatively affect mental state
  - Identify music genres that should be recommended for healing specific types of mental problems (Anxiety, Depression, Insomnia, Obsessive Compulsive Disorder)

### Dataset
  - Description: 736 data points from a public mental health survey, with respondents from diverse age ranges and regions.
  - Survey Structure:
      - Part 1: General background questions about the responders and their music habits.
      - Part 2: Frequency of listening to given music genres.
      - Part 3: Mental Health conditions

## Repo Structure
```
├── README.md                                        <- You're here
|
├── Data_Analysis_on_Music_Therapy_Effect.ipynb      <- Jupyter Notebook Containing EDA, Feature Engineering, Visualisations
|
├── DataViz_and_Insights.ipynb                       <- Data Visualisation Code, Uploaded only for generating the interactive version on Jupyter nbviewer
|
├── requirements.txt                                 <- Python package dependencies

```
## Key Findings
### Listening Habits And Mental Health
<p align='center'>
<img src='https://github.com/S1mon1211/Music_Therapy/blob/main/Graphs/Responder_preference.png?raw=true'>
</p>

#### Findings:
As the responders in this survey are mostly 14-35 year-old young people, so they seem to prefer fast-paced music genres(Rock: 25.5%, Pop: 15.7% and Metal: 12.1%), which may impact their mental conditions.

<p align='center'>
<img src='https://github.com/S1mon1211/Music_Therapy/blob/main/Graphs/Listening_Frequency.png?raw=true'>
</p>

#### Findings:
Obvious variations could be identified in the listening frequency for each genre (Rock and pop are more popular than Gospel and Latin).
<p align='center'>
<img src='https://github.com/S1mon1211/Music_Therapy/blob/main/Graphs/Age.png?raw=true'>
</p>

#### Findings:
Different genres may attract specific age groups, which indicates that certain music therapy could be proposed to targeted groups.

### Music Genres And Mental Health
<p align='center'>
<img src='https://github.com/S1mon1211/Music_Therapy/blob/main/Graphs/Fav_genre_intensity.png?raw=true'>
</p>

#### Findings:
After defining three intensity levels(1-3: mild, 4-7: moderate, 8-10: severe), we compared among genres by mental problem.
- For Anxiety, **folk and pop** listeners have obviously higher intensity (75% above level 6), while **gospel** listeners are less likely to have anxiety (75% below level 6).
- For depression, **lofi** listeners have severe depression intensity (50% above level 8), while **gospel** listeners seem to have smaller possibility to be depressed (75% below level 4).
- For insomnia, latin fans have lower insomnia intensity (all of which below level 1) and no specific genres seem to result in high intensity.
- For OCD, music therapy exhibits almost no effect on it.

### Genre Recommendations For Therapy
<p align='center'>
<img src='https://github.com/S1mon1211/Music_Therapy/blob/main/Graphs/Therapy_effect_anxiety.png?raw=true'>
</p>

#### Findings:
We examined therapy effects for each of four mental disorders and here is an example on anxiety. For more details, go check [**Data Analysis Notebook**](https://github.com/S1mon1211/Music_Therapy/blob/main/Data_Analysis_on_Music_Therapy_Effect.ipynb).

