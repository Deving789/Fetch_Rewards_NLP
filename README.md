# Fetch_Rewards_NLP
Using 3 sentences to figure out which are most alike. 

# The objective is to write a program that takes two or more texts and uses a metric to determine how similar they are. Documents that are exactly the same get a score of 1 and those that are not a like score a 0.

## Questions to answer

- Do you count punctuation or only words?

Punctuation should always be looked at in NLP because the same word can have a different meaning. One example is 'wow' or 'WOW', this word can be used in sarcasm,excitment -- any sort of strong feeling but with differen't meaning.

- Which words should matter in the similarity comparison?

The words that should matter most in this model are fetch, rewards, earn, points,will, get and easy.

- Do you care about the ordering of words?

The ordering of words does not matter. Any combination of the listed words is good advertisement for the company.

- What metric do you use to assign a numerical value to the similarity?
1.0 or 0.0

- What type of data structures should be used? (Hint: Dictionaries and lists are particularly helpful data structures that can be leveraged to calculate the similarity of two pieces of text.)

The data structure used in this particular instance is a list. It is a list that we turn into an array.

Taking a peak at the code:
- Taking the sentence and turning it into a list, then taking away unimportant words to further disect.
<img width="1377" alt="1" src="https://user-images.githubusercontent.com/67278193/103719910-1fad3380-4f98-11eb-9f1b-0bf861580f01.png">

- Creating hashing frequency and IDF so the data can be put into training & test sets for machine learning.
<img width="1378" alt="Screen Shot 2021-01-05 at 8 53 17 PM" src="https://user-images.githubusercontent.com/67278193/103719918-22a82400-4f98-11eb-815c-85378b235bb6.png">
