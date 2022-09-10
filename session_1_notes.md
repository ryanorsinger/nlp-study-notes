# CLJ - NLP

## Dimid's presentation

## Properties of human language:
- Displacement - we can talk about remote things in space/time
- Nurture - language isn't only genetic, it requires socialization
- Arbitrariness - allows us to talk about abstract/arbitrary concepts and ideas: coupling a sign and a concept
- Recursion - language is recursive



## Linguistics 101: 
- Phonetics: sounds and their articulation like labials, labio-dentals, palatals, friccatives, nasals, plosives, etc..
- Morphology: how different sub-units make a word. Take "independent". "in" is the prefix, depend is the verb, and theses basic parts are morphemes. 
    - Inflection: we can inflect a word in time, in person, aspect, mode
    - Arrangement morphemes: turn a word from a noun to a verb, for example.
- Syntax: parts of speech, syntactic trees, phrase definitions, noun phrases, verb phrases, adjective phrases

## Why is NLP difficult?
- She ate the spaghetti with meatballs. She ate the spaghetti with chopsticks.


## Concepts
- dependency grammar: avoids the concept of constituents. this is a root/recursion
- "Universal Dependencies" is a large effort with industry/academia for defining all these relations for many languages (100 languages)

Lemmatization removes inflectional and derivational pieces



Goal is to determine "intent"
ATIS dataset
https://www.kaggle.com/datasets/hassanamin/atis-airlinetravelinformationsystem



http://www.futurile.net/2020/02/20/python-from-clojure-with-libpython-clj/

## Daniel's live coding intro to Spacy in Clojure
- https://spacy.io/usage/visualizers
- Rasa NLU JSON format is a format for annotating text for NLU
- We can teach Spacy about NEW entities!



## Interop
- in-process interoperability
- out-of-process interoperability
- "zero copy" - you could take the python numpy array and write a clojure function and apply this function to the array and get a new array without ever copying the array to the clojure runtime.
- https://github.com/scicloj/scicloj.ml from Carsen Behring
- https://github.com/clj-python/libpython-clj and Chris Nuernberger
