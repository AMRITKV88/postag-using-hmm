# postag-using-hmm
Building a POS Tagger using HMM

## nltk.corpus.treebank.tagged_sents()

**What :** It takes a treebank corpus (a file of sentense) as i/p and gives the output as a list of sentences, each encoded as a list of (word,tag) tuples.

**What Type :** list(list(tuple(str,str)))

## nltk.corpus.treebank.chunked_sents()

**What :** It takes treebank corpus (a file of sentense) as i/p and gives the output as a list of sentences, each encoded as a shallow Tree. The leaves of these trees are encoded as (word, tag) tuples (if the corpus has tags) or word strings (if the corpus has no tags).

**What Type :** list(Tree)