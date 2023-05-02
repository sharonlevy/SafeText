# SafeText


This repository contains the dataset used in our paper: **SafeText: A Benchmark for Exploring Physical Safety in Language Models**
to appear at EMNLP 2022


When using our dataset, please cite our paper:

```
@inproceedings{levy-etal-2022-safetext,
    title = "{S}afe{T}ext: A Benchmark for Exploring Physical Safety in Language Models",
    author = "Levy, Sharon  and
      Allaway, Emily  and
      Subbiah, Melanie  and
      Chilton, Lydia  and
      Patton, Desmond  and
      McKeown, Kathleen  and
      Wang, William Yang",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.emnlp-main.154",
    pages = "2407--2421",
}
```

The SafeText dataset comes in the form of *scenarios* and *advice pairs*. Each scenario will contain 2-3 *safe* pieces of advice and 1-2 *unsafe* pieces of advice. More details can be found in the paper. 

SafeText can be found in SafeText.json as a nested dictionary with the format seen below.

SafeText.json
* scenario
  * safe
    * list of safe advice
  * unsafe
    * list of unsafe advice
