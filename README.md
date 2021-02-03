# Datasets ![License](https://img.shields.io/github/license/benedekrozemberczki/temporal_datasets.svg?color=blue) [![repo size](https://img.shields.io/github/repo-size/benedekrozemberczki/datasets.svg)](https://github.com/benedekrozemberczki/temporal_datasets/archive/master.zip)

Spatio-temporal datasets collected for network science, deep learning and general machine learning research.

<p align="center">
  <img width="600" src="/images/field.png">
</p>

##### Contents   
1. [Chickenpox Cases in Hungary](#chickenpox-cases-in-hungary)
2. [Twitch Gamers](#twitch-gamers)
3. [LastFM Asia Social Network](#lastfm-asia-social-network)
4. [Deezer Europe Social Network](#deezer-europe-social-network)
5. [GitHub StarGazer Graphs](#github-stargazer-graphs)
6. [Twitch Ego Nets](#twitch-ego-nets)
7. [Reddit Thread Graphs](#reddit-thread-graphs)  
8. [Deezer Ego Nets](#deezer-ego-nets)
9. [GitHub Social Network](#github-social-network)
10. [Deezer Social Networks](#deezer-social-networks)
11. [Facebook Page-Page Networks](#facebook-page-page-networks)  
12. [Wikipedia Article Networks](#wikipedia-article-networks)
13. [Twitch Social Networks](#twitch-social-networks)
14. [Facebook Large Page-Page Network](#facebook-large-page-page-network)


## Chickenpox Cases in Hungary
<p align="center">
  <img width="200" src="https://babesabouttown.com/wp-content/uploads/2010/06/chicken-pox-boy.jpg">
</p>


### Description
<p align="justify">
A spatio-temporal dataset of weekly chickenpox (childhood disease) cases from Hungary. The dataset consists of a county-level adjacency matrix and time series of the county-level reported cases between 2005 and 2015. There are 2 specific related tasks:</p>

- County level case count prediction.
- National level case count prediction.

### Links


- [Chickenpox Cases in Hungary Edges](https://graphmining.ai/temporal_datasets/hungary_county_edges.csv)
- [Chickenpox Cases in Hungary Time Series](https://graphmining.ai/temporal_datasets/hungary_chickenpox.csv)

### Properties

- **Directed:** No.
- **Node features:** Yes.
- **Temporal:** Yes.


|   | **Hungarian Counties**  |
|---|---|
| **Nodes** |20   |
| **Edges** |61 |
| **Density** |  0.3211 |
| **Transitvity** | 0.4134|

### Possible tasks

- **Count data regression**
