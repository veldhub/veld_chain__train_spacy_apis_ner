# VELD chain to train NER models on apis data

#### m1

Quick experiment with spaCy's defaults, without pre-trained vectors.

Evaluation scores:
- NER P   75.36
- NER R   75.56
- NER F   75.46

Reproducable at commit: 4f6736c2d6fdcb37395a73767b2592d005227182

#### m2

Same as m2, but with pre-trained vectors from `de_core_news_lg`

- NER P   77.99 
- NER R   79.85 
- NER F   78.91 

Reproducable at commit: 6c352cd331ea893ccf9f0daf931c93b2832389a9 

