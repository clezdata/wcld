# WCLD: Curated Large Dataset of Criminal Cases from Wisconsin Circuit Courts


Machine learning based decision-support tools in criminal justice systems are subjects of intense discussions and academic research. There are important open questions about the utility and fairness of such tools. Academic researchers often rely on a few small datasets that are not sufficient to empirically study various real-world aspects of these questions. In this paper, we contribute WCLD, a curated large dataset of 1.5 million criminal cases from circuit courts in the U.S. state of Wisconsin. We used reliable public data from 1970 to 2020 to curate attributes like prior criminal counts and recidivism outcomes. The dataset contains large number of samples from five racial groups, in addition to information like sex and age (at judgment and first offense). Other attributes in this dataset include neighborhood characteristics obtained from census data, detailed types of offense, charge severity, case decisions, sentence lengths, year of filing etc. We also provide pseudo-identifiers for judge, county and zipcode. The dataset will not only enable researchers to more rigorously study algorithmic fairness in the context of criminal justice, but also relate algorithmic challenges with various systemic issues. We also discuss in detail the process of constructing the dataset and provide a datasheet.

## Citing this work
```
@article{ash2023wcld,
      title={WCLD: Curated Large Dataset of Criminal Cases from Wisconsin Circuit Courts}, 
      author={Elliott Ash and Naman Goel and Nianyun Li and Claudia Marangon and Peiyao Sun},
      booktitle={37th Conference on Neural Information Processing Systems (NeurIPS 2023) Track on Datasets and Benchmarks.},
      year={2023}
}
```