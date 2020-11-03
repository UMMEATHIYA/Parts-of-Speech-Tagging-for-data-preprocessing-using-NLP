# Parts-of-Speech-Tagging-for-data-preprocessing-using-NLP
<h2><b>Note:- I have developed this Project entitled "Parts of Speech Tagging for Data Pre-Processing using NLP" with Flask mainframe API and python programming
language. It shows the sentence polarity and subjectivity values obtained with the help of package - "TextBlob", "nltk".</b></h2>
<h3><b>Overview</b></h3>
POS tagging is a process of categorizing each word in a sentence into nouns, verbs, pronouns, adjectives, conjunctions and determinants. Various Machine Learning
algorithms basic model depends on preprocessing of text. My proposed approach use lateral entries in the dictionary along with their information. Here, it mainly
depends on the frequency of occurrence of words in the dictionary.<br>
<h3><b>Existing System</b></h3>
We live in an era of digital technology enhancement, still identifying POS Tagging is much more difficult when compared to matching words to their independent parts
of speech via a dictionary method. It is quite different to sense that one word has two or more meanings based on their reference and the context they are being used.
It is difficult to individually classify and assign the parts of speech for words manually. Thus new types of words keep building up in the dictionary, as POS depends
on pre trained data it is not capable of scaling to newly introduced words.<br>
<h3><b>Proposed System</b></h3>
The objective of this paper is to increase automaticity and maintain high precision, while limiting the size of human made corpus. In my current work we approach the
task of POS tagging as an optimization problem.<br>
<h3><b>System Design</b></h3>
<h4><b>i)Tokenization</b></h4>
Tokenization is process of dividing the stream of text entered by the user into individual group of words/ phrases/ symbols which give a meaningful elements. These
process of division is the initial step which is further taken as the next level for the preprocessing. Tokenization is also referred to as text segmentation or
lexical analysis.<br>
<h4><b>ii)Lemmatization</b></h4>
Lemmatization is the process of grouping the words together with the same meaning which was obtained from the tokenization process. Lemmatization is like the same way
of stemming. So it connects words with similar sense with the other words. Text preprocessing combines both the process of stemming as well as lemmatization. Some
treat these two as same. Actually, lemmatization is preferred over Stemming because lemmatization does morphological analysis of the words.<br>
<h4><b>iii)Removal of Stop Words</b></h4>
The Removal of stop words is the process where the most commonly occurring words in the document are extracted and using these words would mean to contribute very
little meaning or contribute no help in the tagging system. Stop Words are also referred as the “Bag of Words”. These bag of words are commonly occurring for example
‘a’, ‘an’, ‘the’, etc words.<br>
<h4><b>iv)Parts of Speech Tagging</b></h4>
The Parts of Speech Tagging is the process of classifying each word entered in the text or sentence into its corresponding tagging system such as Noun, Verbs,
Pronouns, Determiners, Adjectives, Interjections, Conjunctions and many more.<br>
<h4><b>iv)Ambiguity Resolution</b></h4>
Given a sentence with ambiguous words, its most likely to split the words into its lexical categories with various meanings for the same words based on the context
and the information they are being referred in that particular situation.<br>
![alt text](https://www.google.com/imgres?imgurl=https%3A%2F%2Fmiro.medium.com%2Fmax%2F1170%2F1*CbZE2ZTBlmswW84Knjbqkg.png&imgrefurl=https%3A%2F%2Fmedium.com%2Fanalytics-vidhya%2Fpos-tagging-using-conditional-random-fields-92077e5eaa31&tbnid=AfAx9Vc53eu71M&vet=12ahUKEwjgtvuox-bsAhWJynMBHYRzDfcQMygAegUIARCkAQ..i&docid=UWim5wlIOufFIM&w=1170&h=545&q=parts%20of%20speech%20tagging%20in%20nlp&ved=2ahUKEwjgtvuox-bsAhWJynMBHYRzDfcQMygAegUIARCkAQ)
