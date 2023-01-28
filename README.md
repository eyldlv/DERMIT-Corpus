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



## [Gold Standard](./gold_standard/)
A set of 600 parallel sentences (German-Romansh), manually annotated for word alignment. 

## Citation
If you use this corpus or gold standard for published work, please cite my [master's thesis](https://www.cl.uzh.ch/dam/jcr:5eda2d8a-fe61-4860-82c1-421e2e1d18c3/MA_thesis_Digital_Linguistics_Eyal_Dolev_2022_12_11.pdf):

```bibtex
@mastersthesis{mathesis-dolev-2022,
  author  = "Eyal Liron Dolev",
  title   = "Using Multilingual Word Embeddings for Similarity-Based Word Alignments in a Zero-Shot Setting: Tested on the Case of German–Romansh",
  school  = "University of Zurich",
  year    = "2022",
  url     = "https://www.cl.uzh.ch/dam/jcr:5eda2d8a-fe61-4860-82c1-421e2e1d18c3/MA_thesis_Digital_Linguistics_Eyal_Dolev_2022_12_11.pdf"
}

```