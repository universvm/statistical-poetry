# Random Forest

Gain(D, r) = E(D) - E(D|r) 

Where: 
E = entropy
D = dreams 
r = reality 

- Gain(D, r): (46.207058, 6.155667)

- E(D): The Persistence of Memory - Salvador Dalì

- E(D|r): Meditations - Marcus Aurelius 

## Forest:

- II.1,14,15,16
- III.1,3,5,13
- IV.2,3,4,7,10,12,14,17,24,25,26,27,28,39,43,47,49,51
- V.1,2,6,9,10,11,19,23,26
- VI.1,6,18,21,27,31,47,51,52,56,58,
- VII.2,7,8,10,15,18,20,21,22,23,29,49,56,73
- VIII.42,49,51,59
- IX.4,19,20
- X.8,11,29
- XI.1,4,18
- XII.4,22

## Explanation:

We start with an equation of information gain in the system. The point is to maximise the Information Gain after every split of the decision tree and minimize the entropy after the split. 

Here, the Gain(D, r) is in terms of dreams and reality. The term E(D) is the entropy of the dreams, ie. how realistic they are. They are represented my Dalì's magical Persistence of Memory, a classic painting from the surrealist artistic movement. 

The E(D|r), entropy of the dreams given the current reality, is represented my Marcus Aurelius' Meditations. I chose this book as it has inspired me to have a more realistic view on reality and embrace elements of stoic philosophy in my life. The book itself is a series of thoughts or principles according to which the Roman emperor lived his life. To me, each of them was a reminder about the human nature and a reflection on apathy, the insensitiveness towards pathological emotions. 

Since the algorithm is actually a random forest, I chose my favorite verses from the book of meditations divided by chapter. The idea being that the more decision trees are built, the higher the accuracy of the model. 
