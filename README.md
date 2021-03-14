# Spatiotemporal Datasets ![License](https://img.shields.io/github/license/benedekrozemberczki/spatiotemporal_datasets.svg?color=blue) [![repo size](https://img.shields.io/github/repo-size/benedekrozemberczki/spatiotemporal_datasets.svg)](https://github.com/benedekrozemberczki/spatiotemporal_datasets/archive/master.zip)

Spatiotemporal datasets collected for network science, deep learning and general machine learning research.

<p align="center">
  <img width="600" src="https://github.com/benedekrozemberczki/datasets/blob/master/images/field.png">
</p>


##### Contents   
1. [Chickenpox Cases in Hungary](#chickenpox-cases-in-hungary)
2. [PedalMe London Bicycle Deliveries](#pedalme-london-bicycle-deliveries)

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
@misc{rozemberczki2021chickenpox,
      title={{Chickenpox Cases in Hungary: a Benchmark Dataset for Spatiotemporal Signal Processing with Graph Neural Networks}}, 
      author={Benedek Rozemberczki and Paul Scherer and Oliver Kiss and Rik Sarkar and Tamas Ferenci},
      year={2021},
      eprint={2102.08100},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

## PedalMe London Bicycle Deliveries
<p align="center">
  <img width="200" src="https://babesabouttown.com/wp-content/uploads/2010/06/chicken-pox-boy.jpg">
</p>
