# HuRC

This is the home repository for the Hungarian Corpus for Reading Comprehension with Commonsense Reasoning (HuRC), which is also part of the Hungarian Language Understanding Evaluation Benchmark Kit [HuLU](hulu.nlp.nytud.hu). 

## Data

The files are in the 'data' folder. The dataset contains 80 621 instances. Each instance is composed of a passage and a cloze-style query with a masked entity. The task is to select the named entity that is being masked in the query.

The data was collected from the online news of Népszabadság online (nol.hu).

## Data format

The data files are in json format. The keys are the following:

`idx`: unique id of the instances;

`passage`: 2-3 paragraphs of a news article;

`query`: the last paragraph of the article with a masked named entity; 

`answers`: a list of the possible answers, where each answer consists of an id and a string.  

## Guidelines

Later...

## License and usage


## Citation

If you use this resource or any part of its documentation, please refer to:

Ligeti-Nagy, N., Ferenczi, G., Héja, E., Jelencsik-Mátyus, K., Laki, L. J., Vadász, N., Yang, Z. Gy. and Váradi, T. (2022) HuLU: magyar nyelvű benchmark adatbázis
kiépítése a neurális nyelvmodellek kiértékelése céljából [HuLU: Hungarian benchmark dataset to evaluate neural language models]. XVIII. Magyar Számítógépes Nyelvészeti Konferencia. (in press)

```

@inproceedings{ligetinagy2022hulu,
  title={HuLU: magyar nyelvű benchmark adatbázis kiépítése a neurális nyelvmodellek kiértékelése céljából},
  author={Ligeti-Nagy, N. and Ferenczi, G. and Héja, E. and Jelencsik-Mátyus, K. and Laki, L. J. and Vadász, N. and Yang, Z. Gy. and Váradi, T.},
  booktitle={XVIII. Magyar Számítógépes Nyelvészeti Konferencia},
  year={2022}
}
```
