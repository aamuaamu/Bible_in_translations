# Bible_in_translations

We analyze the distribution of different parts-of-speech and the count of each word in the Bible in 14 different languages:

English
Danish
Dutch
German
Norwegian
French
Italian
Portuguese
Spanish
Romanian
Russian
Polish
Japanese
Greek

The bible is made available by Christos Christodoulopoulos and Mark Steedman here:
[https://github.com/christos-c/bible-corpus](https://github.com/christos-c/bible-corpus)

We use the NLP models provided by spaCy to do the part-of-speech tagging. For detail, see spaCy's documentation:
[https://spacy.io/usage/models](https://spacy.io/usage/models)

Bible_preparation.py:
Download the bibles, tag the part-of-speech of each word, save the number of occurence of each verb in each book of a language.

Bible_word_counts:
Count the number of occurence of each part-of-speech in each language, ignoring PUNCT, SYM, SPACE, X.
List the most common nouns (including common nouns and proper nouns) in each language.

Bible_eng_translation:
Translate the most common nouns in each langauge into English.
