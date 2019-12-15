# LanguageDetector

The implementation of Bayes Rule over trigrams extracted from the given language text.
Given a string in any of the 41 languages whose profiles have been created from wikitext dataset (taken from Google Langauge Detection Api)

The core logic of the implementation is P(Ck|x) is directly proportional to P(Ck)*P(x|Ck) where P(Ck|x) is the probability of a string belonging to language category Ck given a trigram obtained x
