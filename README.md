# CNIT581-NLT
This repository is for Fall 2019 CNIT581-NLT class project
### Data
  * Add `glove.840B.300d.txt` and `stanford-corenlp-full-2018-02-27` under `data` folder
  * `sentence.txt` is the corpus for testing sentence similarity
  
### Usage
  * `glove_model` will take a long time to load
  * Word similarity is able to compute after loading `glove_model`
  * `nlp = StanfordCoreNLP(r'<your-directory>\data\stanford-corenlp-full-2018-02-27')`
  * Parsing results (dependency & Part-of-speech) are saved as `dict()`, which using **index** of sentences to retrive the `list` of parsing results
