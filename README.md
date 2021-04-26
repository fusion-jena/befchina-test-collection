# BEF-China test collection for dataset search

This repository provides a test collection for dataset search in biodiversity. The test collections consists of 14 questions collected in different biodiversity research related projects and reflecting real user informations needs, a corpus of 372 datasets created in the scope of the [BEF-China project](https://bef-china.com) and human assessments evaluating which dataset is relevant to a question. 

Further information on the BEF-China project can be obtained from the website: [https://bef-china.com](https://bef-china.com).

## Data Corpus

The data-portal is available under this link [https://data.botanik.uni-halle.de](https://data.botanik.uni-halle.de).

Each dataset is available with the following pattern: `https://data.botanik.uni-halle.de/bef-china/datasets/<dataset-number>`, e.g., https://data.botanik.uni-halle.de/bef-china/datasets/630

## Questions

| Question Number | Question |
| ------ | ------ |
|Q1	|Name 3 species that occur in the shrub layer.|
|Q2	|Find 3 plant species where root lengths (depth) have been considered.|
|Q3	|Find 3 datasets from oaks where nitrogen content have been measured.|
|Q4	|Find 3 datasets where dry weights from conifers have been measured.|
|Q5	|Which nutrients occur in soil?|
|Q6	|Identify all parameters that are correlated to soil depth.|
|Q7	|Which taxa associated with tree species have been found, for example, insects on host trees?|
|Q8	|Which soil samples in BEF-China data show a low pH value?|
|Q9	|Does tree diversity reduce competition?|
|Q10|Do the soil carbon concentrations increse with soil depth?|
|Q11|Are there data about the leaf area index (LAI) and in particular in combination with diversity?|
|Q12|How does tree height have been measured in BEF-China experiments?|
|Q13|How does the nitrogen cycle interact with water?|
|Q14|How significant is the role of throughfall as water input to the forest floor?|


## Human Assessments

The human assessments are available in the provided txt file complying with the TREC benchmark data format. An entry in the txt file looks as follows:

```
1::161::1::1424380312
```

The first number denotes the question number, the second number provides the dataset number, the third number denotes the relevance judgment (1-relevant) and the last number is the timestamp of the creation of the entry. All datasets of the corpus that are not mentioned for a question are not deemed relevant.

## Licenses

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

The BEF-China test collection is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Citation

TBD