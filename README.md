# Tokenization
Here I gonna make some operations on text and test posibilities of my NLP model
# First I impoer "spacy" and load "small madel in english" then i put text into my nlp object and make for loop on my text "printing sentences" 
# It figure out that dot after Mr. it's not the end of phrase
# Then i make same for loop buy for every word in my text, Now I gonna do this same with "nltk"
# So first i import nltk and download my object, then I ipmort "sent_tokenize" and put my text into it and it separate my sentence into two
# Now I gonna import "word_tokenize" and put my text inside, it will return me every token from my text
# In nltk You must try different optins because it have many algorithms and possibilities to customise, instead spacy figure out the best algorithm
# Then I go back to spacy and put some text to tekenize every word I also check types of every object I have 
# And check if spacy recognize type of word np. 'John' in not 'num' but if i tape '2' it sees that it is 'num' also '$' it sees that it is currency
# Now I gonna check types of every word in my text, so first it print token, then some types np. 'is_alpha, is_punct'
# I gonna load text with informations of students and change it into one text, I want to extract only emails of students from this text
# So I put text into nlp object and create empty list for emils, then I start for loop on my text and I set condition 
# if token is en eamil
