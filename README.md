# VELD chain to train NER models on apis data

Trained at chain: https://gitlab.oeaw.ac.at/acdh-ch/nlp/veld_chain_7_train

#### m1

Quick experiment with spaCy's defaults, without pre-trained vectors.

Evaluation scores:
- P: 75.36
- R: 75.56
- F: 75.46

Reproducable at: https://gitlab.oeaw.ac.at/acdh-ch/nlp/veld_chain_7_train/-/commit/4f6736c2d6fdcb37395a73767b2592d005227182

#### m2

Same as m1, but with pre-trained vectors from `de_core_news_lg`.

Evaluation scores:
- P: 77.99 
- R: 79.85 
- F: 78.91 

Reproducable at: https://gitlab.oeaw.ac.at/acdh-ch/nlp/veld_chain_7_train/-/commit/6c352cd331ea893ccf9f0daf931c93b2832389a9

#### m3

Basic training with Transformer. Config as suggested by spaCy.

Evaluation scores:
- P: 79.72 
- R: 84.28 
- F: 81.93 

Reproducable at: https://gitlab.oeaw.ac.at/acdh-ch/nlp/veld_chain_7_train/-/commit/5861ed24c534b108759bb6bbb0bc3e7e742aabb6
