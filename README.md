# Spatiotemporal Datasets ![License](https://img.shields.io/github/license/benedekrozemberczki/spatiotemporal_datasets.svg?color=blue) [![repo size](https://img.shields.io/github/repo-size/benedekrozemberczki/spatiotemporal_datasets.svg)](https://github.com/benedekrozemberczki/spatiotemporal_datasets/archive/master.zip)

Spatiotemporal datasets collected for network science, deep learning and general machine learning research.

<p align="center">
  <img width="600" src="https://github.com/benedekrozemberczki/datasets/blob/master/images/field.png">
</p>


##### Contents   
1. [Chickenpox Cases in Hungary](#chickenpox-cases-in-hungary)

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

### Citing
```bibtex
>@misc{rozemberczki2021twitch,
       title = {Twitch Gamers: a Dataset for Evaluating Proximity Preserving and Structural Role-based Node Embeddings}, 
       author = {Benedek Rozemberczki and Rik Sarkar},
       year = {2021},
       eprint = {2101.03091},
       archivePrefix = {arXiv},
       primaryClass = {cs.SI}
       }
```
