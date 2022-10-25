# SafeText


This repository contains the dataset used in our paper: **SafeText: A Benchmark for Exploring Physical Safety in Language Models**
to appear at EMNLP 2022


When using our dataset, please cite our paper:

```
@article{levy2022safetext,
  title={SafeText: A Benchmark for Exploring Physical Safety in Language Models},
  author={Levy, Sharon and Allaway, Emily and Subbiah, Melanie and Chilton, Lydia and Patton, Desmond and McKeown, Kathleen and Wang, William Yang},
  journal={arXiv preprint arXiv:2210.10045},
  year={2022}
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
