# Classification-of-Writers-Texts
this project presents a neural network for text classification.
##
Let's use the Tokenizer function built into Keras to split the text and turn it into a matrix of numerical values
```ruby
tokenizer = Tokenizer(num_words=maxWordsCount, filters='', lower=True, split=' ', oov_token='unknown', char_level=False)
```
```num_words=maxWordsCount```- determine the maximum number of words/indexes, taken into account when teaching the texts

```filters='!"#$%&()*+,-./::<=>?@[\]^_{|}~\t\n'``` - we get rid of unnecessary characters

```lower=True``` - bring words to lower case

```split=''``` - splits words by a space

```char_level=False``` - tokenize on words (If true - each character will be treated as a separate token)
