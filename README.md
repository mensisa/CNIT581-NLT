# CNIT581-NLT Sentence Similarity
This repository is for Fall 2019 CNIT581-NLT class project.  
 For project ideas, click [here](https://docs.google.com/document/d/125JhN6XhmpnZ5nq2uthlHJNAeYQ7m2gv8A8pHmt-73o/edit)  
 For milestone 2 presentation, click [here](https://docs.google.com/presentation/d/1ZaZiEU2XsEFCUAA03z8qERim2d6MGDG9oSFAT9bVzwE/edit#slide=id.g78e23b0480_1_68)  
### Data
  * Add `glove.840B.300d.txt` and `stanford-corenlp-full-2018-02-27` under `data` folder
  * `sentence.txt` is the corpus for testing sentence similarity (Feel free to add more~)
  
### Usage
  * `glove_model` will take a long time to load(sad)
  * Word similarity is able to compute after loading `glove_model`
  * `nlp = StanfordCoreNLP(r'<your-directory>\data\stanford-corenlp-full-2018-02-27')`
  * Parsing results (dependency & Part-of-speech) are saved as `dict()`, which using **index** of sentences to retrive the `list` of parsing results

### Useful Tools
 * Stanford CoreNLP:    [:octocat:GitHub](https://github.com/Lynten/stanford-corenlp)
 * GloVe Loader Script: [:octocat:GitHub](https://github.com/lostkuma/loadGlove)
 * CodeNLP demo:        [Website](http://corenlp.run/)
 * Word2Vec demo:       [Website](http://bionlp-www.utu.fi/wv_demo/)
 * GloVe:               [Website](https://nlp.stanford.edu/projects/glove/)
