
# NLP / Text analytics 

## NLP life cycle 


![](E2E/E2E_chartflow.png)

## E2E Text Clening Pipe-line 


![](E2E/E2E/Textcleaning_pipeline.png)


## List of Text Preprocessing Steps
Remove HTML tags.
Remove extra whitespaces.
Convert accented characters to ASCII characters.
Expand contractions.
Remove special characters.
Lowercase all texts.
Convert number words to numeric form.
Remove numbers.

![](E2E/CommontextPreProcessing.PNG)

## Lowercasing
Lowercasing ALL your text data, although commonly overlooked, is one of the simplest and most effective form of text preprocessing. It is applicable to most text mining and NLP problems and can help in cases where your dataset is not very large and significantly helps with consistency of expected output.

## Tokenization
Tokenization is a step which splits longer strings of text into smaller pieces, or tokens. Larger chunks of text can be tokenized into sentences, sentences can be tokenized into words, etc. Further processing is generally performed after a piece of text has been appropriately tokenized. Tokenization is also referred to as text segmentation or lexical analysis. Sometimes segmentation is used to refer to the breakdown of a large chunk of text into pieces larger 

## Stemming
Stemming is the process of reducing inflection in words (e.g. troubled, troubles) to their root form (e.g. trouble). The “root” in this case may not be a real root word, but just a canonical form of the original word.
![](E2E/stemming_lemme.png)

## Lemmatization
Lemmatization on the surface is very similar to stemming, where the goal is to remove inflections and map a word to its root form. The only difference is that, lemmatization tries to do it the proper way. It doesn’t just chop things off, it actually transforms words to the actual root
![](E2E/diff_Lemmit_stemming.png)

## Stopword Removal
Stop words are a set of commonly used words in a language. Examples of stop words in English are “a”, “the”, “is”, “are” and etc. The intuition behind using stop words is that, by removing low information words from text, we can focus on the important words instead.

For example, in the context of a search system, if your search query is “what is text preprocessing?”, you want the search system to focus on surfacing documents that talk about text preprocessing over documents that talk about what is. This can be done by preventing all words from your stop word list from being analyzed. Stop words are commonly applied in search systems, text classification applications, topic modeling, topic extraction and others.
