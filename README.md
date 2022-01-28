# HuRC

This is the home repository for the Hungarian Corpus for Reading Comprehension with Commonsense Reasoning (HuRC), which is also part of the Hungarian Language Understanding Evaluation Benchmark Kit [HuLU](hulu.nlp.nytud.hu). 

## Data

The can be found at this [link](https://nc.nlp.nytud.hu/s/3N7nHTC3nk8GxH6). The dataset contains 80 621 instances. Each instance is composed of a passage and a cloze-style query with a masked entity. The task is to select the named entity that is being masked in the query.

The data was collected from the online news of Népszabadság online (nol.hu).

## Data format

The data files are in json format. The keys are the following:

`id`: unique id of the instances;

`lead`: a short summary of the article as it was extracted from the source texts;

`passage`: 3-6 paragraphs of texts as the body of the article;

`query`: the last paragraph of an article, some kind of summary or conclusion, with a named entity masked (with [MASK]) in it;

`MASK`: the masked named entity. 

## Guidelines

Annotation guidelines are available (in Hungarian) in the guidelines folder.

## License and usage

HuRC is released under the cc-by-4.0 license.

## Citation

If you use this resource or any part of its documentation, please refer to:

Ligeti-Nagy, N., Ferenczi, G., Héja, E., Jelencsik-Mátyus, K., Laki, L. J., Vadász, N., Yang, Z. Gy. and Váradi, T. (2022) HuLU: magyar nyelvű benchmark adatbázis
kiépítése a neurális nyelvmodellek kiértékelése céljából [HuLU: Hungarian benchmark dataset to evaluate neural language models]. In: Berend, G., Gosztolya, G. and Vincze, V. (eds), XVIII. Magyar Számítógépes Nyelvészeti Konferencia. Szeged, Szegedi Tudományegyetem, Informatikai Intézet. 431–446.

```

@inproceedings{ligetinagy2022hulu,
  title={HuLU: magyar nyelvű benchmark adatbázis kiépítése a neurális nyelvmodellek kiértékelése céljából},
  author={Ligeti-Nagy, N. and Ferenczi, G. and Héja, E. and Jelencsik-Mátyus, K. and Laki, L. J. and Vadász, N. and Yang, Z. Gy. and Váradi, T.},
  booktitle={XVIII. Magyar Számítógépes Nyelvészeti Konferencia},
  year={2022},
  pages = {431--446},
  editors = {Berend, G. and Gosztolya, G. and Vincze, V.},
  address = {Szeged},
  publisher = {Szegedi Tudományegyetem, Informatikai Intézet}
}
```
