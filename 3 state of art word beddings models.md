# 3 state of art word beddings models

## [**Word2Vec**](<https://code.google.com/archive/p/word2vec/>)

```Python
word_embedding = WordEmbedding()
word_embedding.load(source='word2vec', file_path=word2vec_file_path)
print(word_embedding.get_vector(source='word2vec', word='apple'))
```



## [**GloVe**](<https://nlp.stanford.edu/projects/glove/>)

```Python
word_embedding = WordEmbedding()
word_embedding.load(source='glove', file_path=glove_file_path)
print(word_embedding.get_vector(source='glove', word='apple'))
```



## [**FastText**](<https://fasttext.cc/>)

```Python
word_embedding = WordEmbedding()
word_embedding.load(source='fasttext', file_path=fasttext_file_path)
print(word_embedding.get_vector(source='fasttext', word='apple'))
```

