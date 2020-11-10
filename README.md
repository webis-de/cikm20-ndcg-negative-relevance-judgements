# Code for the CIKM20 Short Paper: "The Impact of Negative Relevance Judgments on NDCG"

```
@InProceedings{gienapp:2020,
  author =              {Lukas Gienapp and Maik Fr{\"o}be and Matthias Hagen and Martin Potthast},
  booktitle =           {29th ACM International Conference on Information and Knowledge Management (CIKM 2020)},
  doi =                 {10.1145/3340531.3412123},
  editor =              {Mathieu d'Aquin and Stefan Dietze and Claudia Hauff and Edward Curry and Philippe Cudre Mauroux and Sourav Bhowmick and Yanyan Lan and Zhiyuan Liu and {Anna Lisa} Gentile and Ricardo Baeza-Yates and Eirini Ntoutsi and Fouad Zablith and Ian Soboroff and Paolo Cremonesi},
  month =               oct,
  publisher =           {ACM},
  site =                {Virtual Event, Ireland},
  title =               {{The Impact of Negative Relevance Judgments on NDCG}},
  year =                2020,
} 
```

This repository consists of three notebooks:
- [`Data.ipynb`](Data.ipynb) converts TREC qrel and run files into a common tabular layout that subsequent steps of the analysis depend on
- [`Scoring.ipynb`](Scoring.ipynb) implements custom nDCG scoring for all variants of the metric explored in the paper
- [`Analysis.ipynb`](Analysis.ipynb) includes all code to reproduce the statistical insights given in the paper.

All dependencies required to run the experiments (including jupyter itself) can be installed using the supplied [`requirements.txt`](requirements.txt).

The qrel & run data can be obtained from the [TREC website](https://trec.nist.gov). They are not shared here due to size & unclear licensing.

Any modifications to the code will be merged directly into the master branch; the original code for the paper is archived as [`1.0.0`](https://github.com/webis-de/cikm20-ndcg-negative-relevance-judgements/releases/tag/1.0.0) release.
