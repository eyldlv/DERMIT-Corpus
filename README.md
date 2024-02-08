# DERMIT-Corpus
A multi-lingual corpus in German, Romansh and Italian

## Corpus
The parallel corpus is presented as JSON files, one per year.

### Parallel sentences
Tab seperated files containing parallel sentences in the three combinations: German-Romansh (DE-RM), German-Italian (DE-IT) and Romansh-Italian (RM-IT).

|Combination|Sentences|Tokens|Types|
|-----------|---------|------|-----|
|DE-RM      |106091   |1864886, 2377547|97385, 50869|
|DE-IT      |103441   |1848214, 2219378|96859, 58050|
|RM-IT      |102757   |2302374, 2165287|50014, 57642|


### Copyright
The copyright to the press releases lies with the Canton of Graubünden. Downloading the press releases is explicitly allowed. Commercial use is explicity prohibited. In any event, please consult the [copyright notice](https://www.gr.ch/de/Seiten/Impressum.aspx) on the cantnon's website.


## [Gold Standard](./gold_standard/)
A set of 600 parallel sentences (German-Romansh), manually annotated for word alignment. 




## Citation
If you use this corpus or the gold standard for published work, please cite my [paper](https://aclanthology.org/2023.swisstext-1.5.pdf):
```bibtex
@inproceedings{dolev-2023-mbert,
    title = "Does m{BERT} understand {R}omansh? Evaluating word embeddings using word alignment.",
    author = "Dolev, Eyal Liron",
    editor = {Ghorbel, Hatem  and
      Sokhn, Maria  and
      Cieliebak, Mark  and
      H{\"u}rlimann, Manuela  and
      de Salis, Emmanuel  and
      Guerne, Jonathan},
    booktitle = "Proceedings of the 8th edition of the Swiss Text Analytics Conference",
    month = jun,
    year = "2023",
    address = "Neuchatel, Switzerland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.swisstext-1.5",
    pages = "41--53",
}

```
