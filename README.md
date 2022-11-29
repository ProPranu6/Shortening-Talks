# Shortening-Talks

Shortening Talks Algorithm

Method 1 (TF-IDF):

Layer 1 : KeyWord Extraction using log(1+ Frequency) x log(Lines In Total/Lines Containing word) (TFIDF) Scores
Layer 2 : KeyWord Allotment to Sentences using Lev Ratios
Method 2 (Frequency):

Layer 1 : KeyWord Extraction using Frequency Scores
Layer 2 : KeyWord Allotment to Sentences using Lev Ratios
Method 3 (BERT Embedding + BERT Classifier):

Layer 1 : Sequence the words in a sentence and pass into BERT
Layer 2 : Top BERT Classifier to produce important/unimportant sentences
Method 4 (BERT Embedding + LexRank):

Layer1 : Sentense to BERT Embeddings Layer 2 : LexRank on sentence vecs and pick sentence vecs above set threshold rank
