Built 2 models of word2vec using review corpus. The models cbow and skipgram are made using Negative Sampling.
1. CBOW model:
	Source code is in Cbow.ipynb notebook file which has separate cells for all the processes. Generating dictionary, generating training data, processing training data, storing pretrained models and visualizing the vectors.
	Pretrained embeddings are stored in cbow_params2 and dictionary mapping is stored in dictionary_mappingcbow2.
	-> To load pretrained model use load_model() api.
	-> To get vector of the word, vector(word)
	-> To get similar words of word, similar_words(word,count)
	-> To get similar vectors of word, similar_vectors(word,count)
2. Skipgram model:
	Source code is in NegativeSampling.ipynb notebook file which has separate cells for all the processes. Generating dictionary, generating training data, processing training data, storing pretrained models and visualizing the vectors.
        Pretrained embeddings are stored in skipgram_parameters2 and dictionary mapping is stored in dictionary_mappingsg2.                                         -> To load pretrained model use load_model() api.
        -> To get vector of the word, vector(word)
        -> To get similar words of word, similar_words(word,count)
        -> To get similar vectors of word, similar_vectors(word,count)

All the answers to the queries are addressed in WordComparisions.pdf. 
